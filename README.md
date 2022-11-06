# DataStructuresAndAlgorithms Questions

## Merge Sort Projesi
### Soru:
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

### Cevap:
<p>
   -         [16,21,11,8,12,22] 
              
        [16]-[21,11]    -    [8]-[12,22]
         
        [16]-[21]-[11]       [8]-[12]-[22]
       
         [16]-[11,21]         [8,12]-[22]
         
          [11,16,21]  -   [8,12,22]
           
        [8,11,12,16,21,22]

-  Big-O Notation = O(nlogn) şeklindedir.
    </p>
   
    
## Insertion Sort Projesi
### Soru:
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### Cevap: 
<p>
   1)
        [22	27	16	2	18	6]		Data
         <br/>
        [2	27	16	22	18	6]		[2-22]
         <br/>
        [2	6	16	22	18	27]		[6-27]
         <br/>
        [2	6	16	18	22	27]		[18-22]
        <br/>
   2) Big-O 			O(n^2)
        <br/>
   3) Time Complexity: Average case:O(n²),Worst case: O(n²), Best case:O(n)
        <br/>
   4) 18 average case kapsamındadır.
    </p>
        
        
## Binary Search Tree Projesi
### Soru:
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Cevap:
                        [7,5,1,8,3,6,0,9,4,2]
  <p> 1)Sıralama adımları :
       7
   -----------------
       7
      /
     5
   -----------------
        7
       /
      5
    /
   1
   ------------------
         7
       /   \
      5     8
    /
   1
  ------------------
         7
       /   \
      5     8
    /        
   1 
    \
     3
  ------------------
         7
       /   \
      5     8
    /  \      
   1    6
    \
      3     
 ------------------
         7
       /   \
      5     8
    /  \      
   1    6
  / \
 0   3 
 ------------------
         7
       /   \
      5     8
    /  \     \
   1    6     9
  / \
 0   3 
------------------
         7
       /   \
      5     8
    /  \     \
   1    6     9
  / \
 0   3
      \
       4
------------------
         7
       /   \
      5     8
    /  \     \
   1    6     9
  / \
 0   3
    / \
   2   4
   
    10 indeksli dizimizde 1. index olan 7 elemanı Root olur.
    Root = 7
    Rootun sağında 8 solunda 5 bulunur.
    - 8'in sağında 9 vardır.
    - 5'in sağında 6 solunda 1 vardır.
    - 1'in solunda 0 sağında 3 vardır.
    - 3'ün solunda 2 sağında 4 vardır. (2 ve 4 bu ağacın yaprak düğümleridir.)
    </p>
    <br/>
    
## [Patika Link](https://app.patika.dev/mehmetarikannn)
    



