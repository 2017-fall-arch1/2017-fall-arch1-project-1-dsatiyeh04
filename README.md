# arch1-linked-list-demo

This directory contains:
* code that uses a Binary Search Tree to store Employee names 
* a demo program that uses it

The demo program reads a text file, and creates nodes with the employees names
then it creates a BST where you can add new names,
delete names, and output a text file with current employees.

This demo contains the following files:
 BSTDemo.c  Where it creates the file and read it and ask for user input
 BSTree.c Where it creates the nodes and the tree with the employee information
 BSTree.h where all the methods are stored
 Makefile to connect all of the c files together
 names.txt where all the intital employee names are stored
 

To compile:
~~~
$ make
~~~

To test it, try:
~~~
$ make ./BSTDemo
~~~

To delete binaries:
~~~
$ make clean
~~~
c