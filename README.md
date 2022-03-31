# Binary Search Tree Projesi

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

* İlk olarak diziyi sıralayacak olursak;
**[0,1,2,3,4,5,6,7,8,9]** 

* Toplam 10 elemanlı bir binary tree de sağ ve sol kollarda denge yaratabilmek daha iyi sonuçlar verecektir. Dolayısıyla root elemanını 5 olarak seçiyorum.
* 5'in sağında kendinden büyük sayılar, solunda ise kendinden küçük sayıları;
onları da kendi içlerinde sağında büyük, solunda küçük olarak diziyorum.
```
                        5
                     /    \
                   2        7
                  /\       / \ 
                 1  3     6   8
                /    \         \
               0      4          9
```
               