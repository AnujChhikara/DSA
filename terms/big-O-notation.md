# Time Complexities in Big-O Notation

## O(1) - Constant Time
- **Description**: Execution time is constant and does not change with input size.
- **Example**: Accessing an array element by index.

## O(log n) - Logarithmic Time
- **Description**: Execution time grows slowly as input size increases, typical for algorithms that divide the problem in half repeatedly.
- **Example**: Binary search.

## O(n) - Linear Time
- **Description**: Execution time grows directly in proportion to input size. Includes multiples of `n`, like `20n` or `30n`.
- **Example**: A loop through all elements in an array.

## O(n log n) - Linearithmic Time
- **Description**: Execution time grows at `n × log(n)`. Commonly found in efficient sorting algorithms.
- **Example**: Merge sort, quicksort (average case).

## O(n²) - Quadratic Time
- **Description**: Execution time grows with the square of input size. Common in algorithms with nested loops over the same data.
- **Example**: Basic bubble sort, selection sort, insertion sort.

## O(n³) - Cubic Time
- **Description**: Execution time grows with the cube of input size. Typically found in algorithms with three nested loops.
- **Example**: Some brute-force algorithms for finding combinations.

## O(2ⁿ) - Exponential Time
- **Description**: Execution time doubles with each additional input unit, growing very quickly. Common in algorithms that explore all possible combinations.
- **Example**: Recursive solutions to the Fibonacci sequence, the traveling salesman problem (brute-force).

## O(n!) - Factorial Time
- **Description**: Execution time grows at the factorial of the input size, which is extremely slow for large inputs. Often found in brute-force approaches to permutation and combination problems.
- **Example**: Generating all permutations of a set.
