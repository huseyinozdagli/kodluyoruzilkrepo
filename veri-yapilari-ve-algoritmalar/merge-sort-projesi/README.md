# Veri Yapıları ve Algoritmalar > Merge Sort Projesi

## Proje 2
**[16,21,11,8,12,22] -> Merge Sort**

>Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

1) Diziyi ortadan ikiye bölünmeyecek duruma hale gelene kadar ikiye bölüp en son çıkan parçaları kendi aralarında sıralıyoruz.


![left-merge](https://github.com/huseyinozdagli/patika.dev/blob/main/veri-yapilari-ve-algoritmalar/merge-sort-projesi/left-merge.png)

---

2) Sol tarafın sıralanması tamamlandı.



![left-merge-complete](https://github.com/huseyinozdagli/patika.dev/blob/main/veri-yapilari-ve-algoritmalar/merge-sort-projesi/left-merge-complete.png)

---

3) Kalan kısmı ikiye bölünmeyecek duruma hale gelene kadar ikiye bölüp en son çıkan parçaları kendi aralarında sıralıyoruz.


![right-merge](https://github.com/huseyinozdagli/patika.dev/blob/main/veri-yapilari-ve-algoritmalar/merge-sort-projesi/right-merge.png)

---

4) Sağ tarafın sıralanması tamamlandı.


![right-merge-complete](https://github.com/huseyinozdagli/patika.dev/blob/main/veri-yapilari-ve-algoritmalar/merge-sort-projesi/right-merge-complete.png)

---

5) Diziyi birleştirdiğimizde sıralı diziyi elde ediyoruz.

![merge-complete](/https://github.com/huseyinozdagli/patika.dev/blob/main/veri-yapilari-ve-algoritmalar/merge-sort-projesi/sort-done.png)

---


> Big-O gösterimini yazınız.

**O(n*log n)**






