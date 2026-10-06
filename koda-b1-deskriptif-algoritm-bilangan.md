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
    start((start)) --> angka[/Angka/]--> modulus[Modulus 2] --> Decision{Sisa Bagi = 0} --> Yes@{shape: rect} --> genap[genap]
    
    Decision --> No --> ganjil[ganjil]
    
    genap --> stop(((stop)))
    ganjil --> stop
    
```

## Pseudo-Code
``` pseudo-code
DECLARE Num : INTEGER

FOR Num <- 0 TO 100 STEP 1
    IF Num % 2 = 0 THEN
        OUTPUT Num, "adalah Bilangan Genap"
    ELSE
        OUTPUT Num, "adalah Bilangan Ganjil"
    ENDIF
NEXT Num
```
