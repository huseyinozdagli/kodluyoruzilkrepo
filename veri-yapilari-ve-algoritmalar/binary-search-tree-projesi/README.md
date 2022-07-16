# Veri Yapıları ve Algoritmalar > Merge Sort Projesi

## Proje 3
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.**

**Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.**

---

1) Root(Kök düğüm) 7'dir. Rootun sağında veya solunda şuan birşey bulunmaz.

![1-adim](https://github.com/huseyinozdagli/patika.dev/blob/main/veri-yapilari-ve-algoritmalar/binary-search-tree-projesi/1-adim.png)


2) 5, 7'den küçük olduğu için 7'nin sol düğümüne eklenir.

![2-adim](https://github.com/huseyinozdagli/patika.dev/blob/main/veri-yapilari-ve-algoritmalar/binary-search-tree-projesi/2-adim.png)

3) 1, 7'den küçük olduğu için 7'nin sol düğümüne eklenir. 1, 5'den küçük olduğu için 5'in sol düğümüne eklenir.

![3-adim](https://github.com/huseyinozdagli/patika.dev/blob/main/veri-yapilari-ve-algoritmalar/binary-search-tree-projesi/3-adim.png)

4) 8, 7'den büyük olduğu için 7'nin sağ düğümüne eklenir.

![4-adim]([/4-adim.png](https://github.com/huseyinozdagli/patika.dev/blob/main/veri-yapilari-ve-algoritmalar/binary-search-tree-projesi/4-adim.png))

5) 3, 7'den küçük olduğu için 7'nin sol düğümüne eklenir. 3, 5'den küçük olduğu için 5'in sol düğümüne eklenir. 3, 1'den büyük olduğu için 1'in sağ düğümüne eklenir.

![5-adim]([/5-adim.png](https://github.com/huseyinozdagli/patika.dev/blob/main/veri-yapilari-ve-algoritmalar/binary-search-tree-projesi/4-adim.png))

6) 6, 7'den küçük olduğu için 7'nin sol düğümüne eklenir. 6, 5'den büyük olduğu için 5'in sağ düğümüne eklenir.

![6-adim](/6-adim.png)

7) 0, 7'den küçük olduğu için 7'nin sol düğümüne eklenir. 0, 5'den küçük olduğu için 5'in sol düğümüne eklenir. 0, 1'den küçük olduğu için 1'in sol düğümüne eklenir.

![7-adim](/7-adim.png)

8) 9, 7'den büyük olduğu için 7'nin sağ düğümüne eklenir. 9, 8'den büyük olduğu için 8'in sağ düğümüne eklenir.

![8-adim](/8-adim.png)

9) 4, 7'den küçük olduğu için 7'nin sol düğümüne eklenir. 4, 5'den küçük olduğu için 5'in sol düğümüne eklenir. 4, 1'den büyük olduğu için 1'in sağ düğümüne eklenir. 4, 3'den büyük olduğu için 3'ün sağ düğümüne eklenir.

![9-adim](/9-adim.png)

10) 2, 7'den küçük olduğu için 7'nin sol düğümüne eklenir. 2, 5'den küçük olduğu için 5'in sol düğümüne eklenir. 2, 1'den büyük olduğu için 1'in sağ düğümüne eklenir. 2, 3'den küçük olduğu için 3'ün sol düğümüne eklenir.

![10-adim](/10-adim.png)
