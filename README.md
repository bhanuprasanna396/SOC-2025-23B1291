# SOC-2025-23B1291
**SOC Project ID-43: Kickstart CP**

**Week 1 – Core Concepts Overview**

1)Time Complexity & Efficiency
Learn to analyze your code's speed using Big-O (e.g., O(n log n)), which is crucial for solving problems under time limits.

2)Sorting & Searching
Foundation of many CP problems. Sorting helps in preparing data; searching (especially Binary Search) helps in fast querying or optimization.

3)Binary Search Mastery
Go beyond simple search—learn how to apply binary search on the answer space to solve tricky problems efficiently (e.g., min/max value that satisfies a condition).

4)Basic Data Structures
Arrays, sets, maps, stacks, queues – the tools you’ll use in almost every solution. Knowing when and how to use them is key.

5)Problem-Solving Framework
Start thinking in patterns: brute-force → optimize → use DS/algos to improve time and space.

Resources Links:
https://cses.fi/book/book.pdf
https://www.youtube.com/playlist?list=PLgUwDviBIf0pMFMWuuvDNMAkoQFi-h0ZF
https://drive.google.com/file/d/1ho6xPiOxzu2h8dieXAkaLz9G0pc7F0V2/view?usp=sharing

Assignment Link:
https://1drv.ms/w/c/3d3dfac7f44bdc27/EQZ8AZbd9vpMgybqvq0-hCsBIff6sSxoBrh52wUWR19cxA?e=GcF0fL

Submission Link:
https://drive.google.com/drive/folders/1RVF7hx9Wds8KCSMa-ai_EbKL_Yeo53h1?usp=sharing

**Week 2 - Sorting Overview**

Bubble Sort
Repeatedly compares adjacent elements and swaps them if they are in the wrong order.
Time Complexity: O(n²)
Space Complexity: O(1)

Selection Sort
Finds the smallest element in the unsorted part and places it at the correct position.
Time Complexity: O(n²)
Space Complexity: O(1)

Insertion Sort
Builds the sorted array one element at a time by inserting elements into their correct position.
Time Complexity: O(n²)
Space Complexity: O(1)

Merge Sort
Divides the array into halves, recursively sorts them, and merges the sorted halves.
Time Complexity: O(n log n)
Space Complexity: O(n)

Quick Sort
Picks a pivot, partitions the array into smaller and larger elements, and recursively sorts.
Time Complexity: O(n log n) on average, O(n²) worst case
Space Complexity: O(log n)

Resources Links:
https://youtu.be/HGk_ypEuS24?si=Vvl5NYLW8BredO4O
https://youtu.be/WIrA4YexLRQ?si=KJ64YyjUBsvMjOih
https://youtu.be/ogjf7ORKfd8?si=dW_1H3lDk4oXYO-r

Assignment Link:
https://1drv.ms/w/c/3d3dfac7f44bdc27/EQZ8AZbd9vpMgybqvq0-hCsBIff6sSxoBrh52wUWR19cxA?e=GcF0fL

Submission Link:
https://drive.google.com/drive/folders/1BL6Hwfy1pDXzpPEV9zeJXD_QIRXkoHLk?usp=sharing

**Week-3 : Advanced Problems + Binary Trees**

1) Union of Intervals
--> Given overlapping intervals, calculate the total length covered without double-counting overlaps.
--> Requires sorting + merge logic.

2) Count Inversions

--> Count how far an array is from being sorted.

--> Can be solved efficiently using modified Merge Sort.

3) Search in a Matrix

--> Given a sorted 2D matrix, search for a number.

--> Variants include linear search from corners or applying binary search in flattened form.

4) Skyline Area Problem

--> Calculate the area of a city skyline by removing overlaps and invisible parts.

--> Use a sweep line algorithm or segment tree for optimal solution.

5) Minimum Pages Problem

--> Divide books among students to minimize the maximum pages any student reads.

--> Apply Binary Search on Answer strategy.

New Concepts: Binary Trees
1)Binary Tree (BT)
--> Each node has at most 2 children: left and right.
--> Basic building block for many tree structures.

