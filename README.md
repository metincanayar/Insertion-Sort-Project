# Insertion-Sort-Project 


[22,27,16,2,18,6] -> Insertion Sort

## 1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
  #1 2 --> 22 [2,27,16,22,18,6]
  #2 27 --> 6 [2,6,16,22,18,27]
  #3 16 X (no need to relocate) [2,6,16,22,18,27]
  #4 18 --> 22 [2,6,16,18,22,27]
  
## 2- Big-O gösterimini yazınız.
[22,27,16,2,18,6] ---> (n) 
[2,27,16,22,18,6] ---> (n-1)
[2,6,16,22,18,27] ---> (n-2)
[2,6,16,18,22,27] ---> (n-3)
 
 
 --> n+(n-1)+(n-2)+(n-3)....+1 
 n*(n+1)/2 --> n²+n/2
 
  #### Worst Case: O(n²)
  #### Average Case: O(n²)
  #### Best Case: O(n)

## 3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

 #### Worst Case: [27,22,18,16,6,2]
 #### Best Case: [2,6,16,18,22,27]


## 4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
Dizi sıralandıktan sonra dizimiz [2,6,16,18,22,27] şeklinde olacaktır. 18 sayısı ortada bulunduğu için average case diyebiliriz.

## 5- [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
#1  7 --> 2  [2,3,5,8,7,9,4,15,6]
#2  3 X (no need to relocate)  [2,3,5,8,7,9,4,15,6]
#3  5 --> 4  [2,3,4,8,7,9,5,15,6]
#4  8 --> 5  [2,3,4,5,7,9,8,15,6]

[patika.dev](https://patika.dev/)
