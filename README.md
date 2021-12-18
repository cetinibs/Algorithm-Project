# Algorithm-Project
 =============
  
## Project One
-------------

### [22,27,16,2,18,6] -> Insertion Sort

1-)Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

2-)Big-O gösterimini yazınız.

3-)Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4-)Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

5-)[7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

#### Çözümler
1-)[2,22,27,16,18,6]->[2,6,22,27,16,18]->[2,6,16,22,27,18]->[2,6,16,18,22,27]

2-)O(n^2)

3-)Avarage case: O(n^2/2), Worst case : O(n^2), Best case: O(1)

4-)Avarage case

5-)[2,7,3,5,8,9,4,15,6]->[2,3,7,5,8,9,4,15,6]->[2,3,4,7,5,8,9,15,6]->[2,3,4,,5,7,8,9,15,6]

## Project Two
[16,21,11,8,12,22]

### Soru-1-a: Yukarıdaki dizinin Merge sort türüne göre aşamalarını yazınız.

1 Bölme [16,21,11,8,12,22]
2 Bölme [16,21,11] - [8,12,22]
3 Bölme [16,21] - [11] - [8,12] - [22]
4 Bölme [16] - [21] - [11] - [8] - [12] - [22]
5 Birleştirme : [16,21] - [8,11] - [12,22]
6 Birleştirme : [8,11,16,21] - [12,22]
7 Birleştirme : [8,11,12,16,21,22]

### Soru-1-b: Big-O gösterimini yazınız.
2^x=n ise logn = x olduğundan O(nlogn)

## Project Three

## Soru 1) Aşağıdaki dizinin Binary-Search-Tree aşamalarını yazınız.
[7,5,1,8,3,6,0,9,4,2]
Öncelikle diziyi sıralayalım
[0,1,2,3,4,5,6,7,8,9]

  • Root=7 olarak seçtim.
           7
         /   \
        5     8
       / \     \
      1   6     9
     / \
    0   3
       / \
      2   4
 
 
