Bubble Sort Algorithm in C++
Description
This project demonstrates the implementation of the Bubble Sort Algorithm in C++. Bubble Sort is a simple sorting algorithm that repeatedly compares adjacent elements in an array and swaps them if they are in the wrong order. The process continues until the entire array is sorted.

This implementation includes:

Reading an array of integers from the user.
Sorting the array using Bubble Sort.
Displaying the sorted array.
How It Works
The algorithm compares each pair of adjacent elements in the array.
If an element is larger than the next one, they are swapped.
After each pass through the array, the largest unsorted element "bubbles up" to its correct position.
The process is repeated until the array is sorted.
An optimization is included to stop early if the array becomes sorted before all passes are complete.
Features
Simple Implementation: The program is beginner-friendly and easy to understand.
Input Flexibility: The user can input an array of any size within the limits of the program.
Optimized Algorithm: The implementation uses a flag to reduce unnecessary passes when the array is already sorted.
How to Use
Clone this repository or copy the source code.
Compile the program using a C++ compiler (e.g., g++):
bash
Copy code
g++ bubble_sort.cpp -o bubble_sort
Run the executable:
bash
Copy code
./bubble_sort
Follow the prompts:
Enter the size of the array.
Input the elements of the array.
View the original and sorted arrays.
Example
Input:
mathematica
Copy code
Enter the number of elements in the array: 5
Enter 5 integers: 64 34 25 12 22
Output:
c
Copy code
Original array: 64 34 25 12 22
Sorted array: 12 22 25 34 64
Code Structure
bubbleSort Function: Implements the Bubble Sort algorithm with an optimization to stop early if the array is already sorted.
printArray Function: Prints the array elements in a readable format.
main Function: Handles user input, calls the sorting function, and displays the results.
Complexity
Time Complexity:
Worst Case: 
𝑂
(
𝑛
2
)
O(n 
2
 ) (when the array is reverse sorted).
Best Case: 
𝑂
(
𝑛
)
O(n) (when the array is already sorted).
Space Complexity: 
𝑂
(
1
)
O(1) (in-place sorting).
Limitations
Bubble Sort is not the most efficient sorting algorithm for large datasets due to its quadratic time complexity.
License
This project is open-source and available under the MIT License.

Author
Developed by Priyadharshini as a demonstration of sorting algorithms in C++. 😊

