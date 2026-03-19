# File-merger-cpp
C++ project for file merging
 File Merge Utility

Description:
This C++ program merges two text files containing sorted words into a single output file while preserving lexicographical order. It reads words from the input files, compares them, and writes the merged result to a new file.

Features:

Merges two input files into one sorted output file.

Handles files of different lengths.

Preserves the original lexicographical order of words.

Handles empty files gracefully.

Simple and lightweight, implemented in standard C++ without external libraries.

Usage:

Prepare two input text files (e.g., text1.txt and text2.txt) with words separated by spaces.

Compile the program:



The merged output will be saved in output.txt (created in the program’s working directory).

Example:

Input text1.txt: apple banana cherry


Input text2.txt: avocado berry date


Output output.txt:  apple avocado banana berry cherry date

Notes:

Currently, the program uses lexicographical order for sorting words.

To merge numerical words in numeric order (e.g., "one", "two", "three"), additional logic is required.
