## Merge Sort
 ___
 <span style="color:red">[16,21,11,8,12,22]</span>-> Merge Sort

### 1. Yukarıdaki dizinin merge sort türüne göre asamalari asagidaki gibidir.
           [16,21,11,8,12,22]

         [16,21,11]        [8,12,22]

     [16]  [21,11]          [8,12]  [22]

    [16] [21] [11]           [8]  [12] [22]

     [16]  [11,21]          [8,12]  [22]
 
         [11,16,21]        [8,12,22]

             [8,11,12,16,21,22]
  


### 2. Big-O gösterimi.
    O(nlogn)