Description:

This C program implements various sorting algorithms including Selection Sort, Insertion Sort, Bubble Sort, Merge Sort, and Heap Sort. Each sorting algorithm is applied to datasets read from input files (input1.txt, input2.txt, input3.txt). The program measures the runtime and the amount of extra memory allocated by each sorting algorithm.

File Structure:

bonus_assignment.c: The main C source code file containing the implementation of sorting algorithms, file parsing, memory allocation functions, and the main function.
input1.txt, input2.txt, input3.txt: Input files containing datasets for sorting.
README.md (or README.txt): This file, providing information about the program.


How to Compile and Run:

Open a terminal or command prompt.
Navigate to the directory containing the source code file (main.c) and input files.
Compile the code using a C compiler such as GCC:
gcc main.c -o sorting_program
Run the compiled program:
bash
./sorting_program


Input Format:

Each input file (input1.txt, input2.txt, input3.txt) contains a dataset for sorting.
The first line of each input file specifies the size of the dataset (dataSz).
The subsequent lines contain integer values representing elements of the dataset.
Output:

For each dataset, the program outputs the following information for each sorting algorithm:
Dataset Size (dataSz).
Runtime of the sorting algorithm.
Extra memory allocated during sorting.
First 100 elements and last 100 elements of the sorted array.
Sorting Algorithms Implemented:

Selection Sort: Sorts the array by repeatedly finding the minimum element from the unsorted part and moving it to the beginning.
Insertion Sort: Builds the final sorted array one item at a time by repeatedly taking the next element and inserting it into the sorted part.
Bubble Sort: Repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.
Merge Sort: Divides the array into two halves, recursively sorts each half, and then merges the sorted halves.
Heap Sort: Builds a max heap from the array and repeatedly extracts the maximum element from the heap to obtain a sorted array.

