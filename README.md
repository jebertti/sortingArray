Write a C program to read in a given list of nonnegative integers and store them in a dynamic array. Then create another dynamic array and copy
the elements of the previous array into the new one. Sort the newly created array. Next, based
on the user input perform either of two tasks given below:


• If the user input is 1, perform a comparison on arrays to find how many elements are in the
same location/index in both arrays:
Example:
Original array: 31, 5, 8, 28, 15, 21, 11, 2
Sorted array: 2, 5, 8, 11, 15, 21, 28, 31
Output: 4 values are in the same location in both arrays.
 Original array: 5, 2, 8, 6, 20, 18
Sorted array: 2, 5, 6, 8, 18, 20
Output: All elements change location in the sorted array.


• If the user input is 2, perform target sum. Prompt the user to enter a target integer and check
if there exist two integers in the list that sum up to the target integer.
Example:
 Original array: 31, 5, 8, 28, 15, 21, 11, 2
 Sorted array: 2, 5, 8, 11, 15, 21, 28, 31
 Target: 26
 Output: Success! Elements at indices 1 and 5 add up to26.
 Target: 44
 Output: Target sum failed!
