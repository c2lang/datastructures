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

