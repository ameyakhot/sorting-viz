# Sorting Visualizer

A web-based sorting algorithm visualizer that allows you to see how various sorting algorithms work in real-time.

![Sorting Visualizer Screenshot](screenshot.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Usage](#usage)
- [Algorithms](#algorithms)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Sorting Visualizer project is designed to help you understand how different sorting algorithms function by visualizing their operations on an array of bars. This interactive web application lets you experiment with sorting algorithms and see the sorting process step by step.

## Features

- Visualize various sorting algorithms, including Bubble Sort, Merge Sort, Quick Sort, Insertion Sort, Selection Sort, and Heap Sort.
- Adjustable array size and sorting speed.
- Randomize the array for different input data.
- Step-by-step visualization of sorting operations.
- Pause and stop sorting at any time.

## Usage

1. **Array Size**: Use the slider to adjust the size of the array to be sorted.

2. **Sorting Speed**: Choose from "Slow," "Medium," or "Fast" to set the sorting speed.

3. **Algorithm Selection**: Select a sorting algorithm from the dropdown menu.

4. **Randomize Array**: Click the "Randomize Array" button to generate a new random array.

5. **Sort**: Click the "Sort" button to start sorting. You can pause or stop the sorting process at any time by clicking the "Stop" button that appears during sorting.

6. **Visualizer**: Observe the bars in the visualization container change colors to represent the sorting process.

## Algorithms

This project includes the following sorting algorithms:

- **Bubble Sort**: Simple comparison-based sorting that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order.

- **Merge Sort**: A divide-and-conquer algorithm that divides the unsorted list into `n` sub-lists, each containing one element, and then repeatedly merges sub-lists to produce new sorted sub-lists.

- **Quick Sort**: A divide-and-conquer algorithm that works by selecting a 'pivot' element from the array and partitioning the other elements into two sub-arrays, according to whether they are less than or greater than the pivot.

- **Insertion Sort**: Builds the final sorted array one item at a time by repeatedly taking the next item and 'inserting' it into its correct position within the already-sorted part of the array.

- **Selection Sort**: Divides the input list into two parts: the sublist of items already sorted and the sublist of items remaining to be sorted. It repeatedly selects the minimum element from the unsorted sublist and moves it to the end of the sorted sublist.

- **Heap Sort**: A comparison-based sorting algorithm that divides the input into a sorted and an unsorted region, and iteratively shrinks the unsorted region by extracting the largest element and moving it to the sorted region.

## Contributing

Contributions to this project are welcome! If you'd like to contribute, please follow the [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
