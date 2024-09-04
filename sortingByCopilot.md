## Types of Sorting Algorithms
### Comparison-based Sorting:

*Bubble Sort:* Repeatedly swaps adjacent elements if they are in the wrong order.

Selection Sort: Selects the smallest (or largest) element from the unsorted portion and moves it to the sorted portion.

Insertion Sort: Builds the sorted list one element at a time by repeatedly picking the next element and inserting it into the correct position.

Merge Sort: Divides the list into halves, sorts each half, and then merges the sorted halves.

Quick Sort: Selects a ‘pivot’ element and partitions the list into elements less than and greater than the pivot, then recursively sorts the partitions.

Heap Sort: Converts the list into a heap data structure, then repeatedly extracts the maximum element and rebuilds the heap.

### Non-comparison-based Sorting:

Counting Sort: Counts the occurrences of each element and uses this information to place elements in the correct position.

Radix Sort: Sorts numbers by processing individual digits, starting from the least significant digit to the most significant.

Bucket Sort: Distributes elements into buckets, sorts each bucket, and then concatenates the sorted buckets.

### Characteristics of Sorting Algorithms

Time Complexity: Measures the time an algorithm takes to complete as a function of the input size. Common notations include O(n), O(n log n), O(n²).

Space Complexity: Measures the amount of extra memory an algorithm uses. For example, Merge Sort requires O(n) extra space, while Quick Sort is in-place with O(log n) extra space.

Stability: A stable sorting algorithm maintains the relative order of equal elements. Merge Sort and Insertion Sort are stable, while Quick Sort and Heap Sort are not.

In-place Sorting: An in-place algorithm sorts the list without requiring extra space. Examples include Quick Sort and Heap Sort.
Applications of Sorting Algorithms

Searching: Sorted lists allow for efficient searching algorithms like binary search.

Data Organization: Sorting helps in organizing data for better readability and accessibility.

Algorithm Optimization: Many algorithms, such as those for finding the median or mode, benefit from sorted data.
