HOSTINE OLARE
EB3/68519/23
Selection Sort Algorithm in C++
This repository contains a simple implementation of the Selection Sort algorithm in C++. The program takes user input for an array of integers, displays the original array, sorts it using selection sort, and then displays the sorted array.
Description
Selection sort is a simple comparison-based sorting algorithm. It works by dividing the array into two parts: a sorted portion and an unsorted portion. The algorithm repeatedly selects the smallest element from the unsorted portion and swaps it with the element at the beginning of the unsorted portion.
How Selection Sort Works:
1.	Find the minimum element in the unsorted part of the array
2.	Swap it with the element at the current position
3.	Move the boundary between sorted and unsorted parts one element to the right
4.	Repeat until the entire array is sorted
Features
•	Takes user input for array size and elements
•	Displays the original array before sorting
•	Implements selection sort algorithm with O(n²) time complexity
•	Shows the sorted array after the algorithm completes
•	Handles arrays of any size (limited by available memory)



Code Structure
Functions
selectionSort(int arr[], int n)
•	Parameters:
o	arr[]: The integer array to be sorted
o	n: The size of the array
•	Returns: void (sorts the array in-place)
•	Description: Implements the selection sort algorithm to sort the array in ascending order
Main Program Flow
1.	Prompts user to enter the number of elements
2.	Creates an array of the specified size
3.	Takes input for each element
4.	Displays the original array
5.	Calls selectionSort() to sort the array
6.	Displays the sorted array
Time Complexity
•	Best Case: O(n²) - even if the array is already sorted, the algorithm still needs to find the minimum element for each position
•	Average Case: O(n²)
•	Worst Case: O(n²)
Space Complexity
•	Auxiliary Space: O(1) - selection sort is an in-place sorting algorithm, meaning it sorts the array without requiring additional memory proportional to the input size


Advantages and Disadvantages
Advantages:
•	Simple and easy to understand
•	Performs well on small arrays
•	In-place sorting (requires minimal extra memory)
•	Number of swaps is O(n) - makes it useful when swapping is expensive
Disadvantages:
•	Quadratic time complexity makes it inefficient for large arrays
•	Not stable (may change the relative order of equal elements)
•	Always takes O(n²) time regardless of the initial order
File Structure
•	selectionsortascending.cpp - Main source code file containing the implementation in ascending order
•	selectionsortdescending.cpp - Main source code file containing the implementation in descending order
•	README.md - This documentation file

