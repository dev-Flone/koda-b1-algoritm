# Algoritma Perhitungan

## Deskriptif
```
1. Mulai
2. Masukkan variabel A
3. Masukkan variabel B
4. Hitung hasil dari A + B
5. Tampilkan Hasil
6. Selesai
```

## Flowchart
``` mermaid
flowchart TD
    start((start)) --> A[/Input A/] --> B[/Input B/]
    B --> hasil[A + B] 
    hasil --> output[Tampilkan Hasil]--> stop(((stop)))

```

## Pseudo-Code
``` pesudo-Code
DECLARE A : INTEGER
DECLARE B : INTEGER
DECLARE HASIL : INTEGER

INPUT A
INPUT B
HASIL <- A + B
OUTPUT "Hasil Perhitungan adalah", HASIL
```
