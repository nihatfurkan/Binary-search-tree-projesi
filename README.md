# Binary-search-tree-projesi
Binary Search Tree nedir?
Binary Search Tree (BST), her düğümünde en fazla iki çocuğu olan ve sol alt ağacındaki düğümlerin değerlerinin kendisinden küçük, sağ alt ağacındaki düğümlerin değerlerinin ise kendisinden büyük olduğu bir ağaç veri yapısıdır.

BST yapısı, arama, ekleme ve silme işlemleri için oldukça etkilidir. Arama işleminde, verilen bir anahtar değerinin ağaçta olup olmadığını hızlı bir şekilde tespit edebiliriz. Ekleme ve silme işlemlerinde ise, yeni bir düğüm eklenirken veya mevcut bir düğüm silinirken ağaç yapısı korunarak işlem yapılır.

BST, özellikle sıralı verilerin arama, ekleme ve silme işlemleri için oldukça uygun bir veri yapısıdır. Ancak, ağacın dengesiz şekilde büyümesi durumunda (yani, her bir alt ağaç birbirine çok yakın boyutta değilse), arama, ekleme ve silme işlemlerinde kötü performans gösterebilir. Bu nedenle, dengeli ağaç yapıları gibi alternatif veri yapıları da kullanılabilir.
-------
Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

1.Dizinin ilk elemanı kök düğüm olur: 7
                               7
2.Kök düğümün soluna, kök düğümden küçük olan elemanlar eklenir:   
             7
            / \
           5  
3.Kök düğümün sağına, kök düğümden büyük olan elemanlar eklenir:        
            7
            / \
           5   8
4.5'in soluna, 5'ten küçük olan elemanlar eklenir:
         
            7
            / \
           5   8
          / 
 5. 5'in sağına, 5'ten büyük olan elemanlar eklenir: 
              7
            / \
           5   8
          / \
         1 
 6.  8'in soluna, 8'den küçük olan elemanlar eklenir:
             7
            / \
           5   8
          / \
         1   3
  7.  8'in sağına, 8'den büyük olan elemanlar eklenir:
             7
            / \
           5   8
          / \   \
         1   3   9 
   8. 1'in soluna, 1'den küçük olan elemanlar eklenir:
              7
            / \
           5   8
          / \   \
         1   3   9
        / \
       0 
    9.1'in sağına, 1'den büyük olan elemanlar eklenir:
             7
            / \
           5   8
          / \   \
         1   3   9
        / \
       0   2
       
   10. 3'ün soluna, 3'ten küçük olan elemanlar eklenir:
            7
           / \
          5   8
         / \   \
        1   3   9
       / \     
      0   2   
 11.   9'un soluna, 9'dan küçük olan elemanlar eklenir:    
            7
           / \
          5   8
         / \   \
        1   3   9
       / \     
  12.   4'ün soluna, 4'ten küçük olan elemanlar eklenir:
            7
           / \
          5   8
         / \   \
        1   3   9
       / \     
      0   2   
           \
            4
   13.   2'nin sağına, 2'den büyük olan elemanlar eklenir:  
            7
           / \
          5   8
         / \   \
        1   3   9
       / \     
      0   2   
           \
            4
             \
              6
        
      0   2      
 
