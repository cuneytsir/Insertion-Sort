www.patika.dev
# Insertion-Sort
[22,27,16,2,18,6] -> Insertion Sort

1) Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.

Array: [22,27,16,2,18,6]

[22,27,16,2,18,6]
[16,22,27,2,18,6]
[2,16,22,27,18,6]
[2,16,18,22,27,6]
[2,6,16,18,22,27]

************************************************************************************
2) Big-O gösterimini yazınız.

Big-O notation:

n(n+1)/2 -> (n^2+n)/2
Big-O : O(n^2)
************************************************************************************

3) Time Complexity: Average case: Aradığımız sayının ortada olması,
Worst case: Aradığımız sayının sonda olması, 
Best case: Aradığımız sayının dizinin en başında olması.


Time comptlexity:

Average case: O(n^2) 
Worst case: O(n^2)
Best case: O(n)

************************************************************************************

4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[2, 6, 16, 18, 22, 27]

18 sayısı ortada olduğundan dolayı average case kapsamına girer.

************************************************************************************
5) [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

Array: [7,3,5,8,2,9,4,15,6]

1.[7,3,5,8,2,9,4,15,6] 
2.[3,5,7|8,2,9,4,15,6]
3.[2,3,5,7,8|9,4,15,6]
4.[2,3,4,5,7,8,9|15,6]


4.adımdaki hali [2, 3, 4, 5, 7, 8, 9, 15, 6]
