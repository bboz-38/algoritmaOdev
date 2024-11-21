# Dizi: [16, 21, 11, 8, 12, 22]

## 1. Bölme aşaması:
[16, 21, 11] ve [8, 12, 22]
 Sol alt dizi: [16, 21, 11]

[16] ve [21, 11]
[21] ve [11] (birleştir: [11, 21])
[16] ve [11, 21] (birleştir: [11, 16, 21])
 Sağ alt dizi: [8, 12, 22]

[8] ve [12, 22]
[12] ve [22] (birleştir: [12, 22])
[8] ve [12, 22] (birleştir: [8, 12, 22])

## 2. Birleştirme aşaması:
Sol dizi: [11, 16, 21]
Sağ dizi: [8, 12, 22]
Birleştir: [8, 11, 12, 16, 21, 22]

## Sonuç:
Sıralı dizi: [8, 11, 12, 16, 21, 22]

# Big-O Gözterimi

En kötü durum (Worst-case): O(nlogn) 


Ortalama durum (Average-case): O(nlogn) 


En iyi durum (Best-case):  O(nlogn)







