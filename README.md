# The Low-level Design Primer

Low-level design (LLD) is a componenet-level design process and is frequently used while designing data structures, and algorithms. It is also known as Object-Oriented Design (OOD), micro-level/detailed design. In general, a low-level design consists of class diagrams, program specifications and other low-level details for a given software componenet. During the LLD phase, the actual software components are designed by defining the logical and functional segments whereas design of application structure is developed during the high=level design phase. Low-level design is often created based on the high-level design.

## Motivation

> Learn how to design a given system in an object-oriented approach.
>
> Prep for the low-level design interview.

## Low-level design interview questions with solutions

> Common low-level design interview questions with sample discussions, code, and diagrams.
>
> Solutions linked to content in the `solutions/` folder.

| Question                                |                                                                                                                                            |
| --------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| Design a Parking Lot                    | [Solution](https://github.com/donnemartin/system-design-primer/blob/master/solutions/object_oriented_design/parking_lot/parking_lot.ipynb) |
| Design Poker Game - Under Development   | [Solution](https://github.com/bharatsesham/low-level-design-primer/blob/main/solutions/poker_game.ipynb)                                   |
| Design an Online Shopping Platform      | [Contribute](#contributing)                                                                                                                |
| Design a Movie Ticket Booking System    | [Contribute](#contributing)                                                                                                                |
| Design Facebook                         | [Contribute](#contributing)                                                                                                                |
| Design a Car Rental System              | [Contribute](#contributing)                                                                                                                |
| Design an Online Stock Brokerage System | [Contribute](#contributing)                                                                                                                |
| Design Blackjack                        | [Contribute](#contributing)                                                                                                                |
| Design an Airline Management System     | [Contribute](#contributing)                                                                                                                |
| Design an ATM                           | [Contribute](#contributing)                                                                                                                |
| Design a Hotel Management System        | [Contribute](#contributing)                                                                                                                |
| Add a system design question            | [Contribute](#contributing)                                                                                                                |

## Contributing

> Learn from the community.

Feel free to submit pull requests to help:

- Fix errors
- Improve sections
- Add new sections

## Index of low-level design topics

- [Low-level design topics: start here](#low-level-design-topics-start-here)
  - [Step 1: Object Oriented Basics](#step-1-object-oriented-basics)
  - [Step 2: Object Oriented Analysis and Design](#step-2-object-oriented-analysis-and-design)
  - [Step 3: UML and Diagrams](#step-3-uml-and-diagrams)
  - [Step 4: Distributed Systems Concepts](#step-4-distributed-systems-concepts)
  - [Step 5: Crptography](#step-5-cryptography)
  - [Next steps](#next-steps)
- [Programming Logic](#programming-logic)
  - [Basics](#basics)
  - [Algorithms](#algorithms)
  - [Data Structures](#data-structures)
- [Design Patterns](#design-patterns)
- [Architectural Patterns](#architectural-patterns)
- [Appendix](#appendix)
- [Under development](#under-development)
- [Credits](#credits)
- [Contact info](#contact-info)
- [Additional Resources](#additional-resources)
- [Inspiration](#inspiration)
- [License](#license)

## Low-level design topics: start here

New to low-level design?

First, you'll need a basic understanding of OOPS concepts, learning about what they are, how they are used, and their pros and cons.

### Step 1: Object Oriented Basics

### Step 2: Object Oriented Analysis and Design

### Step 3: UML and Diagrams

- Topics covered:
  - Use Case Diagrams
  - Class Diagram
  - Sequence Diagram
  - Activity Diagrams

### Step 4: Distributed Systems Concepts

### Step 5: Cryptography

Cryptography is the practice of securely communicating information by transforming it into an unreadable format (ciphertext) to prevent unauthorized access. Cryptography can be divided into two main categories: classical cryptography and modern cryptography. Classical cryptography uses techniques such as substitution ciphers and transposition ciphers, while modern cryptography uses mathematical algorithms and computer technology to provide stronger security. Some common applications of cryptography include secure communication over the internet, data protection, and digital signatures. Some of the concepts related to cryptography are:

1.  Encryption: The process of transforming plaintext into an unreadable format (ciphertext) using an encryption algorithm and a key. The ciphertext can only be decrypted back into its original form using the same key. There are several types of encryption, including:

    - Symmetric encryption: Also known as shared secret encryption, uses the same key for both encryption and decryption. Examples include AES, DES, and Blowfish.

    - Asymmetric encryption: Also known as public key encryption, uses a pair of keys – one for encryption and another for decryption. Examples include RSA, Elliptic Curve Cryptography (ECC), and Diffie-Hellman.

    - Stream cipher: Encrypts data one bit or byte at a time, making it more suitable for real-time applications such as video and audio streaming. Examples include RC4 and Salsa20.

    - Block cipher: Encrypts data in fixed-size blocks, making it more suitable for encrypting large amounts of data. Examples include AES and DES.

    - Hash functions: A type of encryption that creates a fixed-length, unique value from an input message. Hash functions are commonly used for digital signatures, message authentication codes, and password storage. Examples include SHA-256, MD5, and SHA-3.

    - Elliptic Curve Cryptography (ECC): A type of public key encryption that uses the mathematics of elliptic curves to provide stronger security compared to traditional algorithms.

    - Homomorphic encryption: A type of encryption that allows computations to be performed on ciphertext, producing an encrypted result which, when decrypted, is the same as if the computation was performed on plaintext.

2.  Decryption: The process of transforming ciphertext back into its original form (plaintext) using the same key and decryption algorithm used for encryption.

3.  Key: A secret value used in the encryption and decryption process to control the transformation of plaintext into ciphertext and vice versa. The key is used to control the strength of the encryption and ensure that the ciphertext can only be decrypted by authorized individuals.

4.  Algorithm: A set of mathematical steps and rules used to encrypt and decrypt data. Cryptographic algorithms are divided into symmetric (using the same key for encryption and decryption) and asymmetric (using a pair of keys for encryption and decryption). Some of the commonly used cryptographic algorithms are:

    - Symmetric Key Algorithms:
      - Advanced Encryption Standard (AES)
      - Data Encryption Standard (DES)
      - Blowfish
      - Twofish
        <br />

    * Asymmetric Key Algorithms (Public Key Cryptography):
      - Rivest-Shamir-Adleman (RSA)
      - Elliptic Curve Cryptography (ECC)
      - Digital Signature Algorithm (DSA)
      - Elliptic Curve Digital Signature Algorithm (ECDSA)
        <br />

    - Hash Functions:
      - Message Digest Algorithm 5 (MD5)
      - Secure Hash Algorithm (SHA)
      - SHA-256
      - SHA-3
        <br />

    * Key Derivation Functions (KDFs):
      - PBKDF2 (Password-Based Key Derivation Function 2)
      - scrypt
      - Argon2
        <br />

    - Stream Ciphers:
      - RC4
      - Salsa20
      - ChaCha20

    These are just a few examples of cryptographic algorithms. The selection of the appropriate algorithm depends on the specific security requirements of the application and the amount of computational resources available. Cryptographic algorithms are constantly being improved and updated to provide stronger security, and new algorithms are being developed as the need for stronger security arises.

5.  Cryptanalysis: The study and practice of analyzing and breaking cryptographic systems. Cryptanalysts use mathematical and computational methods to attempt to crack cryptographic systems and gain access to the original plaintext.

6.  Key management: The process of generating, distributing, and storing keys in a secure manner to ensure the confidentiality, integrity, and authenticity of encrypted data.

7.  Cryptographic protocols: Sets of rules and procedures used to securely communicate information and perform cryptographic operations, such as digital signatures and secure key exchange. Some of the common cryptographic protocols are:

    - Secure Socket Layer (SSL) / Transport Layer Security (TLS): A protocol used to secure web communications, including email and online transactions.

    - Internet Protocol Security (IPSec): A protocol used to secure Internet Protocol (IP) communications, including Virtual Private Network (VPN) connections.

    - Pretty Good Privacy (PGP): A protocol used to encrypt and sign emails, files, and other types of data.

    - Secure Shell (SSH): A protocol used to securely access remote servers and network devices.

    - File Transfer Protocol Secure (FTPS): A protocol used to securely transfer files over the internet.

    - Wireless Protected Access (WPA): A protocol used to secure wireless networks.

    - Digital Signature Algorithm (DSA): A protocol used to generate digital signatures, which can be used to verify the authenticity and integrity of electronic documents and messages.

    - Elliptic Curve Digital Signature Algorithm (ECDSA): A protocol used to generate digital signatures using the mathematics of elliptic curves.

    - Secure Remote Password (SRP): A protocol used to securely authenticate users over the internet, without sending passwords in the clear.

    - Kerberos: A protocol used to securely authenticate users on computer networks.

    These are just a few examples of cryptographic protocols. The selection of the appropriate protocol depends on the specific security requirements of the communication or operation being performed.

## Programming Logic

In this topic, we will concentrate on the brains of the problem solution. While design components are important, logic is what determines how a software works. The logic often composed of various algorithms and data strucutres. Also, data structures and algorithms play a major role in the hiring process as well. In this section, the idea is to go over some of the popular algorithms and data structures that are crucial for any aspiring software engineer. We can start off the discussion by discussing some of the basics concepts like Time and Space complexity which can be used to analyse the performance of the algorithms.

### Basics

### Algorithms

1. Sorting algorithms: Algorithms for sorting arrays or lists of elements, such as QuickSort, MergeSort, and HeapSort.

2. Search algorithms: Algorithms for searching arrays or lists for specific elements, such as Binary Search and Linear Search.

3. Graph algorithms: Algorithms for processing graph data structures, such as Depth-First Search (DFS), Breadth-First Search (BFS), and Dijkstra's Shortest Path algorithm.

4. Dynamic Programming algorithms: Algorithms for solving problems by breaking them down into smaller sub-problems and storing their solutions, such as the Longest Common Subsequence (LCS) algorithm.

5. Divide and conquer algorithms: Algorithms for solving problems by breaking them down into smaller sub-problems and solving them recursively, such as the Fast Fourier Transform (FFT) algorithm.

6. Greedy algorithms: Algorithms for solving problems by making the locally optimal choice at each step, such as the Kruskal's algorithm for finding minimum spanning trees in a graph.

7. Backtracking algorithms: Algorithms for finding solutions to problems by trying out potential solutions and undoing them if they don't work, such as the N-Queens problem.

8. Randomized algorithms: Algorithms that use randomization to solve problems, such as the QuickSort algorithm.

9. String algorithms: Algorithms for processing strings, such as the Knuth-Morris-Pratt (KMP) algorithm for string matching.

10. NP-hard and NP-complete problems: Algorithms for solving some of the most difficult problems in computer science, such as the Traveling Salesman Problem and the Boolean Satisfiability Problem.

#### More specific algorithms:

1. Matrix algorithms: Algorithms for processing matrices, such as Gaussian elimination and LU decomposition.

2. Computational geometry algorithms: Algorithms for processing geometric data, such as Convex Hull, Closest Pair of Points, and Line Intersection algorithms.

3. Machine learning algorithms: Algorithms for training models on data and making predictions, such as Linear Regression, Logistic Regression, and Support Vector Machines (SVMs).

4. Computer vision algorithms: Algorithms for processing image and video data, such as Image Segmentation, Object Detection, and Face Recognition algorithms.

5. Network algorithms: Algorithms for processing data in networks, such as PageRank for analyzing the importance of nodes in a graph and Maximum Flow algorithms for finding the maximum flow in a network.

6. Cryptographic algorithms: Algorithms for securing data, such as RSA for public key encryption and SHA-256 for hash functions.

7. Compression algorithms: Algorithms for reducing the size of data, such as Huffman coding and LZ77 compression.

8. Parallel algorithms: Algorithms that can be executed in parallel to speed up processing, such as MapReduce and the Parallel Prefix Sum (also known as Scan) algorithm.

9. Artificial Intelligence algorithms: Algorithms for simulating human intelligence, such as Artificial Neural Networks and Genetic Algorithms.

10. Blockchain algorithms: Algorithms for secure and decentralized data storage and processing, such as the Proof-of-Work (PoW) algorithm used in Bitcoin.

11. Pattern matching algorithms: Algorithms for matching patterns in data, such as the Knuth-Morris-Pratt (KMP) algorithm for string matching.

12. Approximation algorithms: Algorithms that produce approximate solutions to NP-hard problems, such as the Metropolis Algorithm for simulating physical systems.

13. Monte Carlo algorithms: Algorithms that use random sampling to solve problems, such as the Monte Carlo Tree Search (MCTS) algorithm for game-playing AI.

14. Recommender systems algorithms: Algorithms for making personalized recommendations, such as Collaborative Filtering and Matrix Factorization.

15. Error correcting algorithms: Algorithms for detecting and correcting errors in data, such as Error Correction Codes (ECC) and Reed-Solomon codes.

16. Scheduling algorithms: Algorithms for scheduling tasks and resources, such as the Round Robin scheduling algorithm for CPU scheduling.

17. Decision tree algorithms: Algorithms for creating decision trees for decision making, such as the C4.5 algorithm for constructing decision trees from data.

18. Genetic algorithms: Algorithms that mimic the process of natural selection and evolution to find solutions to optimization problems.

19. Clustering algorithms: Algorithms for grouping similar data points into clusters, such as K-Means and Hierarchical Clustering.

20. Deep learning algorithms: Algorithms that use deep neural networks to learn from data, such as Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs).

#### Interview Coding Patterns

**1. Sliding Window**
<table>
  <tr>
    <td valign="top" border="0px">
The sliding window algorithm is a technique used to process sequences of elements, such as arrays or strings. It works by maintaining a "window" of elements, and moving this window along the sequence, processing the elements within the window at each step. The size of the window is determined by the specific problem that needs to be solved, and the processing of the elements within the window is determined by the algorithm's implementation. The Sliding Window pattern is a useful technique for solving many problems, such as finding the longest substring with non-repeating characters, or the minimum window in a string containing all characters of another string.
    </td>
  </tr>
<tr>
  <td align="center" border="0px">
    Longest Substring Without Repeating Characters

  <img src="https://github.com/bharatsesham/low-level-design-primer/blob/main/metadata/media/Sliding_Window.gif" width="760" height="120"/>
  </td>
</tr>
</table>


Pseudo code for a sliding window algorithm:

```python
def sliding_window(sequence, window_size):
    n = length of sequence
    window_start = 0
    window_end = 0

    while window_end < n:
        while (window_end - window_start + 1 <= window_size) and (window_end < n):
            process element at index window_end
            window_end = window_end + 1

        process elements in the current window [window_start, window_end-1]

        while (window_end - window_start + 1 > window_size) and (window_start < n):
            process element at index window_start
            window_start = window_start + 1

    return result
```

**2. Islands (Matrix Traversal)**
<table>
  <tr>
    <td valign="top" border="0px">
The Islands problem involves finding the number of distinct islands in a 2D grid composed of '1's (land) and '0's (water). An island is formed by connecting adjacent lands horizontally or vertically (not diagonally). The goal is to count the number of such islands within the grid or something similar. This problem is a classic application of graph traversal algorithms like Depth First Search (DFS) or Breadth First Search (BFS). Each cell in the grid can be considered as a node in a graph, and edges exist between horizontally or vertically adjacent land cells. By traversing the grid and performing a DFS or BFS from each unvisited land cell, we can mark all connected land cells as part of the same island.
  </td>
    <td>
<img src="https://github.com/bharatsesham/low-level-design-primer/blob/main/metadata/media/Island_Traversal.gif" width="285" height="285"/>
</td> 
</tr>
</table>

Pseudo code for an Island Traversal:

```python
def numIslands(grid):
    if not grid:
        return 0
    number_of_islands = 0
    rows = len(grid)
    cols = len(grid[0])
    for i in range(rows):
        for j in range(cols):
            if grid[i][j] == '1':
                DFS(grid, i, j)
                number_of_islands += 1
    return number_of_islands

def DFS(grid, i, j):
    rows = len(grid)
    cols = len(grid[0])
    # Base case: check boundaries and if the cell is water or already visited
    if i < 0 or i >= rows or j < 0 or j >= cols or grid[i][j] != '1':
        return
    grid[i][j] = '0'  # Mark the cell as visited by sinking the island
    # Recursively visit all adjacent cells (up, down, left, right)
    DFS(grid, i + 1, j)  # Down
    DFS(grid, i - 1, j)  # Up
    DFS(grid, i, j + 1)  # Right
    DFS(grid, i, j - 1)  # Left

```
**3. Two Pointers**
<table>
  <tr>
    <td valign="top" border="0px">
      The Two Pointers technique is an algorithmic strategy that involves using two indices (pointers) to iterate through a data structure, typically an array or string. This method is especially effective for solving problems that require searching for pairs or sequences that satisfy certain conditions in a sorted data set.
    </td>
  </tr>
<tr>
  <td align="center" border="0px">
    2Sum using Two-pointer <br>

  <img src="https://github.com/bharatsesham/low-level-design-primer/blob/main/metadata/media/Two_Pointer.gif" width="760" height="110"/>
  </td>
</tr>
</table>


Pseudo code for a Two Pointer Technique:

```python
function findPairs(array, targetSum):
    left = 0
    right = length of array - 1

    while left < right:
        leftValue = array[left]
        rightValue = array[right]
        sum = leftValue + rightValue

        if sum == targetSum:
            output "Found pair:", leftValue, rightValue
            left = left + 1
            right = right - 1
        else if sum < targetSum:
            left = left + 1  // Move left pointer to the right to increase sum
        else:
            right = right - 1  // Move right pointer to the left to decrease sum
```

5. Fast & Slow Pointers
6. Merge Intervals
7. Cyclic Sort
8. In-place Reversal of a LinkedList
   
**8. Breadth-First Search**
<table>
  <tr>
    <td valign="top" border="0px">
Breadth-First Search (BFS) is an algorithm for traversing or searching a tree, graph or other data structure in breadth-first order. It visits all the vertices of a graph or all the nodes of a tree at the same level before going deeper. BFS is used to find the shortest path between two nodes or to find all nodes within a certain distance from a starting node. It operates by visiting all neighbors of a node before visiting their neighbors, ensuring that it visits nodes in the order of increasing distance from the starting node.

</td>
<td>
<img src="https://github.com/bharatsesham/low-level-design-primer/blob/main/metadata/media/BFS_tree.gif" width="250" height="250"/>
</td> </tr> </table>

Pseudo code for a breadth-first search algorithm on a graph:

```python
def BFS(graph G, start vertex s)
  let Q be a queue
  mark s as visited
  Q.enqueue(s)
  while Q is not empty
    v = Q.dequeue()
    for each unvisited neighbor w of v
      mark w as visited
      Q.enqueue(w)
```

Pseudo code for a breadth-first search algorithm on a tree:

```python
def BFS_on_tree(tree T, start node s)
  let Q be a queue
  mark s as visited
  Q.enqueue(s)
  while Q is not empty
    v = Q.dequeue()
    for each unvisited child w of v
      mark w as visited
      Q.enqueue(w)
```

**9. Depth First Search**
<table>
  <tr>
    <td valign="top" border="0px">
Depth First Search (DFS) is an algorithm for traversing and searching a graph or tree data structure. It starts at the root node and explores as far as possible along each branch before backtracking and visiting the next branch. The goal of DFS is to visit all the nodes of the graph or tree in a depth-first manner, i.e., visiting the children of a node before its siblings. The implementation of DFS can be done using a stack or through recursion. It is used in many applications, such as topological sorting, finding connected components, solving mazes and solving problems in artificial intelligence.

</td>
<td>
<img src="https://github.com/bharatsesham/low-level-design-primer/blob/main/metadata/media/DFS_tree.gif" width="250" height="250"/>
</td> </tr> </table>

Pseudo code for a depth-first search algorithm on a graph:

```python
def DFS(G, v):
    create a stack S
    mark v as visited
    push v onto S
    while S is not empty:
        t = S.pop()
        for all edges e in G.incidentEdges(t):
            w = G.opposite(t, e)
            if w is not visited:
                mark w as visited
                push w onto S

```

Pseudo code for a depth-first search algorithm on a tree:

```python
def DFS(T, v):
    mark v as visited
    for each child u of v in T:
        if u is not visited:
            DFS(T, u)

```


**10. Topological Sort** - Topological Sort is an algorithm used to linearize a directed acyclic graph (DAG) into a linear order of its vertices, such that for every directed edge (u, v), vertex u comes before vertex v in the linear order. In other words, it sorts the vertices of a graph such that all directed edges go from earlier vertices to later vertices in the linear order. Topological sort is commonly used to find a valid ordering of tasks, such as in scheduling problems, where some tasks must be completed before others can be started.

There are several algorithms for performing a topological sort, but one of the most common is the depth-first search (DFS) based algorithm. The idea behind this algorithm is to visit all vertices in a graph, track which vertices have been visited, and add a visited vertex to the linear order after all its outgoing edges have been processed.

Pseudo code for a topological sort algorithm on a graph:

```python
def topological_sort(graph):
    n = len(graph)
    visited = [False] * n
    stack = []

    def dfs(u):
        visited[u] = True
        for v in graph[u]:
            if not visited[v]:
                dfs(v)
        stack.append(u)

    for i in range(n):
        if not visited[i]:
            dfs(i)

    return list(reversed(stack))
```

In this example, graph is a representation of the directed acyclic graph as an adjacency list. The visited array keeps track of which vertices have been visited, and the stack is used to store the linear order of the vertices. The dfs function implements the depth-first search, visiting vertices and marking them as visited. The outer loop iterates over all vertices, calling dfs for each unvisited vertex. Finally, the linear order is returned as the reversed order of the stack, since vertices are added to the end of the stack during the depth-first search.

11. Two Heaps
12. Subsets
13. Modified Binary Search
14. Bitwise XOR
15. Top ‘K’ Elements
16. K-way Merge
17. 0/1 Knapsack
18. Fibonacci Numbers
19. Palindromic Subsequence
20. Longest Common Substring

### Data Structures

Data structures are a way of organizing and storing data in a computer program. There are several commonly used data structures in computer science, including:

#### Time Complexity

<!-- Markdown Time Complexity Table Start -->

<table class="tg">
<thead>
  <tr>
    <th class="tg-6fut" rowspan="3"><span style="background-color:#F1ECB6"> </span>Data Structure<span style="background-color:#F1ECB6"> </span></th>
    <th class="tg-6fut" colspan="8"><span style="background-color:#F1ECB6"> </span>Time Complexity<span style="background-color:#F1ECB6"> </span></th>
    <th class="tg-6fut"><span style="background-color:#F1ECB6"> </span>Space Complexity<span style="background-color:#F1ECB6"> </span></th>
  </tr>
  <tr>
    <th class="tg-6fut" colspan="4"><span style="background-color:#F1ECB6"> </span>Average<span style="background-color:#F1ECB6"> </span></th>
    <th class="tg-6fut" colspan="4"><span style="background-color:#F1ECB6"> </span>Worst<span style="background-color:#F1ECB6"> </span></th>
    <th class="tg-6fut" rowspan="2"><span style="background-color:#F1ECB6"> </span>Worst<span style="background-color:#F1ECB6"> </span></th>
  </tr>
  <tr>
    <th class="tg-6fut"><span style="background-color:#F1ECB6"> </span>Access<span style="background-color:#F1ECB6"> </span></th>
    <th class="tg-6fut"><span style="background-color:#F1ECB6"> </span>Search<span style="background-color:#F1ECB6"> </span></th>
    <th class="tg-6fut"><span style="background-color:#F1ECB6"> </span>Insertion<span style="background-color:#F1ECB6"> </span></th>
    <th class="tg-6fut"><span style="background-color:#F1ECB6"> </span>Deletion<span style="background-color:#F1ECB6"> </span></th>
    <th class="tg-6fut"><span style="background-color:#F1ECB6"> </span>Access<span style="background-color:#F1ECB6"> </span></th>
    <th class="tg-6fut"><span style="background-color:#F1ECB6"> </span>Search<span style="background-color:#F1ECB6"> </span></th>
    <th class="tg-6fut"><span style="background-color:#F1ECB6"> </span>Insertion<span style="background-color:#F1ECB6"> </span></th>
    <th class="tg-6fut"><span style="background-color:#F1ECB6"> </span>Deletion<span style="background-color:#F1ECB6"> </span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/Array_data_structure" target="_blank" rel="noopener noreferrer">Array</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">Θ(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">Θ(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">Θ(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">O(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/Stack_(abstract_data_type)" target="_blank" rel="noopener noreferrer">Stack</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">Θ(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">Θ(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">O(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">O(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/Queue_(abstract_data_type)" target="_blank" rel="noopener noreferrer">Queue</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">Θ(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">Θ(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">O(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">O(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/Singly_linked_list#Singly_linked_lists" target="_blank" rel="noopener noreferrer">Singly-Linked List</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">Θ(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">Θ(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">O(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">O(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/Doubly_linked_list" target="_blank" rel="noopener noreferrer">Doubly-Linked List</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">Θ(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">Θ(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">O(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">O(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/Binary_search_tree" target="_blank" rel="noopener noreferrer">Binary Search Tree</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/Skip_list" target="_blank" rel="noopener noreferrer">Skip List</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-0zjz"><span style="background-color:#FCAD29"> </span><span style="color:#000">O(n log(n))</span><span style="background-color:#FCAD29"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/Hash_table" target="_blank" rel="noopener noreferrer">Hash Table</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-vq3a"><span style="background-color:#D4D4D4"> </span><span style="color:#000">N/A</span><span style="background-color:#D4D4D4"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-ra3r"><span style="background-color:#3EC509"> </span><span style="color:#000">Θ(1)</span><span style="background-color:#3EC509"> </span></td>
    <td class="tg-vq3a"><span style="background-color:#D4D4D4"> </span><span style="color:#000">N/A</span><span style="background-color:#D4D4D4"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="https://en.wikipedia.org/wiki/Cartesian_tree" target="_blank" rel="noopener noreferrer">Cartesian Tree</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-vq3a"><span style="background-color:#D4D4D4"> </span><span style="color:#000">N/A</span><span style="background-color:#D4D4D4"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-vq3a"><span style="background-color:#D4D4D4"> </span><span style="color:#000">N/A</span><span style="background-color:#D4D4D4"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/B_tree" target="_blank" rel="noopener noreferrer">B-Tree</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/Red-black_tree" target="_blank" rel="noopener noreferrer">Red-Black Tree</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="https://en.wikipedia.org/wiki/Splay_tree" target="_blank" rel="noopener noreferrer">Splay Tree</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-vq3a"><span style="background-color:#D4D4D4"> </span><span style="color:#000">N/A</span><span style="background-color:#D4D4D4"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-vq3a"><span style="background-color:#D4D4D4"> </span><span style="color:#000">N/A</span><span style="background-color:#D4D4D4"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/AVL_tree" target="_blank" rel="noopener noreferrer">AVL Tree</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">O(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
  <tr>
    <td class="tg-vd55"><span style="background-color:#F1ECB6"> </span><a href="http://en.wikipedia.org/wiki/K-d_tree" target="_blank" rel="noopener noreferrer">KD Tree</a><span style="background-color:#F1ECB6"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-m3yf"><span style="background-color:#B1EA0D"> </span><span style="color:#000">Θ(log(n))</span><span style="background-color:#B1EA0D"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
    <td class="tg-vd15"><span style="background-color:#FFFF10"> </span><span style="color:#000">O(n)</span><span style="background-color:#FFFF10"> </span></td>
  </tr>
</tbody>
</table>

<!-- Markdown Time Complexity Table End -->

#### Basic Data Structures

The basic data structures used in computer science include:

- **LinkedList** - A linked list is a linear data structure where each element, called a node, points to the next node in the list. It consists of a head, which points to the first node, and a tail, which points to the last node. The nodes contain a value and a reference to the next node. Linked lists can be used to implement various abstract data types like stacks, queues, and associative arrays. The advantage of linked lists over arrays is that elements can be efficiently inserted or removed without reallocation or reorganization of the entire structure because only a few links need to be changed.

Some of the use-cases of linkedlist are:

1. Dynamic memory allocation: Linked lists can be used to allocate memory dynamically, making it easier to manage memory usage.

2. Stacks and Queues: Linked lists can be used to implement stacks and queues, which are commonly used in computer science and software engineering.

3. Polynomial Representation: Linked lists can be used to represent polynomials in mathematics, where each node can represent a term in the polynomial.

4. Sparse Matrices: Linked lists can be used to efficiently store sparse matrices, where most elements are zero.

5. Undo/Redo Operations: Linked lists can be used to implement undo/redo operations in text editors and other software applications.

6. Implementing Graphs: Linked lists can be used to implement graphs, where each node represents a vertex, and the reference to the next node represents an edge.

7. Circular Linked Lists: Circular linked lists can be used to implement certain data structures like hash tables, where indexing is based on the value of a key modulo the size of the hash table.

- **Set** - A set is a collection of unique elements. Sets are commonly used in computer science to store and manipulate collections of elements without duplicates. In programming, sets are usually implemented using a hash table or a tree structure. This allows for efficient operations such as add, remove, and search in constant time, on average. Some common use cases for sets include checking for duplicates in a collection, performing set operations such as union, intersection, and difference, and testing for membership in a collection.

Some of the use-cases of sets are:

1. Removing duplicates: Sets can be used to store a collection of elements, automatically removing duplicates, making it useful for tasks such as checking for duplicates in a list.

2. Set operations: Sets can be used to perform set operations, such as union, intersection, and difference, which are useful for solving problems in areas such as database management and information retrieval.

3. Membership testing: Sets can be used to efficiently test for membership in a collection of elements, making it useful for tasks such as searching a list of items.

4. Handling large datasets: Sets can be used to store and process large datasets, taking advantage of the efficient set operations and membership tests.

5. Representing relationships: Sets can be used to represent relationships between elements, such as the relationships between people in a social network.

6. Modeling concepts: Sets can be used to model abstract concepts, such as sets of mathematical objects, making it useful for tasks such as solving mathematical problems.

7. Filtering data: Sets can be used to filter data, such as removing duplicates from a list or selecting items that meet certain criteria.

- **Stack** - A stack is a linear data structure that follows the Last-In-First-Out (LIFO) principle (meaning that the last item to be added to the stack is the first one to be removed). Stacks can be implemented using an array or a linked list. In both cases, the basic operations on a stack include push (adding an element to the top of the stack), pop (removing the top element), and peek (accessing the top element without removing it). Stacks are efficient data structures, with operations such as push and pop taking constant time, on average. However, they generally tend have a limited size and can only be used for specific types of problems.

Some of the use-cases of stack are:

1. Function call management: Stacks are used to manage function calls in programming languages, keeping track of the function calls that have been made and in what order. This is known as the call stack.

2. Reversing data: Stacks can be used to reverse the order of elements in a collection, such as reversing a string.

3. Evaluating expressions: Stacks can be used to evaluate expressions written in Reverse Polish Notation (RPN), a mathematical notation where operators follow the operands.

4. Undo/Redo functionality: Stacks can be used to implement undo and redo functionality in applications, allowing users to revert or repeat actions.

5. Balancing symbols: Stacks can be used to verify the balance of symbols in a string, such as matching parentheses or brackets in a code snippet.

6. Navigation history: Stacks can be used to keep track of a user's navigation history in a web browser or application, allowing users to go back to previously visited pages or states.

7. Pathfinding algorithms: Stacks can be used in pathfinding algorithms, such as breadth-first search and depth-first search, to keep track of the nodes that need to be processed.

- **Queue** - A queue is a linear data structure that follows the First-In-First-Out (FIFO) principle (meaning that the first item to be added to the queue is the first one to be removed). Queues can be implemented using an array or a linked list. In both cases, the basic operations on a queue include enqueue (adding an element to the end of the queue), dequeue (removing the front element), and peek (accessing the front element without removing it). Queues are efficient data structures, with operations such as enqueue and dequeue taking constant time, on average. However, they generally tend to have a limited size and can only be used for specific types of problems.

Some of the use-cases of queue are:

1. Task management: Queues can be used to manage tasks or jobs, such as scheduling print jobs or network requests.

2. Event management: Queues can be used to manage events, such as processing mouse clicks or keyboard presses in a graphical user interface.

3. Breadth-first search: Queues can be used in breadth-first search algorithms, where nodes are added to the queue in the order that they are discovered, and processed in the order in which they were added.

4. Simulation: Queues can be used to model and simulate real-world systems, such as a line at a bank or a line of customers waiting for service.

5. Load balancing: Queues can be used to distribute load across multiple processors or servers, ensuring that tasks are processed in a fair and efficient manner.

6. Communication systems: Queues can be used in communication systems, such as packet switching networks, where packets of data are added to a queue for transmission and removed in the order in which they were added.

7. Asynchronous processing: Queues can be used to implement asynchronous processing, where tasks are added to a queue for processing in the background, allowing the main thread to continue executing.

- **Array** - An array is a data structure that stores a collection of elements, each identified by a unique index or position. Arrays are used to store and manage large amounts of data, and they can be dynamically resized to accommodate changes in the size of the data set. Arrays are typically implemented as contiguous blocks of memory, allowing fast and efficient access to individual elements. This makes arrays particularly useful for operations that require frequent access to specific elements, such as search, sort, and manipulation of individual elements. Arrays have several advantages, including: Constant time access (Arrays provide constant time access to individual elements, making them ideal for applications where quick access to specific elements is important), Efficient memory utilization (Arrays store elements in contiguous blocks of memory, making efficient use of memory), Easy manipulation (Arrays allow for easy manipulation of individual elements, including insertion, deletion, and modification). However, arrays also have some disadvantages, such as: Fixed size (Arrays have a fixed size, making them less flexible than other data structures, such as linked lists, for handling changes in the size of the data set), Linear search time (Arrays have a linear search time, meaning that finding a specific element requires iterating through the entire array). Despite these limitations, arrays are widely used and remain a fundamental building block of computer programming and software engineering.

Some of the use-cases of array are:

1. Representing a list of items, such as the names of students in a class or products in a shopping cart.

2. Performing mathematical operations, such as finding the average of a set of numbers or multiplying matrices.

3. Implementing dynamic data structures, such as stacks and queues, which can grow and shrink as needed.

4. Storing and retrieving data efficiently, as arrays provide constant time access to individual elements based on their index.

5. Used in various algorithms, such as searching and sorting, as arrays can be easily manipulated to store and rearrange data.

- **HashMap** - A hash map, also known as a dictionary or associative array, is a data structure that maps keys to values. It uses a hash function to compute an index into an array of buckets or slots, from which the desired value can be found. The hash function takes the key as input and returns an integer, which is used as the index for the value in the array. When multiple keys have the same hash value, a collision occurs, and the hash map uses a collision resolution technique such as chaining (linked list) or open addressing (probing) to handle the collision. The main advantage of hash maps over other data structures such as arrays or linked lists is their constant-time average O(1) lookup time for finding values, making them very efficient for large data sets.

Some of the use-cases of hashmap are:

1. Caching: Hash maps can be used to implement caches, which store frequently used data to speed up access.

2. Indexing: Hash maps can be used as an index in databases and other data storage systems to allow for fast searching and retrieval of data.

3. Spell Checking: Hash maps can be used to implement spell checkers, where the keys are words and the values are booleans indicating whether a word is correctly spelled.

4. Frequency Counting: Hash maps can be used to count the frequency of elements in a data set, where the keys are elements and the values are their frequencies.

5. Word Counting: Hash maps can be used to count the occurrences of words in a document, where the keys are words and the values are their frequencies.

6. Graph Algorithms: Hash maps can be used in graph algorithms to store and retrieve data about vertices and edges.

7. Associative Arrays: Hash maps can be used as associative arrays, where the keys are arbitrary values and the values are the data associated with those keys.

8. Implementing Maps: Hash maps can be used to implement maps in programming languages, where keys can be of any type and values can be of any type.

- **Heap** - A heap is a tree-based data structure that satisfies the heap property, which states that the value of each node is either greater than or equal to (for a max-heap) or less than or equal to (for a min-heap) the values of its children. Heaps are commonly implemented as binary trees, where each node has at most two children. The root node of a heap is always the node with the largest (for a max-heap) or smallest (for a min-heap) value. Some of the operations that heap supports are: Insertion (To insert a new element into a heap, it is added to the end of the tree and then compared to its parent. If the heap property is violated, the elements are swapped until the property is restored), Extract Max/Min (To extract the maximum (for a max-heap) or minimum (for a min-heap) element from a heap, the root node is removed and replaced with the last element in the tree. The new root node is then compared to its children and swapped with the larger (for a max-heap) or smaller (for a min-heap) of the two until the heap property is restored), Delete (To delete an element from a heap, it can be replaced with a special value (such as -infinity) and then extracted), Peek (To view the maximum (for a max-heap) or minimum (for a min-heap) element in a heap without removing it, simply access the root node), Increase/Decrease Key (To change the value of an element in a heap, it is first removed and then reinserted with the new value), Merge (To merge two heaps into a single heap, the elements of one heap can be added to the other, and then the resulting heap can be rebuilt to restore the heap property).

Some of the use-cases of heap are:

1. Priority Queues: Heaps can be used to implement priority queues, where the element with the highest (for a max-heap) or lowest (for a min-heap) priority is always removed first.

2. Sorting Algorithms: Heapsort, a comparison-based sorting algorithm, uses a max-heap to sort an array of elements in ascending order.

3. Graph Algorithms: Heaps can be used in graph algorithms, such as Dijkstra's shortest path algorithm, to efficiently find the minimum value in a set of vertices.

4. Median Maintenance: Heaps can be used to maintain the median of a set of elements in an efficient manner, by using a max-heap and a min-heap.

5. Implementing Multilevel Priority Queues: Heaps can be used to implement multiple priority queues, where each queue has a different priority level.

6. Huffman Coding: Heaps can be used in Huffman coding, an entropy encoding algorithm used for lossless data compression.

7. Memory Management: Heaps can be used in memory management, where the operating system uses a heap to manage dynamic memory allocation.

8. Event-Driven Simulations: Heaps can be used in event-driven simulations, where events are stored in a priority queue and processed in order of priority.

#### Advanced Data Structures

- Trees
- Binary Trees
<table>
  <tr>
    <td align="middle">
      InOrder Traversal
      <img src="https://github.com/bharatsesham/low-level-design-primer/blob/main/metadata/media/inOrder.gif" width="270" height="360"/>
    </td>
    <td align="middle">
      PreOrder Traversal
      <img src="https://github.com/bharatsesham/low-level-design-primer/blob/main/metadata/media/preOrder.gif" width="270" height="360"/>
    </td> 
    <td align="middle">
      PostOrder Traversal
      <img src="https://github.com/bharatsesham/low-level-design-primer/blob/main/metadata/media/postOrder.gif" width="270" height="360"/>
    </td> 
  </tr> 
</table>

- Binary Search Trees
- m-Array Trees
- B-Trees
- Binomial Heaps
- Fibonacci Heaps
- Red-Black Trees
- Graphs

## Design Patterns

> **Note: This section is under development**

## Under development

Interested in adding a new section or helping complete one in-progress? Feel free to [Contribute](#contributing)!

## Additional Resources

- [Grokking the Object Oriented Design Interview](https://github.com/tssovi/grokking-the-object-oriented-design-interview)
- [Big-O Cheat Sheet](https://www.bigocheatsheet.com/)

## Inspiration

Inspired from [System Design Primer](https://github.com/donnemartin/system-design-primer)
