# Algorithms
This is just a refernce for common algorithms in case I need a refresher

## Binary Search Algorithm:

***Description***: A search algorithm that works on a sorted array by repeatedly dividing the search space in half.

***Big O notation***: O(log n) (where n is the size of the input array)

***Use case***: Searching for an element in a sorted array efficiently.

## Breadth First Search (BFS) Algorithm:

***Description***: A graph traversal algorithm that explores all the vertices of a graph in breadth-first order.

***Big O notation***: O(V + E) (where V is the number of vertices and E is the number of edges in the graph)

***Use case***: Shortest path problems, connected components, and graph exploration.

## Depth First Search (DFS) Algorithm:

***Description***: A graph traversal algorithm that explores as far as possible along each branch before backtracking.

***Big O notation***: O(V + E) (where V is the number of vertices and E is the number of edges in the graph)

***Use case***: Detecting cycles in a graph, topological sorting, and finding connected components.

## Merge Sort Algorithm:

***Description***: A comparison-based sorting algorithm that divides the input array into smaller subarrays, sorts them, and then merges them to obtain a sorted array.

***Big O notation***: O(n log n) (where n is the size of the input array)

***Use case***: Efficient sorting of large datasets, stable sorting.

## Quicksort Algorithm:

***Description***: A comparison-based sorting algorithm that partitions the array based on a chosen pivot element, and recursively sorts the subarrays on either side of the pivot.

***Big O notation***: O(n log n) (average case), O(n^2) (worst case)

***Use case***: General-purpose sorting, widely used in practice due to its efficiency.

## Kruskal’s Algorithm:

***Description***: A greedy algorithm that finds the minimum spanning tree of a connected weighted graph by adding edges in increasing order of weight, while avoiding cycles.

***Big O notation***: O(E log E) (where E is the number of edges in the graph)

***Use case***: Finding the minimum spanning tree, network design.

## Floyd Warshall Algorithm:

***Description***: An algorithm for finding the shortest paths between all pairs of vertices in a weighted directed graph.

***Big O notation***: O(V^3) (where V is the number of vertices in the graph)

***Use case***: Shortest path problems in graphs with negative edge weights.

## Dijkstra’s Algorithm:

***Description***: A greedy algorithm that finds the shortest path from a single source vertex to all other vertices in a weighted graph.

***Big O notation***: O((V + E) log V) with a binary heap (where V is the number of vertices and E is the number of edges in the graph)

***Use case***: Finding the shortest path in road networks, routing protocols.

## Bellman Ford Algorithm:

***Description***: An algorithm that finds the shortest path from a single source vertex to all other vertices in a weighted graph, even with negative edge weights.

***Big O notation***: O(V * E) (where V is the number of vertices and E is the number of edges in the graph)

***Use case***: Shortest path problems with negative edge weights.

## Kadane’s Algorithm:

***Description***: An algorithm for finding the maximum subarray sum in a given array of integers.

***Big O notation***: O(n) (where n is the size of the input array)

***Use case***: Finding the largest sum of a contiguous subarray within a larger array.

## Lee Algorithm:

***Description***: An algorithm for finding the shortest path between two points in a grid using breadth-first search.

***Big O notation***: O(V + E) (where V is the number of vertices and E is the number of edges in the grid)

***Use case***: Pathfinding in grid-based environments, maze solving.

## Flood Fill Algorithm:

***Description***: An algorithm that determines the area connected to a given cell in a multi-dimensional array and fills it with a specific color.

***Big O notation***: O(n) (where n is the number of cells in the connected area)

***Use case***: Image processing, bucket fill tools in graphics editors.

## Floyd’s Cycle Detection Algorithm:

***Description***: An algorithm that detects cycles in a linked list by using two pointers, one moving slower than the other.

***Big O notation***: O(n) (where n is the length of the linked list)

***Use case***: Detecting and removing cycles in linked lists.

## Union Find Algorithm:

***Description***: A data structure and algorithm for efficiently keeping track of a partition of a set into disjoint subsets.

***Big O notation***: O(log n) (where n is the number of elements)

***Use case***: Disjoint-set data structure, solving connectivity problems, cycle detection.

## Topological Sort Algorithm:

***Description***: An algorithm that orders the vertices of a directed acyclic graph in such a way that for every directed edge (u, v), vertex u comes before v in the ordering.

***Big O notation***: O(V + E) (where V is the number of vertices and E is the number of edges in the graph)

***Use case***: Task scheduling, dependency resolution, build systems.

## KMP Algorithm (Knuth-Morris-Pratt Algorithm):

***Description***: A string matching algorithm that finds occurrences of a pattern in a given text efficiently by utilizing information from previously matched characters.

***Big O notation***: O(n + m) (where n is the length of the text and m is the length of the pattern)

***Use case***: String searching, text processing.

## Insertion Sort Algorithm:

***Description***: A simple sorting algorithm that builds a sorted array one element at a time by repeatedly inserting the next element into its correct position.

***Big O notation***: O(n^2) (where n is the size of the input array)

***Use case***: Small input sizes, partially sorted arrays.

## Selection Sort Algorithm:

***Description***: A simple sorting algorithm that repeatedly selects the smallest (or largest) element from the unsorted portion of the array and places it at the beginning of the sorted portion.

***Big O notation***: O(n^2) (where n is the size of the input array)

***Use case***: Small input sizes, simplicity.

## Counting Sort Algorithm:

***Description***: A non-comparison-based sorting algorithm that counts the number of occurrences of each distinct element in the input array and uses this information to reconstruct a sorted array.

***Big O notation***: O(n + k) (where n is the size of the input array and k is the range of input values)

***Use case***: Sorting integers within a known range, stable sorting.

## Heap Sort Algorithm:

***Description***: A comparison-based sorting algorithm that uses a binary heap data structure to efficiently build a sorted array.

***Big O notation***: O(n log n) (where n is the size of the input array)

***Use case***: In-place sorting, guaranteed worst-case time complexity.

## Huffman Coding Compression Algorithm:

***Description***: A lossless data compression algorithm that assigns variable-length codes to different characters based on their frequencies in the input data.

***Big O notation***: O(n log n) (where n is the size of the input data)

***Use case***: File compression, data storage optimization.

## Quickselect Algorithm:

***Description***: A selection algorithm that finds the kth smallest element in an unordered list without completely sorting it.

***Big O notation***: O(n) (where n is the size of the input list)

***Use case***: Finding the median, order statistics.

## Boyer-Moore Majority Vote Algorithm:

***Description***: An algorithm for finding the majority element (an element that appears more than n/2 times) in an array.

***Big O notation***: O(n) (where n is the size of the input array)

***Use case***: Finding the majority element efficiently.

## Euclid’s Algorithm:

***Description***: An algorithm for finding the greatest common divisor (GCD) of two integers using repeated divisions.

***Big O notation***: O(log(min(a, b))) (where a and b are the input integers)

***Use case***: Computing the GCD, simplifying fractions.
