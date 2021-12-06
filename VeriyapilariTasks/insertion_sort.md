# Insertion Sort

<span style="color:red">[22,27,16,2,18,6]</span> -> Insertion Sort

### 1. Yukarıdaki dizinin sort türüne göre aşamalarını asagidaki gibidir.

    1. [22,27,16,2,18,6]
    2. [2,27,16,22,18,6]
    3. [2,6,16,22,18,27]
    4. [2,6,16,18,22,27]

### 2. Big-O gösterimi .
O(n<sup>2</sup>)


### 3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

Best case: 2 <br>
Average Case: 16 ve 18 <br>
Worse Case: 27

### 4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer?

   18 sayisi ortada olduğu için "Average Case" kapsamına girer.


----
----

<span style="color:red">[7,3,5,8,2,9,4,15,6]</span>

### Dizisinin Insertion Sort'a göre ilk 4 adımı.

    1. [7,3,5,8,2,9,4,15,6] n
    2. [2,3,5,8,7,9,4,15,6] n-1
    3. [2,3,4,8,7,9,5,15,6] n-2
    4. [2,3,4,5,7,9,8,15,6] n-3
