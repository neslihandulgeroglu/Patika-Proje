# Patika-Proje
Veri yapıları ve algoritmalar
Proje1
[22,27,16,2,18,6]
1.	Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
o	[22,27,16,2,18,6]
o	[2,27,16,22,18,6]
o	[2,6,16,22,18,27]
o	[2,6,16,22,18,27]
o	[2,6,16,18,22,27]
o	[2,6,16,18,22,27]
2.	Big-O gösterimini yapınız.
o	[22,27,16,2,18,6] 6 sayı tarandı (n)
o	[2,27,16,22,18,6] 5 sayı tarandı (n-1)
o	[2,6,16,22,18,27] 4 sayı tarandı (n-2)
o	[2,6,16,22,18,27] 3 sayı tarandı (n-3)
o	[2,6,16,18,22,27] 2 sayı tarandı (n-4)
o	[2,6,16,18,22,27] 1 sayı tarandı (1)
Toplam işlem sayısı n + (n-1) + (n-2) + ... + 1 = (n^2+n)/2 olduğundan O(n^2) diyebiliriz.
3.	Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer
•	[2,6,16,18,22,27] sıralı dizisinde 18 sayısı ortalarda olduğundan Average Case kapsamına girmektedir.
4.	[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
o	[7,3,5,8,2,9,4,15,6]
o	[2,3,5,8,7,9,4,15,6]
o	[2,3,5,8,7,9,4,15,6]
o	[2,3,4,8,7,9,5,15,6]

