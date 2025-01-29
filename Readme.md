This repository contains sample code for the fd io introduction lab.

The primary learning objectives for this lab are developing comptency with
* POSIX syscalls related to file access, as exposed in python
* development and execution of python programs in a POSIX command line environment.

In the repository are two plain text files with lots of words. Your
assignment is to create a python 3 program which:
* takes as input the name of an input file and output file
* example

`$ python wordCount.py input.txt output.txt`
* keeps track of the total the number of times each word occurs in the text file 
* excluding white space and punctuation
* is case-insensitive
* print out to the output file (overwriting if it exists) the list of
  words sorted in descending order with their respective totals
  separated by a space, one word per line

We encourage you to utilize the re regular expression library and python dictionaries in your program.
