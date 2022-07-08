# binary-search-tree

Binary-Search-Tree
Patika Dev Profile: https://app.patika.dev/ezgikarali4

Project 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

Answer
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] Dizi içerisinde soldan sağa doğru

Adım 1 

Root 7 dir. 

7 

Adım 2 

5 sayısı 7 den küçüktür. Solunda yer alır. 

Adım 3 

1 sayısı 7 ve 5 den küçüktür. 5'in solunda yer alır. 

Adım 4 

8 sayısı 7 den büyüktür. 7'nin sağında yer alır. 

Adım 5 

3 sayısı 7,5 den küçük 1 den büyük. Bundan dolayı 1'in sağında yer alır. 

Adım 6 

6 sayısı 7 den küçük 5 den büyük bundan dolayı 5'in sağında yer alır. 

Adım 7 

0 sayısı 7,5,1,3 den küçük. 3'ün solunda yer alır. 

Adım 8 

9 sayısı 7 den ve 9 den büyük bundan dolayı 8'in sağında yer alır. 

Adım 9

4 sayısı 7,5,6 dan küçük 3 den büyük. 3'ün sağında yer alır. 

Adım 10 

2 sayısı 7,5,6,3 den küçük. 3'ün solunda yer alır. 

       7
     /   \
    5     8
   / \     \
  1   6     9  
 /  \
0    3
    /  \
    2   4


