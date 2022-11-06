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
         <br/>
        [16]-[21]-[11]       [8]-[12]-[22]
         <br/>
         [16]-[11,21]         [8,12]-[22]
          <br/>
          [11,16,21]  -   [8,12,22]
           <br/>
        [8,11,12,16,21,22]

-  Big-O Notation = O(nlogn) şeklindedir.
    </p>
   
    
## Insertion Sort Projesi
### Soru:
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.
Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### Cevap: 
<p>
    1)    [22	27	16	2	18	6]		Data
         <br/>
        [2	27	16	22	18	6]		[2-22]
         <br/>
        [2	6	16	22	18	27]		[6-27]
         <br/>
        [2	6	16	18	22	27]		[18-22]
        <br/>
       2) Big-O 			O(n^2) => O(36)
        <br/>
       3)    Dizi sıralandıktan sonra 18 sayısı ortada olacağı için Average Case kapsamına girer.
    </p>
        
        
## Binary Search Tree Projesi
### Soru:
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

### Cevap:
                        [7,5,1,8,3,6,0,9,4,2]
  <p> 1) Öncelikle Binary  Search sıralanmış (sorting algoritması yapılmış) dizi üzerinde yapılır.
    Sıralanmış dizimiz [0,1,2,3,4,5,6,7,8,9] olur.
    10 indeksli dizimizde 6. index olan 5 elemanı Root olur.
    Root = 5
    Rootun sağında 6 solunda 4 bulunur
    </p>
    <br/>
    
 [Patika](https://app.patika.dev/mehmetarikannn)
    



