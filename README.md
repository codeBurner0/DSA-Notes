# DSA-Notes
important data structure and algorithm notes
# Data Structure and Algorithm

Data structures are a way of organizing and storing data in a computer program efficiently so that it can be accessed and used efficiently. They are essential for designing efficient algorithms and for solving complex problems in computer science. Some examples of data structures include:

- Arrays
- Linked Lists
- Stacks
- Queues
- Trees
- Graphs

## Searching Algorithms

There are several types of searching algorithms, including linear search, binary search, and interpolation search.

### Linear Search

Linear search is a simple search algorithm that checks each element in a list until it finds the target value. 

The time complexity is O(n). 

The space complexity is O(1).

For example, to search for the value 5 in the following list:

```
[1, 3, 5, 7, 9]

```

The linear search algorithm would start at the beginning of the list and check each element until it finds the value 5.

### Binary Search

Binary search is a more efficient search algorithm that works on sorted lists. It starts in the middle of the list and eliminates half of the remaining elements based on whether the target value is greater or less than the middle element. 

The time complexity is O(log n).

The space complexity is O(1).

For example, to search for the value 5 in the following sorted list:

```
[1, 3, 5, 7, 9]

```

The binary search algorithm would start by checking the middle element, 5. Since the target value is equal to the middle element, the search is complete.

### Interpolation Search

Interpolation search is a search algorithm that works on uniformly distributed sorted lists. It uses a formula to estimate the position of the target value based on its value and the values of the first and last elements in the list. The time complexity of interpolation search is O(log log n) in the average case and O(n) in the worst case. The space complexity is O(1).

For example, to search for the value 5 in the following sorted list:

```
[1, 3, 5, 7, 9]

```

The interpolation search algorithm would estimate the position of the value 5 based on its value and the values of the first and last elements in the list. It would then check the estimated position and adjust its estimate until it finds the target value. In this case, the interpolation search would start by estimating that the value 5 is at position 2 in the list, which is correct.

## Sorting Algorithms

Sorting algorithms are used to arrange data in a particular order. There are several types of sorting algorithms, including:

### Bubble Sort

Bubble sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements and swaps them if they are in the wrong order. The algorithm passes through the list until no swaps are needed, which indicates that the list is sorted.

- Time complexity:
    - Worst case: O(n^2)
    - Best case: O(n)
    - Average case: O(n^2)
- Space complexity: O(1)

For example, to sort the following list in ascending order using bubble sort:

```
[4, 2, 1, 3, 5]

```

The algorithm would start by comparing the first two elements, 4 and 2, and swapping them because they are in the wrong order. It would then compare the second and third elements, 4 and 1, and swap them. This process would continue until the list is sorted.

### Selection Sort

Selection sort is another simple sorting algorithm that repeatedly selects the smallest element from the unsorted portion of the list and swaps it with the first element of the unsorted portion.

- Time complexity:
    - Worst case: O(n^2)
    - Best case: O(n^2)
    - Average case: O(n^2)
- Space complexity: O(1)

For example, to sort the following list in ascending order using selection sort:

```
[4, 2, 1, 3, 5]

```

The algorithm would start by selecting the smallest element, which is 1, and swapping it with the first element of the list, 4. It would then select the next smallest element, which is 2, and swap it with the second element of the list, 4. This process would continue until the list is sorted.

### Insertion Sort

Insertion sort is a simple sorting algorithm that builds the final sorted array one item at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort.

- Time complexity:
    - Worst case: O(n^2)
    - Best case: O(n)
    - Average case: O(n^2)
- Space complexity: O(1)

For example, to sort the following list in ascending order using insertion sort:

```
[4, 2, 1, 3, 5]

```

The algorithm would start by selecting the second element of the list, 2, and inserting it in the correct position relative to the first element, 4. It would then select the third element of the list, 1, and insert it in the correct position relative to the first two elements, 2 and 4. This process would continue until the list is sorted.

### Quick Sort

Quicksort is a divide-and-conquer algorithm that partitions an array into two sub-arrays, and then recursively sorts the sub-arrays. The sub-arrays are partitioned based on a pivot element, which is typically the last element in the array.

- Time complexity:
    - Worst case: O(n^2)
    - Best case: O(n log n)
    - Average case: O(n log n)
- Space complexity:
    - Worst case: O(n)
    - Best case: O(log n)

For example, to sort the following list in ascending order using quicksort:

```
[4, 2, 1, 3, 5]

```

The algorithm would start by selecting the pivot element, 5. It would then partition the array into two sub-arrays, one containing elements less than the pivot and the other containing elements greater than the pivot. It would then recursively sort the sub-arrays until the entire list is sorted.

### Merge Sort

Merge sort is a divide-and-conquer algorithm that recursively divides the input array into two halves, sorts each half, and then merges the sorted halves into one sorted array.

- Time complexity:
    - Worst case: O(n log n)
    - Best case: O(n log n)
    - Average case: O(n log n)
- Space complexity: O(n)

For example, to sort the following list in ascending order using merge sort:

```
[4, 2, 1, 3, 5]

```

The algorithm would start by dividing the list into two halves, [4, 2, 1] and [3, 5]. It would then recursively sort each half and merge them back together to form the sorted list.
