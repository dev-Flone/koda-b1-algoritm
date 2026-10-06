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