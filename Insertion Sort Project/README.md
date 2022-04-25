# Insertion Sort Example

Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed at the correct position in the sorted part.

## Algorithm

To sort array an array of size n in ascending order:

1. Iterate from arr[1] to arr[n] over the array.
2. Compare the current element (key) to its predecessor.
3. If the key element is smaller than its predecessor, compare it to the elements before. Move the greater elements one position up to make space for the swapped element.

## Example

We take an unsorted array for our example.

> [22,27,16,2,18,6]

## Solution Steps

1. [22,27,16,2,18,6]
2. [2,27,16,22,18,6]
3. [2,6,16,22,18,27]
4. [2,6,16,18,22,27]

## Big O Notation

> n + (n-1) + (n-2) + (n-3) ... +1\
> n.(n+1)/2\
> O(n^2)

## Time Complexity

Best Case : O(n)\
Avarage Case: O(n^2)\
Worst Case: O(n^2)

Since the number 18 is the middle element of the array,
enters average case status

> [7,3,5,8,2,9,4,15,6]

1. [2,3,5,8,7,9,4,15,6]
2. [2,3,4,8,7,9,5,15,6]
3. [2,3,4,5,7,9,8,15,6]
4. [2,3,4,5,6,9,8,15,7]
