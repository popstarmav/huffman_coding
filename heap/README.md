# Huffman Coding Project

## Overview
This repository contains an implementation of Huffman coding, a lossless data compression algorithm. The project includes data structures and functions to build a min binary heap, which is used to construct the Huffman tree efficiently.

## Directory Structure
- **`huffman_coding/`**: Main directory for the Huffman coding project.
  - **`heap/`**: Contains heap-related files.
    - `heap.h`: Header file defining the heap and binary tree node structures.
    - `heap_create.c`: Implementation of the heap creation function.
  - `huffman.h`: Header file defining the symbol structure for Huffman coding.

## Files
1. **`heap/heap.h`**  
   Defines the `binary_tree_node_t` and `heap_t` structures, along with the prototype for the `heap_create` function.

2. **`heap/heap_create.c`**  
   Implements the `heap_create` function to initialize a min binary heap.

3. **`huffman.h`**  
   Defines the `symbol_t` structure to store characters and their frequencies.

## Compilation
To compile the project, use the following command from the `huffman_coding` directory:
```bash
gcc -Wall -Wextra -Werror -pedantic -Iheap/ -I./ heap/*.c <main_file>.c -o <output_name>
