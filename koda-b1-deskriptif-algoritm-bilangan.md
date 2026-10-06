## Menentukan bilangan ganjil genap

```
1. Mulai
2. Melakukan pembagian terhadap angka yang akan di cek dengan angka dua
3. Jika menghasilkan sisa, berarti angka ganjil
4. Sebaliknya, jika tidak menghasilkan sisa berarti genap
5. Selesai
```

## Flowchart Ganjil Genap
``` mermaid
flowchart TD
    start((start)) --> angka[/Angka/]--> modulus[Modulus 2] --> Decision{Sisa Bagi = 0} --> Yes[Genap]
    Decision --> No[Ganjil]
    Yes --> stop(((stop)))
    No --> stop
    
```