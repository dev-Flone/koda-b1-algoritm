# Menghitung luas dan keliling lingkaran

## Keliling Lingkaran
```
1. Mulai
2. Tentukan nilai jari-jari
3. Gunakan phi = 22/7 jika jari-jari habis dibagi 7
4. Gunakan 3.14 jika tidak
5. Tentukan ingin menghitung Luas atau Keliling
6. Rumus Luas, L = phi x r x r || Rumus Keliling, K = 2 x phi x r
7. Selesai
```

## Flowchart
### Luas Keliling Lingkaran
``` mermaid
flowchart TD
    start((Start)) --> jari[/jari-jari/] --> phi[phi = 3.14]
    phi --> luaskeliling{Hitung Luas} --> yes@{ shape: text, label: "Yes" }
    luaskeliling --> no@{ shape: text, label: "No" }

    yes --> luas[L = phi x r x r]
    no --> keliling[K = 2 x phi x r]

    luas --> stop(((stop)))
    keliling --> stop

```

## Pseudo-Code
``` pseudo-code
DECLARE phi : REAL
DECLARE r : REAL
DECLARE L : REAL
DECLARE K : REAL
DECLARE lork : INTEGER

L <- phi * r * r
K <- 2 * phi * r

OUTPUT "Masukkan Nilai r: "
INPUT r

IF r % 7 = 0 THEN
    phi <- 22/7
ELSE
    phi <- 3.14
ENDIF

IF lork == 1 THEN
    OUTPUT "Luas Lingkaran = ", L
ELSE
    OUTPUT "Keliling Lingkaran = ", K
ENDIF
```
