# Assignment 2 - Data Structures

Design and Analysis of Algorithms

Student: Zhumabay Aikyn  
Group: SE-2523  
Instructor: Taubakabyl Nurlybek

## Project Description

This project implements three data structures from scratch:

- DynamicArray
- MyLinkedList
- MinHeap

All structures store primitive int values.

The project also includes operation counters, JUnit 5 tests, benchmarks, CSV results and plots.

## Implemented Operations

### DynamicArray

- add(x)
- add(index, x)
- remove(index)
- get(index)
- contains(x)

### MyLinkedList

- add(x)
- add(index, x)
- remove(index)
- get(index)
- contains(x)

### MinHeap

- insert(x)
- peekMin()
- extractMin()
- buildHeap(int[] array)

## Metrics

The program counts:

- steps
- moves
- comparisons

## Benchmark

The benchmark uses these sizes:

- 100
- 1000
- 10000
- 100000

Random data is generated with:

new Random(42)

The benchmark contains:

- W1 - Random Access
- W2 - Search
- W3 - Insert and Remove
- W4 - Priority Processing

Each case has one warm-up run and five measured runs.

The median time is saved to:

results/results.csv

## Bonus Task B

The project includes Floyd's buildHeap algorithm.

It compares:

- separate insert operations
- buildHeap

The comparison uses execution time and number of comparisons.

## Tests

JUnit 5 tests check:

- normal operations
- empty structures
- invalid indexes
- duplicate values
- first and last indexes
- heap property
- sorted heap output

Run tests with:

mvn test

## Run Benchmark

Run:

benchmark.Benchmark

The results are saved to:

results/results.csv

## Plots

Charts are created in Excel using results.csv.

PNG files are saved in:

results/plots/

## Project Structure

src/main/java/structures  
src/main/java/metrics  
src/main/java/benchmark  
src/test/java/structures  
results/results.csv  
results/plots/  
README.md  
REPORT.md