2) Binary Search Tree (BST)
--> Left subtree contains values < root, right subtree > root.
--> Enables efficient search, insertion, and deletion in O(log n) time (avg case).

   Resources Links:
   1. Tree representation - https://www.youtube.com/watch?v=ctCpP0RFDFc&feature=youtu.be
   2. preorder - https://youtu.be/RlUu72JrOCQ
   3. inorder - https://youtu.be/Z_NEgBgbRVI
   4. postorder - https://youtu.be/COQOU6klsBg
   5. Level order - https://youtu.be/EoAsWbO7sqg
   6. Height of BT - https://youtu.be/EoAsWbO7sqg
Also go through these: Top view of BT - https://youtu.be/Et9OCDNvJ78 --try to solve right/left view and bottom

Assignment Link:
https://1drv.ms/w/c/3d3dfac7f44bdc27/EQZ8AZbd9vpMgybqvq0-hCsBIff6sSxoBrh52wUWR19cxA?e=GcF0fL

Submission Link:
https://drive.google.com/drive/folders/1t6BKVEonamAGR2tn4qqk8vZwGZrZI77I?usp=drive_link

**Week-4 : Graphs Overview**
A graph is a collection of nodes (vertices) connected by edges. It is used to represent networks like roads, social connections, web links, etc.

Types of Graphs
Directed vs Undirected:

Directed → edges have direction (like one-way roads)

Undirected → edges go both ways

Weighted vs Unweighted:

Weighted → edges have cost/weight (e.g., distance, time)

Unweighted → edges are equal

Cyclic vs Acyclic:

Cyclic → contains loops

Acyclic → no cycles (e.g., trees are acyclic)

Connected vs Disconnected:

Connected → path exists between every pair

Disconnected → some nodes are isolated

Resources Links:

a)First read this for an overview(its just  for overview, so try to understand as much as you can): https://www.w3schools.com/dsa/dsa_theory_graphs.php

b)If you are not familiar with stack and queue refer to this links : 
stack:https://www.tutorialspoint.com/data_structures_algorithms/stack_algorithm.htm
 queue:https://www.tutorialspoint.com/data_structures_algorithms/dsa_queue.htm
 
c)Now go through this pdf for understanding of graphs, no need to look at code part (just make sure to understand the concept thoroughly) :
https://drive.google.com/file/d/1-XvPBVCM_BVrzcEvBX_3GMSHJJolBIFL/view?usp=sharing
(Optional videos to watch for more clarity(highly recommended to watch though)
     Listen to this video – for introduction to graphs.--https://www.youtube.com/watch?v=gTsoyORhqkg
     Listen to this video-for more clarity on bfs--https://www.youtube.com/watch?v=0u78hx-66Xk
     Listen to this video – for more clarity on dfs--https://www.youtube.com/watch?v=Y40bRyPQQr0
     These are just quick videos about bfs and dfs, do watch them for  better clarity.
         https://youtu.be/JM_Ni1roq7k?feature=shared - dfs
         https://youtu.be/cDS5ZTeANZM?feature=shared- bfs)
         
d)For in-depth understanding of bfs: refer to this link-https://www.tutorialspoint.com/data_structures_algorithms/breadth_first_traversal.htm
   For in-depth understanding of dfs: refer to this link-
https://www.tutorialspoint.com/data_structures_algorithms/depth_first_traversal.htm

Assignment Link:
https://1drv.ms/w/c/3d3dfac7f44bdc27/EQZ8AZbd9vpMgybqvq0-hCsBIff6sSxoBrh52wUWR19cxA?e=GcF0fL

Submission Link:
https://drive.google.com/drive/folders/17vxWNE51zdWY97C21rKS_7M6jcNSItGX?usp=drive_link

**Week-5 : Advanced Graphs Overview**

1) Time Complexity & Efficiency
--> Reinforce understanding of Big-O notation for analyzing performance.

--> Focus on worst-case, best-case, and average-case complexities.

--> Learn amortized analysis (e.g., for Union-Find or heaps).

--> Recognize time-space tradeoffs in graph algorithms like Dijkstra’s and Bellman-Ford.

