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
### Keliling Lingkaran
``` mermaid
flowchart TD
    start((Start)) --> jari[/jari-jari/] --> luaskeliling{Luas/Keliling}
    luaskeliling --> luas[Luas] --> phi{22/7 Jika bilangan habis dibagi 7}
    luaskeliling --> keliling[Keliling] --> phi2{22/7 Jika jari-jari habis dibagi 7}

    phi --> yl[Yes]
    phi --> nl[No]

    yl --> hitungLuas[L = 22/7 x r x r]
    nl --> hitungLuas2[L = 3.14 x r x r]


    phi2 --> yk[Yes]
    phi2 --> nk[No]

    yk --> hitungKeliling[K = 2 x 22/7 x r]
    nk --> hitungKeliling2[K = 2 x 3.14 x r]

    hitungLuas --> stop(((Stop)))
    hitungLuas2 --> stop(((Stop)))
    hitungKeliling --> stop(((Stop)))
    hitungKeliling2 --> stop(((Stop)))

```