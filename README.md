
# DAA.PRATICAL_1
# SUMMARY:-
This Design and Analysis of Algorithms (DAA) notebook demonstrates the implementation and performance evaluation of four fundamental sorting algorithms: Bubble Sort, Selection Sort, Merge Sort, and Quick Sort. Each algorithm accepts user input, sorts the given array, and measures the execution time using Python's time.perf_counter() function. The implementations illustrate different algorithmic strategies, including iterative and divide-and-conquer approaches. The notebook also highlights the time complexity of these algorithms, enabling a comparison of their efficiency for different input sizes. Overall, it serves as a practical learning resource for understanding sorting techniques, algorithm design, and performance analysis.

# CONCLUSION:
The notebook shows that different sorting algorithms have varying levels of efficiency depending on their approach. Bubble Sort and Selection Sort are simple to implement but are less efficient for large datasets because of their O(n²) time complexity. In contrast, Merge Sort and Quick Sort use the divide-and-conquer technique, making them significantly faster for larger inputs with an average time complexity of O(n log n). By measuring execution time, the notebook demonstrates the practical impact of algorithmic complexity on performance. Overall, the experiment emphasizes the importance of selecting the appropriate sorting algorithm based on the size and characteristics of the data to achieve optimal performance.


# DAA.PRATICAL_2
# Summary:-

This program demonstrates the implementation of Linear Search and Binary Search algorithms in Python. It accepts user input, searches for a given element, measures the execution time, and displays the result along with the time complexity. Linear Search checks each element one by one, whereas Binary Search works on a sorted array by repeatedly dividing the search space into two halves, making it more efficient.

# Conclusion:-

The experiment shows that Binary Search is significantly faster than Linear Search for large sorted datasets, with a time complexity of O(log n) compared to O(n) for Linear Search. However, Binary Search requires the array to be sorted, while Linear Search can be applied to both sorted and unsorted data. Therefore, the choice of algorithm depends on the nature of the input data and the application's requirements.


# DAA.PRATICAL_3
# Summary:-

This program implements the Heap Sort algorithm in Python. It builds a Max Heap from the input array and repeatedly extracts the largest element to produce the sorted array in ascending order. The program also measures the execution time in microseconds and displays the best, average, and worst-case time complexities.

# Conclusion:-

The experiment demonstrates that Heap Sort is an efficient comparison-based sorting algorithm with a consistent time complexity of O(n log n) in the best, average, and worst cases. It provides reliable performance regardless of the input order and is suitable for sorting large datasets. Although it is not a stable sorting algorithm, Heap Sort is preferred when guaranteed O(n log n) performance and constant auxiliary space (O(1)) are required.



