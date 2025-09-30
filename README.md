# Algorithm-Analysis-using-Big-O-Notation-

## Aim
To study and analyze the time complexity of various algorithms using Big O notation, understanding how to evaluate algorithm efficiency and performance characteristics for different input sizes.

## Software Used
- **Compiler**: GNU GCC (g++)
- **IDE**: Visual Studio Code
- **Operating System**: Windows/Linux

## Theory
Big O notation is a mathematical notation used to describe the limiting behavior of a function when the argument tends towards a particular value or infinity. In computer science, it's used to classify algorithms according to how their running time or space requirements grow as the input size grows.

### Common Time Complexities:
- **O(1)**: Constant time - operations execute in fixed time
- **O(log n)**: Logarithmic time - operations reduce problem size significantly each step
- **O(n)**: Linear time - operations grow proportionally with input size
- **O(n log n)**: Linearithmic time - common in efficient sorting algorithms
- **O(n²)**: Quadratic time - common in nested loops
- **O(2ⁿ)**: Exponential time - operations double with each additional input element

### Key Principles:
- **Worst-case analysis**: Considers the maximum time an algorithm can take
- **Asymptotic behavior**: Focuses on growth rate as input size approaches infinity
- **Dominant terms**: Only the fastest-growing term is considered
- **Constant factors**: Ignored in Big O notation

## Algorithms and Their Complexity Analysis

### 1. Constant Time Operations - O(1)

**Algorithm:**
1. **Start** the program
2. **Define** operations that execute in fixed time:
   - Array access by index
   - Arithmetic operations
   - Variable assignments
3. **Execute** operations regardless of input size
4. **End** the program

**Characteristics:**
- Execution time doesn't depend on input size
- Most efficient complexity class
- Examples: accessing array elements, basic arithmetic

### 2. Linear Time Algorithms - O(n)

**Algorithm:**
1. **Start** the program
2. **Initialize** array of size n
3. **Iterate** through each element once:
   - Perform constant-time operation on each element
4. **Complete** after processing all n elements
5. **End** the program

**Characteristics:**
- Execution time grows linearly with input size
- Single loop through input data
- Examples: linear search, finding maximum element

### 3. Quadratic Time Algorithms - O(n²)

**Algorithm:**
1. **Start** the program
2. **Initialize** array of size n
3. **Nested iteration**:
   - Outer loop runs n times
   - Inner loop runs n times for each outer iteration
   - Perform constant-time operations in inner loop
4. **Complete** after n × n iterations
5. **End** the program

**Characteristics:**
- Execution time grows with square of input size
- Common in algorithms with nested loops
- Examples: bubble sort, selection sort

### 4. Logarithmic Time Algorithms - O(log n)

**Algorithm:**
1. **Start** the program
2. **Initialize** sorted array of size n
3. **Divide and conquer approach**:
   - Repeatedly divide problem size by constant factor
   - Discard one portion of input at each step
   - Perform constant-time operations per step
4. **Complete** when problem size reduces to 1
5. **End** the program

**Characteristics:**
- Execution time grows logarithmically with input size
- Problem size reduces significantly each iteration
- Examples: binary search, certain tree operations

### 5. Linearithmic Time Algorithms - O(n log n)

**Algorithm:**
1. **Start** the program
2. **Initialize** array of size n
3. **Divide input** into smaller parts (log n divisions)
4. **Process each part** with linear operations
5. **Combine results** from all parts
6. **End** the program

**Characteristics:**
- Common in efficient sorting algorithms
- Combines linear and logarithmic behaviors
- Examples: merge sort, heap sort, quick sort (average case)

## Analysis Methodology

### Step-by-Step Complexity Analysis:
1. **Identify basic operations** that constitute the algorithm
2. **Count operations** in terms of input size n
3. **Determine growth rate** as n approaches infinity
4. **Ignore constant factors** and lower-order terms
5. **Express result** using Big O notation

### Common Patterns:
- **Single loop**: O(n)
- **Nested loops**: O(n²) or O(n × m)
- **Divide by constant**: O(log n)
- **Recursive halving**: O(n log n)
- **Exponential growth**: O(2ⁿ) or O(cⁿ)

## Key Learning Points

- **Efficiency Comparison**: Understanding relative performance of different complexity classes
- **Scalability Prediction**: How algorithms will perform with larger datasets
- **Algorithm Selection**: Choosing appropriate algorithms based on problem constraints
- **Performance Optimization**: Identifying and improving bottleneck operations
- **Practical Implications**: Real-world consequences of algorithmic choices

## Conclusion

This experiment provided comprehensive understanding of algorithm analysis using Big O notation:

1. **Complexity Classification**: Learned to categorize algorithms based on their growth characteristics
2. **Performance Prediction**: Gained ability to estimate how algorithms scale with input size
3. **Algorithm Selection**: Developed skills to choose appropriate algorithms for specific problems
4. **Efficiency Awareness**: Understood the practical implications of different time complexities

Big O notation serves as a fundamental tool for computer scientists and programmers to analyze, compare, and select algorithms based on their efficiency characteristics. This knowledge is crucial for designing scalable systems and writing optimized code that can handle real-world data sizes effectively.
