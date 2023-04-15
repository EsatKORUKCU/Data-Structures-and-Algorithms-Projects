[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.


---------------------------------
Merge Sort :  Diziyi ikiye böl ve tek elaman kalana kadar böl sonra bölümleri kendi içinde sırala ve tekrar birleştir mantıgı ile yapılır.

[16,21,11,8,12,22]

[16,21,11]  ---- [8,12,22]     1.Aşama dizi ortadan ikiye bölündü 

[16] - [21,11] ----- [8] - [12,22] 2.Aşama alt bölümler tekra ikiye bölündü

[16] -[21] - [11] ---- [8] - [12]- [22] 3.Aşama  Dizi elemanları tek olana dek bölünmüş oldu.

[16] - [11,21]  ----  [8] - [12,22] 4.aşama sırlama başladı

[11,16,21] ---- [8,12,22] 5.Aşama alt bölümler kendi aralarında sıralndı

[8,11,12,16,21,22] 6.Sıralanarak tekrar birleştirildi.



Big-O Gösterimi: O(nlogn)
