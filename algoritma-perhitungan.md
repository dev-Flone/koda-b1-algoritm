## Deskriptif
```
1. Mulai
2. Masukkan variabel A
3. Masukkan variabel B
4. Masukkan variabel C
4. Hitung hasil dari A x B + C
5. Tampilkan Hasil
6. Selesai
```
## Flowchart
``` mermaid
flowchart TD
    start((start))
    A[/A = 1/]
    B[/B = 1/]
    C[/C = 0/]
    Hasil[A x B + C]
    Output[Tampilkan Hasil]
    stop(((stop)))

    start --> A --> B --> C --> Hasil --> Output --> stop
```
## Pseudo-Code
``` pesudo-code
DECLARE A : INTEGER
DECLARE B : INTEGER
DECLARE C : INTEGER
DECLARE Hasil : INTEGER

A <- 1
B <- 1
C <- 0
Hasil <- A * B + C
OUTPUT "Hasil perhitungan adalah", Hasil
```
