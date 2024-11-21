# [22,27,16,2,18,6] -> Insertion Sort Sıralaması
## Sıralama Adımları
1.	İlk eleman: 22. Zaten tek başına sıralıdır.
22,27,16,2,18,622, 27, 16, 2, 18, 622,27,16,2,18,6

2.	İkinci eleman: 27. 22'den büyük olduğu için yer değiştirme gerekmez.
22,27,16,2,18,622, 27, 16, 2, 18, 622,27,16,2,18,6

3.	Üçüncü eleman: 16. 27'den küçük, 22'den de küçük. 16 doğru yere yerleştirilir.
16,22,27,2,18,616, 22, 27, 2, 18, 616,22,27,2,18,6

4.	Dördüncü eleman: 2. En küçük eleman olduğu için en başa yerleştirilir.
2,16,22,27,18,62, 16, 22, 27, 18, 62,16,22,27,18,6

5.	Beşinci eleman: 18. 27'den küçük, 22'den küçük ama 16'dan büyük. 16 ile 22 arasına yerleştirilir.
2,16,18,22,27,62, 16, 18, 22, 27, 62,16,18,22,27,6

6.	Altıncı eleman: 6. 16'dan küçük olduğu için ikinci sıraya yerleştirilir.
2,6,16,18,22,272, 6, 16, 18, 22, 272,6,16,18,22,27

## Sonuç
Dizi sıralandıktan sonra;
2,6,16,18,22,27

# Big O Gösterimi
Best Case Big-O: O(n)
Worst Case Big-O: O(n^2)
Average Case Big-O: O(n^2)

## Sonuç
Verilen dizi (22,27,16,2,18,622, 27, 16, 2, 18, 622,27,16,2,18,6) sırasız olduğu için ortalama veya en kötü durum senaryosunda değerlendirilir.
Bu nedenle Big-O Gösterimi: O(n^2)

# [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımı

## 1. Adım:
Sıralanmamış kısım: 7,3,5,8,2,9,4,15,
•	En küçük eleman: 2
•	2, ilk eleman olan 7 ile yer değiştirir.
Yeni dizi:
2,3,5,8,7,9,4,15,62

## 2. Adım:
Sıralanmamış kısım: 3,5,8,7,9,4,15,6
•	En küçük eleman: 3
•	3, zaten doğru konumunda (yer değiştirme gerekmez).
Yeni dizi:
2,3,5,8,7,9,4,15,6

## 3. Adım:
Sıralanmamış kısım: 5,8,7,9,4,15,6En küçük eleman: 4
•	4, 5 ile yer değiştirir.
Yeni dizi:
2,3,4,8,7,9,5,15,6

## 4. Adım:
Sıralanmamış kısım: 8,7,9,5,15,6
•	En küçük eleman: 5
•	5, 8 ile yer değiştirir.
Yeni dizi:
2,3,4,5,7,9,8,15,6

## İlk 4 Adım Sonrası Dizi:
2,3,4,5,7,9,8,15,6



