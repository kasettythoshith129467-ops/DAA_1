# DAA.PRATICAL_1
# SUMMARY:-
This Design and Analysis of Algorithms (DAA) notebook demonstrates the implementation and performance evaluation of four fundamental sorting algorithms: Bubble Sort, Selection Sort, Merge Sort, and Quick Sort. Each algorithm accepts user input, sorts the given array, and measures the execution time using Python's time.perf_counter() function. The implementations illustrate different algorithmic strategies, including iterative and divide-and-conquer approaches. The notebook also highlights the time complexity of these algorithms, enabling a comparison of their efficiency for different input sizes. Overall, it serves as a practical learning resource for understanding sorting techniques, algorithm design, and performance analysis.

# CONCLUSION:
The notebook shows that different sorting algorithms have varying levels of efficiency depending on their approach. Bubble Sort and Selection Sort are simple to implement but are less efficient for large datasets because of their O(n²) time complexity. In contrast, Merge Sort and Quick Sort use the divide-and-conquer technique, making them significantly faster for larger inputs with an average time complexity of O(n log n). By measuring execution time, the notebook demonstrates the practical impact of algorithmic complexity on performance. Overall, the experiment emphasizes the importance of selecting the appropriate sorting algorithm based on the size and characteristics of the data to achieve optimal performance.

# DAA.PRATICAL_2
# SUMMARY:-
This program demonstrates the implementation of Linear Search and Binary Search algorithms in Python. It accepts user input, searches for a given element, measures the execution time, and displays the result along with the time complexity. Linear Search checks each element one by one, whereas Binary Search works on a sorted array by repeatedly dividing the search space into two halves, making it more efficient.

# CONCLUSION:-
The experiment shows that Binary Search is significantly faster than Linear Search for large sorted datasets, with a time complexity of O(log n) compared to O(n) for Linear Search. However, Binary Search requires the array to be sorted, while Linear Search can be applied to both sorted and unsorted data. Therefore, the choice of algorithm depends on the nature of the input data and the application's requirements.

# DAA.PRATICAL_3
# SUMMARY:-
This program implements the Heap Sort algorithm in Python. It builds a Max Heap from the input array and repeatedly extracts the largest element to produce the sorted array in ascending order. The program also measures the execution time in microseconds and displays the best, average, and worst-case time complexities.

# CONCLUSION:-
The experiment demonstrates that Heap Sort is an efficient comparison-based sorting algorithm with a consistent time complexity of O(n log n) in the best, average, and worst cases. It provides reliable performance regardless of the input order and is suitable for sorting large datasets. Although it is not a stable sorting algorithm, Heap Sort is preferred when guaranteed O(n log n) performance and constant auxiliary space (O(1)) are required.

# DAA_PRACTICAL_4
# SUMMARY:
In this practical, a factorial program was implemented using both iterative and recursive methods in Python. The iterative method calculates the factorial by using a loop, while the recursive method calculates it by calling the same function repeatedly until a base condition is reached. Both methods successfully produce the correct factorial value. The time complexity of both approaches is O(n), but the recursive method requires additional memory for function calls.

# CONCLUSION:
Through this practical, we learned how to solve the factorial problem using two different approaches. The iterative method is simple, efficient, and uses less memory, making it suitable for larger inputs. The recursive method is easier to understand and demonstrates the concept of recursion effectively. Both approaches are important for learning programming concepts and understanding different ways to solve the same problem.

# DAA_PRACTICAL_5
# Summary:
In this practical, the 0/1 Knapsack Problem was implemented using Dynamic Programming. The program calculates the maximum value that can be carried in a knapsack without exceeding its weight limit. Dynamic Programming helps avoid repeating the same calculations, making the solution faster and more efficient.

# Conclusion:
The practical helped in understanding how Dynamic Programming can be used to solve optimization problems. By storing intermediate results, the algorithm finds the best possible solution efficiently. It is a useful technique for solving real-world problems that involve maximizing profit or minimizing cost under given constraints.

# DAA_PRACTICAL_6
# Summary:
In this practical, Matrix Chain Multiplication was implemented using Dynamic Programming. The program finds the best order to multiply a group of matrices so that the total number of calculations is minimized. By storing the results of smaller problems, it avoids repeating the same calculations and improves efficiency.

# Conclusion:
This practical helped in understanding how Dynamic Programming can be used to optimize matrix multiplication. The algorithm efficiently finds the minimum multiplication cost and reduces unnecessary computations. It is a useful technique for solving complex optimization problems in computer science.

# DAA_PRACTICAL_7
# SUMMARY:
In this practical, I implemented the Making Change Problem using Dynamic Programming. The aim was to find the minimum number of coins needed to make a given amount from the available coin denominations. By breaking the problem into smaller parts and storing the results, the program was able to solve the problem efficiently. This practical helped me understand how Dynamic Programming avoids repeated calculations and provides an optimal solution in less time.

# CONCLUSION:
By completing this practical, I gained a better understanding of Dynamic Programming and its advantages over simple brute-force methods. I learned how storing previously calculated results can improve the efficiency of a program. The Making Change Problem is a good example of how Dynamic Programming can be used to solve real-life optimization problems. Overall, this practical improved my problem-solving skills and strengthened my understanding of Dynamic Programming concepts.



