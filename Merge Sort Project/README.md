# Merge Sort Example

In computer science, merge sort (also commonly spelled as mergesort) is an efficient, general-purpose, and comparison-based sorting algorithm. Most implementations produce a stable sort, which means that the order of equal elements is the same in the input and output. Merge sort is a divide-and-conquer algorithm that was invented by John von Neumann in 1945.A detailed description and analysis of bottom-up merge sort appeared in a report by Goldstine and von Neumann as early as 1948.

## Algorithm

Conceptually, a merge sort works as follows:

1. Divide the unsorted list into n sublists, each containing one element (a list of one element is considered sorted).
2. Repeatedly merge sublists to produce new sorted sublists until there is only one sublist remaining. This will be the sorted list.

## Example

> [16,21,11,8,12,22]

## Solution Steps

1. [16,21,11] [8,12,22]
2. [16] [21,11] [8] [12,22]
3. [16] [21] [11] [8] [12] [22]
4. [16] [11,21] [8,12] [22]
5. [11,16,21] [8,12,22]
6. [8,11,12,16,21,22]

## Big O Notation

Worst Case: O(nlogn)

Best Case: O(nlogn)

Average Case: O(nlogn)
