# 06

Topic: Midterm Review

## Sorting Algorithms

### Quicksort

<aside>
<img src="https://www.notion.so/icons/thought-alert_blue.svg" alt="https://www.notion.so/icons/thought-alert_blue.svg" width="40px" /> Uses Divide and Conquer (use a partition function with the quicksort function)

- Divide: Divide the sequence into 2 subsequences using the pivot, such that each element in the 1st subsequence is less than or equal to the pivot, each element in the 2nd subsequence is larger the pivot
- Conquer: Sort each subsequence recursively using QuickSort
- Combine: No work is needed, because it sorts in place.
</aside>

### Time Complexity

| Best ($\Omega$) | Average ($\Theta$) | Worst (O) |
| --- | --- | --- |
| n log n | n log n | $n^2$ |

| Space Complexity |
| --- |
| O(log n) |

### Merge Sort

<aside>
<img src="https://www.notion.so/icons/thought-alert_blue.svg" alt="https://www.notion.so/icons/thought-alert_blue.svg" width="40px" /> It sorts a list of values by dividing the array into several smaller instances of the same problem *(**Divide and Conquer)***

- **Divide**: break an instance of a problem into several smaller instances of the same problem
- **Conquer**: Compute solutions for the smaller instances
- **Combine**: Use the solutions to the smaller instances to obtain the solution of the original instance

[File:Merge-sort-example-300px.gif](https://www.google.com/url?sa=i&url=https%3A%2F%2Fen.m.wikipedia.org%2Fwiki%2FFile%3AMerge-sort-example-300px.gif&psig=AOvVaw3xXYeJOKJUizAFUaek7SUK&ust=1706123271673000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCKijl86a9IMDFQAAAAAdAAAAABAP)

</aside>

### Time Complexity

| Best ($\Omega$) | Average ($\Theta$) | Worst (O) |
| --- | --- | --- |
| n log n | n log n | n log n |

| Space Complexity |
| --- |
| O(n) |

### Insertion Sort

<aside>
<img src="https://www.notion.so/icons/thought-alert_blue.svg" alt="https://www.notion.so/icons/thought-alert_blue.svg" width="40px" /> It sorts a list of values by repetitively inserting a particular value into a subset of the list that has already been sorted
*picture example*

![Screen Shot 2024-01-18 at 12.34.07 PM.png](06%201c5c38540bdd4c5fb614b5135c7fd283/Screen_Shot_2024-01-18_at_12.34.07_PM.png)

</aside>

### Time Complexity

| Best ($\Omega$) | Average ($\Theta$) | Worst (O) |
| --- | --- | --- |
| n | $n^2$ | $n^2$ |

| Space Complexity |
| --- |
| O(1) |

## Activation Records

<aside>
<img src="https://www.notion.so/icons/thought-alert_yellow.svg" alt="https://www.notion.so/icons/thought-alert_yellow.svg" width="40px" /> Everytime a function is called, there is an **activation record**. The **activation record** reserves space for the program, the variables, and intermediate results

*Activation records are preformed in a stack (last in first out)*

</aside>

### Merge Sort ARs

<aside>
<img src="https://www.notion.so/icons/pen_yellow.svg" alt="https://www.notion.so/icons/pen_yellow.svg" width="40px" /> Calculate ARs for Merge sort on array [2, 5, 3, 1, 4, 9]
Mergesort ARs for array: 11
Merge ARs for array: 5
Mergesort AR formula: **2n -1** (n = num elements in array)
Merge AR formula: **n - 1**

</aside>

### Quicksort ARs

<aside>
<img src="https://www.notion.so/icons/pen_yellow.svg" alt="https://www.notion.so/icons/pen_yellow.svg" width="40px" /> Calculate ARs for Quicksort on array [2, 5, 3, 1, 4, 9]
Mergesort AR formula: **2n + 1** (n = num partitions)

</aside>