# praktycha robota №3


## алгоритми сортування в мові С++

![alt](https://robodk.com/blog/wp-content/uploads/2018/05/Programming-Language-PNG-Download-Image.png)
###### Bubblesort
 - In this algorithm, traverse from left and compare adjacent elements and the higher one is placed at right side. 
 - In this way, the largest element is moved to the rightmost end at first. 
 - This process is then continued to find the second largest and place it and so on until the data is sorted.
## For example:
Input: arr[] = {6, 3, 0, 5}

### First Pass: 

The largest element is placed in its correct position, i.e., the end of the array.

### Second Pass: 

Place the second largest element at correct position

### Third Pass:

Place the remaining two elements at their correct positions.

Bubble Sort Algorithm : Placing the remaining elements at their correct positions
Bubble Sort Algorithm : Placing the remaining elements at their correct positions

 - Total no. of passes: n-1
 - Total no. of comparisons: n*(n-1)/2

