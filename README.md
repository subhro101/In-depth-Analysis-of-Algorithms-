In this project I evaluate the four sorting algorithms, on various inputs and relate their theoretical run time to their
empirical (actual) behavior. These algorithms are SelectionSort, InsertionSort,MergeSort, and QuickSort.

Once compiled, the program should be run from the command line, as it expects three arguments. If fewer than three arguments are specified, the program will assume default variables for
any unspecified arguments.
The first of these three arguments represents the size of the input array.
The program only accepts sizes between 1 and 1,000,000,000, inclusive(default 10,000). The second argument represents the sorting algorithm you wish to run. Valid algorithms include SelectionSort, InsertionSort, MergeSort,and QuickSort (default MergeSort), or you can abbreviate the algorithms by their first letter (‘s,’ ‘i,’ ‘m,’, or ‘q’). The last argument represents the type of input to sort. Valid input types are sorted, random, and constat(or ‘s,’ ‘r’, ‘c’; default ‘r’), where ‘random’ is an unsorted array, ‘sorted’ is a sorted array (in increasing order), and ‘constant’ is an array where every entry is identical.

In order to improve the timing stability, the algorithm runs the requested sort three times and reports the median of the three timing results to you. In order to get the most accurate timing results, there should be no other processes running on the machine at the same time, but this may not always be possible, especially if you are running the program on a lab machine.

I highly recommend you go through my project report. Thank you. 