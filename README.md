# Benchmarking Sorting Algorithms

This repository contains the benchmarking code for five different sorting algorithms as part of the assessment in the *Computational Thinking with Algorithms* module for the Higher Diploma in Data Analytics with Galway-Mayo Institute of Technology.


## About this Repository

The repository can be accessed [here](https://github.com/jennifer-ryan/benchmarking-sorting-algorithms). Clicking the 'clone or download' button will allow you to download the repository to your machine. Use the 'git clone' command followed by the repository link in your machine's command line to create a local copy for review. 

The contents of this repository are:

1. A README file that outlines the layout of the project.
2. A Jupyter Notebook that contains the sorting algorithm implementations and benchmarking code.
3. A PDF file containing descriptions of the sorting algorithms and their benchmark results.


## Project Specification

For this project you will write a Python application which will be used to benchmark five different sorting algorithms. You will also write a report which introduces the algorithms you have chosen and discusses the results of the benchmarking process.

The five sorting algorithms which you will implement, benchmark and discuss in this project must be chosen according to the following criteria:

1. A simple comparison-based sort (Bubble Sort, Selection Sort or Insertion Sort)
2. An efficient comparison-based sort (Merge Sort, Quicksort or Heap Sort)
3. A non-comparison sort (Counting Sort, Bucket Sort or Radix Sort)
4. Any other sorting algorithm of your choice
5. Any other sorting algorithm of your choice


## Project Description

This project implements functions for and benchmarks five sorting algorithms:

* Selection Sort
* Insertion Sort
* Merge Sort
* Quick Sort
* Counting Sort

The benchmarking process begins with the creation of arrays of random integer arrays of increasing size, each of which are passed to all of the sorting functions. The sorting functions are timed with each array ten times to get an average time for each input size and the results are collated in a dataframe. Please see PDF file for write-up. 

It should be noted that due to the nature of the simple sorting algorithms, the code herein may take quite some time to run as they attempt to sort the larger input sizes.
