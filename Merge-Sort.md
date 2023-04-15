[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


---------------------------------
Merge Sort :  Diziyi ikiye böl ve tek elaman kalana kadar böl sonra bölümleri kendi içinde sırala ve tekrar birleştir mantıgı ile yapılır.

[16,21,11,8,12,22]

[16,21,11]  ---- [8,12,22]

[16] - [21,11] ----- [8] - [12,22]

[16] -[21] - [11] ---- [8] - [12]- [22]

[16] - [11,21]  ----  [8] - [12,22]

[11,16,21] ---- [8,12,22]

[8,11,12,16,21,22]



Big-O Gösterimi: O(nlogn)
