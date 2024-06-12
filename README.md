# datastructures
A collection of datastructures

## Linked List
A doubly-linked list. The same one as used in the Linux kernel

## String pool
A string pool to store strings and filter duplicates. It uses a
Red-Black tree to filter duplicates. Comparing strings is then as
easy as comparing u32's.

## Unique Queue
A circular queue that enforces each value to be unique. This could
be use as command queue, where a command may only be in the queue
once.

## Radix Tree
A Radix tree for very fast word-lookups. It uses data-oriented design
and can store/load the processed data extremely fast.

Pass a file (containing one word per line).
For example the English dictionary, can be found here:

https://github.com/dwyl/english-words

The radix_tree2 is the same, except that it also stores a value per
word (currently the index of the word)