2) Sorting & Searching
--> Practice advanced sorting algorithms (Merge Sort, Heap Sort).

--> Understand the role of sorting in MST algorithms (e.g., Kruskal’s needs sorted edges).

--> Binary Search on arrays and custom conditions.

--> Learn how sorting optimizes greedy and interval-based problems.

3) Binary Search Mastery
--> Apply binary search on answer space (e.g., minimum effort path, max probability path).

--> Solve problems involving “smallest/largest value that satisfies condition.”

--> Combine with graphs or DP for optimization.

--> Practice pattern recognition: when to replace loops with binary search.

4) Advanced Data Structures
--> Tries: For prefix-based problems, word dictionaries.

--> Heaps: Used in Dijkstra’s and Prim’s algorithms for priority queue behavior.

--> Disjoint Set Union (DSU): Core for Kruskal’s MST and connected component problems.

--> Priority Queues: Solve problems with greedy selection based on cost/probability.

5) Problem-Solving Framework
--> Start from brute-force → identify bottlenecks → optimize.

--> Use patterns like:

a) Graph traversal (BFS/DFS → Dijkstra/Prim)

b) Greedy choices (Kruskal, activity selection)

c) Binary search on result space.

d) Break complex problems into subproblems (divide & conquer or recursion).

e) Build intuition by identifying graph types (DAG, weighted, unweighted).

Resources Links:
https://cses.fi/book/book.pdf
https://www.youtube.com/playlist?list=PLgUwDviBIf0pMFMWuuvDNMAkoQFi-h0ZF
https://drive.google.com/file/d/1ho6xPiOxzu2h8dieXAkaLz9G0pc7F0V2/view?usp=sharing

Assignment Link:
https://1drv.ms/w/c/3d3dfac7f44bdc27/EQZ8AZbd9vpMgybqvq0-hCsBIff6sSxoBrh52wUWR19cxA?e=GcF0fL

Submission Link:
https://drive.google.com/drive/folders/1RVF7hx9Wds8KCSMa-ai_EbKL_Yeo53h1?usp=sharing

**Week-6 : Greedy Algorithms Overview**

1) Greedy Algorithm Fundamentals
--> A greedy algorithm chooses the best option at the current step, hoping it leads to the global optimum.

Works when the problem satisfies:

--> Greedy Choice Property (local optimal = part of global optimal).

--> Optimal Substructure (optimal solution = combination of optimal subproblems).

--> Greedy is faster and often simpler than DP but doesn't work for all problems.

--> Key to success: Identify when greedy is safe to apply.

2) Classic Greedy Problems
--> Fractional Knapsack: Sort items by profit/weight ratio, take maximum possible value.

--> Activity Selection: Sort by end time; select non-overlapping intervals.

--> Huffman Encoding: Build tree using a priority queue of character frequencies.

--> These build a foundation for recognizing greedy problem structures.

3) Greedy Scheduling and Interval Problems
--> Job Sequencing: Maximize profit by assigning jobs to latest available slots.

--> Merge Overlapping Intervals: Sort by start, then merge if overlapping.

--> Minimum Platforms: Sort arrivals/departures, track simultaneous trains.

--> Maximum Trains at a Platform: Focus on maximizing platform usage with schedules.

--> These problems teach interval scheduling and event handling.

4) Optimization via Greedy Choices
--> Smallest Subset ≥ K: Sort descending, pick until sum ≥ K.

--> Shop in Candy Store: Sort by price, buy high-cost items, get lowest free.

--> Swap and Maximize: Greedily choose swaps that increase sum the most.

--> Min Cost to Make Size 1: Merge elements with minimum pair cost at each step.

--> These problems reinforce how sorting and priority queues help in greedy strategies.

5) Problem-Solving Framework
Begin with brute-force → identify greedy condition → apply and verify correctness.

Always test:

Does the greedy choice guarantee an optimal solution?

Can I prove greedy is better than DP for this case?

Draw test cases, simulate steps, and justify every decision.

Use sorting, heaps, or greedy slot allocation based on the problem’s structure.



