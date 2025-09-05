# Algo-efficiency-mini-project-Tiya
Question: Implement the following algorithms in Python:
⦁	Fibonacci (naïve recursive and dynamic programming version) 
<img width="369" height="358" alt="image" src="https://github.com/user-attachments/assets/6db6125a-8b6d-40a4-bbcc-14eceb6bc98f" />
<img width="369" height="359" alt="image" src="https://github.com/user-attachments/assets/b9d78d0b-d481-4c40-adb8-2bd43a8ee5bc" />
<img width="384" height="317" alt="image" src="https://github.com/user-attachments/assets/d045587f-89c3-4c63-a36e-83984a51785f" />
Observations and Analysis:
The Fibonacci series is implemented through two methods: recursive and iterative (without recursion). A performance comparison graph is plotted for both methods, where the red curve represents recursion and the blue curve represents iteration.
Iterative (Blue Line) – O (n) 
the blue curve grows linearly with the input size (from 0 to ~1750), confirming a time complexity of O (n). Even for very large values of n, the execution time remains extremely small, making the iterative approach highly efficient and scalable.
Recursive (Red Line)- O (2n)
The red curve remains small for lower input sizes but then rises exponentially after around n = 30. This behaviour corresponds to a time complexity of O (2^n), caused by repeated recalculations of the same subproblems. As a result, the naive recursive approach becomes impractical for larger inputs, failing to compute beyond ~30–40 terms in reasonable time.
Conclusion: 
The iterative approach is significantly more efficient than naive recursion. It can handle large values of n (like ~2000) with ease, whereas recursion quickly becomes infeasible. Hence, the iterative method is preferred in real-world applications, where performance and scalability are critical.
⦁	Merge Sort 
<img width="309" height="331" alt="image" src="https://github.com/user-attachments/assets/d4ee3626-d088-40ee-a1aa-ef52394ee23a" />
⦁	Quick Sort 
<img width="419" height="138" alt="image" src="https://github.com/user-attachments/assets/3b71ef4b-8550-43a3-85ad-9a00a71b5d2b" />
⦁	Insertion Sort 
<img width="300" height="171" alt="image" src="https://github.com/user-attachments/assets/3b97cb96-d337-4be2-9b69-5e9d893ae259" />
⦁	Bubble Sort 
<img width="340" height="135" alt="image" src="https://github.com/user-attachments/assets/24689add-5136-4cc4-ae82-044d9d4709ce" />
⦁	Selection Sort 
<img width="333" height="168" alt="image" src="https://github.com/user-attachments/assets/0262aa30-c7a6-4ed7-8499-b869cfd6abe1" />
<img width="362" height="252" alt="image" src="https://github.com/user-attachments/assets/dd7486de-a0fe-4bc2-aef4-2a8173f2a6ef" />
<img width="397" height="244" alt="image" src="https://github.com/user-attachments/assets/d81b3822-8527-47d8-bbe5-419ec9134b22" />
Observations and Analysis:
The given graph shows a comparative analysis between different sorting algorithms like bubble sort (blue curve), selection sort (orange curve), insertion sort (green curve), merge sort (red curve) and quick sort (purple curve).
Bubble Sort (Blue Curve): The blue curve rises very steeply with increasing input size, verifying a time complexity of O (n²). For even modest input sizes, running time is very large due to the redundant comparisons and swaps of neighbouring elements. Bubble Sort is thus the least efficient of all algorithms tested and not suitable for real-world use with large data sets.
Selection Sort (Green Curve): The green curve also illustrates quadratic growth, corresponding to a time complexity of O (n²). While it makes fewer swaps than Bubble Sort, it nonetheless scans the unsorted section for each iteration. Execution time grows proportionally with input size, exhibiting poor scalability.
Insertion Sort (Orange Curve): The orange curve increases quadratic ally but less steeply than Bubble and Selection Sort for smaller inputs. This corresponds to its worst- and average-case time complexity of O (n²), with better O (n) performance when the input is almost sorted. Insertion Sort is ideal for small or partially ordered inputs but impractical for large inputs.
Merge Sort (Purple Curve): The purple curve increases far less rapidly than quadratic algorithms, showing an O (n log n) time complexity consistently. Even with large input sizes, Merge Sort is efficient with its divide-and-conquer mechanism. It is very scalable and safe with regard to larger data sets, albeit with additional memory needed for merging.
Quick Sort (Red Curve): The red curve is similar to Merge Sort, validating an average-case time complexity of O (n log n). In real life, Quick Sort even surpasses Merge Sort due to its ability to sort in-place and save on memory. But in the worst case scenario (when a bad pivot choice is made), its time complexity can fall to O (n²). Nevertheless, Quick Sort remains one of the fastest, most practical sorting algorithms used.
Conclusion:
⦁	Inefficient (Quadratic): Bubble > Selection > Insertion.
⦁	Efficient (Log-linear): Quick ≈ Merge.
⦁	For real-world applications, Quick Sort and Merge Sort are far better choices, with Quick Sort usually winning in practice unless stability is required (then Merge is preferred).
⦁	Binary Search
<img width="247" height="304" alt="image" src="https://github.com/user-attachments/assets/973a4c0d-5f8d-4e1f-b641-3eb9c1f19403" />
<img width="409" height="269" alt="image" src="https://github.com/user-attachments/assets/d46b1ab4-a10d-46b6-ad2e-ba712d9a6780" />
