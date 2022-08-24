# binarysearchtree

*[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]* dizisinin Binary-Search-Tree a�amalar�n� yaz�n�z.
---

Root 7'dir. 5<7 oldu�undan 5, root'un soluna gider.

||7
|
5|


1<7 oldu�undan 1, root'un soluna, 1<5 oldu�u i�in 5'in de soluna gider.

|||7
|
||5
|1

8>7 oldu�undan 8, root'un sa��na gider.

|||7||
|
||5||8
|1

3<7 oldu�undan 3, root'un soluna, 3<5 oldu�undan 5'in de soluna, 3>1 oldu�u i�in de 1'in sa��na gider.

|||7||
|
||5||8
|1
||3

6<7 oldu�undan 6, root'un soluna, 6>5 oldu�undan 5'in sa��na gider.

|||7||
|
||5||8
|1||6
||3

0<7 oldu�undan 0, root'un soluna, 0<5 oldu�undan 5'in de soluna, 0<1 oldu�u i�in 1'in de soluna gider.

||||7||
|
|||5||8
||1||6
0||3

9>7 oldu�undan 9, root'un sa��na, 9>8 oldu�u i�in 8'in de sa��na gider.

||||7||
|
|||5||8
||1||6||9
0||3

4<7 oldu�undan 4, root'un soluna, 4<5 oldu�undan 5'in de soluna, 4>1 oldu�undan 1'in sa��na, 4>3 oldu�undan 3'�n de sa��na gider.

||||7||
|
|||5||8
||1||6||9
0||3
||||4

2<7 oldu�undan 2, root'un soluna, 2<5 oldu�undan 5'in de soluna, 2>1 oldu�undan 1'in sa��na, 2<3 oldu�undan 3'�n soluna gider.

||||7||
|
|||5||8
||1||6||9
0||3
||2||4

[Patika.dev](https://www.patika.dev.tr)