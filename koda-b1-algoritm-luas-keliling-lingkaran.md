# Menghitung luas dan keliling lingkaran

## Keliling Lingkaran
```
1. Mulai
2. Gunakan 22/7 jika habis dibagi 7
3. Jika tidak, gunakan 3.14
4. 2 dikalikan phi, lalu dikalikan dengan jari-jari
5. Selesai
```

## Luas Lingkarang
```
1. Mulai
2. Gunakan 22/7 jika habis dibagi 7
3. Jika tidak, gunakan 3.14
4. phi dikalikan dengan jari-jari kuadrat
5. Selesai
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