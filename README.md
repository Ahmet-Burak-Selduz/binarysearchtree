# binarysearchtree

*[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]* dizisinin Binary-Search-Tree aþamalarýný yazýnýz.
---

Root 7'dir. 5<7 olduðundan 5, root'un soluna gider.

||7
|
5|


1<7 olduðundan 1, root'un soluna, 1<5 olduðu için 5'in de soluna gider.

|||7
|
||5
|1

8>7 olduðundan 8, root'un saðýna gider.

|||7||
|
||5||8
|1

3<7 olduðundan 3, root'un soluna, 3<5 olduðundan 5'in de soluna, 3>1 olduðu için de 1'in saðýna gider.

|||7||
|
||5||8
|1
||3

6<7 olduðundan 6, root'un soluna, 6>5 olduðundan 5'in saðýna gider.

|||7||
|
||5||8
|1||6
||3

0<7 olduðundan 0, root'un soluna, 0<5 olduðundan 5'in de soluna, 0<1 olduðu için 1'in de soluna gider.

||||7||
|
|||5||8
||1||6
0||3

9>7 olduðundan 9, root'un saðýna, 9>8 olduðu için 8'in de saðýna gider.

||||7||
|
|||5||8
||1||6||9
0||3

4<7 olduðundan 4, root'un soluna, 4<5 olduðundan 5'in de soluna, 4>1 olduðundan 1'in saðýna, 4>3 olduðundan 3'ün de saðýna gider.

||||7||
|
|||5||8
||1||6||9
0||3
||||4

2<7 olduðundan 2, root'un soluna, 2<5 olduðundan 5'in de soluna, 2>1 olduðundan 1'in saðýna, 2<3 olduðundan 3'ün soluna gider.

||||7||
|
|||5||8
||1||6||9
0||3
||2||4

[Patika.dev](https://www.patika.dev.tr)