# Proje 3 - Binary Search Tree
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]**

## Soru 

Yukarıdaki dizinin Binary-Search-Tree aşamalarını yazınız.  
**Örnek:** Root x'dir. Root'un sağından y bulunur. Solunda z bulunur vb.

## Cevap 

1.  Root'u 7 olarak alırız.
2.  İkinci eleman 5, root'tan küçük olduğu için sola,
3.  Üçüncü eleman 1, 5'ten küçük olduğu için 5'in soluna,
4.  Dördüncü eleman 8, root'tan büyük olduğu için root'un sağına,
5.  Beşinci eleman 3, 1'den büyük ama 5'ten küçük olduğu için 1'in sağına,
6.  Altıncı eleman 6, 5'ten büyük ama 7'den küçük olduğu için 5'in sağına,
7.  Yedinci eleman 0, 1'den küçük olduğu için 1'in soluna,
8.  Sekizinci eleman 9, root'tan ve 8'den büyük olduğu için 8'in sağına,
9.  Dokuzuncu eleman 4, 3'ten büyük ama 5'ten küçük olduğu için 3'ün sağına.
10.  Onuncu eleman 2, 1'den büyük ama 3'ten küçük olduğu için 3'ün soluna yazılır.

   
               
           7  
          / \
         5   8
        / \   \
       1   6   9 
      / \   
     0   3  
        / \
       2   4  