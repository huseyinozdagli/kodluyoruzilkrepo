# Veri Yapıları ve Algoritmalar > Insertion Sort Projesi


## Proje 1

**[22,27,16,2,18,6] -> Insertion Sort**


> Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Insertion Sort, iskambil kartlarını elinizde sıralama şekline benzer şekilde çalışan basit bir sıralama algoritmasıdır. Dizi sanal olarak sıralanmış ve sıralanmamış bir bölüme ayrılmıştır. Sıralanmamış parçadan değerler alınır ve sıralanan parçada doğru konuma yerleştirilir.

**Sol taraftaki üzeri çizili sayılar sıralanmış olduğu anlamına gelir.**

1) 22 27 16 2 18 6     //Başlangıç


2) ~~22~~ 27 16 2 18 6 //Sıralanmış kısımda 0 pozisyonundaki kayıtla başlıyoruz ve 1 pozisyonundaki kaydı(mavi) sıralanana kadar sola hareket ettireceğiz.


3) ~~22~~ 27 16 2 18 6 //Pozisyon 1'de kayıt işleniyor


4) ~~22~~ 27 16 2 18 6 //Kaydı doğru konuma gelene kadar sola hareket ettirin.


5) ~~22~~ 27 16 2 18 6 //Pozisyon 2'de kayıt işleniyor


6) ~~22~~ 27 16 2 18 6 //Kaydı doğru konuma gelene kadar sola hareket ettirin.


7) ~~22~~ 16 ~~27~~  2 18 6  //Yer değiştirin


8) 16 ~~22~~  ~~27~~  2 18 6  //Yer değiştirin


9) 16 ~~22~~  ~~27~~  2 18 6 //Pozisyon 3'de kayıt işleniyor


10) 16 ~~22~~  ~~27~~  2 18 6 //Kaydı doğru konuma gelene kadar sola hareket ettirin.


11)  16 ~~22~~  2 ~~27~~   18 6 //Yer değiştirin


12) 16  2 ~~22~~  ~~27~~   18 6 //Yer değiştirin


13)  2 ~~16~~  ~~22~~  ~~27~~   18 6 //Yer değiştirin


14) 2 ~~16~~  ~~22~~  ~~27~~   18 6 //Pozisyon 4'de kayıt işleniyor


15)  2 ~~16~~  ~~22~~  ~~27~~   18 6  //Kaydı doğru konuma gelene kadar sola hareket ettirin.


16) 2 ~~16~~  ~~22~~ 18 ~~27~~ 6 //Yer değiştirin


17) 2 ~~16~~ 18  ~~22~~  ~~27~~  6 //Yer değiştirin


18) 2 ~~16~~ 18  ~~22~~  ~~27~~  6 //Pozisyon 5'de kayıt işleniyor


19)  //Kaydı doğru konuma gelene kadar sola hareket ettirin.


20) 2 ~~16~~ 18  ~~22~~ 6   ~~27~~   //Yer değiştirin


21) 2 ~~16~~ 18  6  ~~22~~    ~~27~~  //Yer değiştirin


22) 2 ~~16~~ 6 ~~18~~    ~~22~~    ~~27~~  //Yer değiştirin


23) 2  6 ~~16~~  ~~18~~    ~~22~~    ~~27~~  //Yer değiştirin


24)  ~~2  6~~ ~~16~~  ~~18~~    ~~22~~    ~~27~~ // Tamamlandı !

---

>Big-O gösterimini yazınız.

**O(n^2)**

---

```
Time Complexity: 
Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması,
Best case: Aradığımız sayının dizinin en başında olması.
```

---
>Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

**Average Case**

---

>[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.


1) 3 ~~7~~ 5 8 2 9 4 15 6

2) 3 ~~7~~ 5 8 2 9 4 15 6

3) 3 5 ~~7~~  8 2 9 4 15 6

4) 3 5 2 ~~7~~  ~~8~~ 9 4 15 6
