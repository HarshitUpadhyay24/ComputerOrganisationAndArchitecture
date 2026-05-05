# Experiment 3

## Debugging C Programs using GDB (Pointers, Stacks, Queues, and Linked Lists)

---

## Objective

The objective of this experiment is to understand the use of the GNU Debugger (GDB) in debugging C programs. The focus is on analyzing and troubleshooting programs involving pointers, stacks, queues, and linked lists.

---

## Background Study

Debugging is an essential part of software development that involves identifying and fixing errors in a program. The GNU Debugger (GDB) is a powerful tool used to debug C programs by allowing step-by-step execution, inspection of variables, and analysis of memory.

Pointers are variables that store memory addresses and are widely used in dynamic data structures. Errors in pointer handling can lead to issues such as segmentation faults and memory leaks.

Data structures like stacks, queues, and linked lists rely heavily on pointers. A stack follows the Last In First Out (LIFO) principle, while a queue follows the First In First Out (FIFO) principle. Linked lists consist of nodes connected through pointers, allowing dynamic memory allocation.

GDB helps in understanding the behavior of such programs by enabling breakpoints, variable tracking, and memory examination.

---

## Experiment Description

In this experiment, C programs involving pointers, stacks, queues, and linked lists were written and debugged using GDB.

The programs were compiled with debugging symbols using the `-g` flag. GDB commands such as `break`, `run`, `next`, `step`, `print`, and `continue` were used to control execution and inspect program state.

For pointer-based programs, memory addresses and values were examined to ensure correct allocation and dereferencing.

In stack and queue implementations, operations such as push, pop, enqueue, and dequeue were monitored to verify correct data flow.

For linked lists, node creation, insertion, deletion, and traversal were debugged by inspecting pointer connections and memory locations.

---

## Observations

GDB allowed precise tracking of program execution and helped in identifying logical and runtime errors.

Pointer-related issues such as incorrect dereferencing and uninitialized pointers were easily detected.

In stack and queue implementations, GDB helped verify that elements were added and removed in the correct order.

For linked lists, it was useful in checking node links and detecting errors such as broken or incorrect pointer connections.

---

## Result

The C programs involving pointers, stacks, queues, and linked lists were successfully debugged using GDB. Errors were identified and corrected efficiently using debugging techniques.

---

## Conclusion

This experiment demonstrated the importance of debugging tools in software development. GDB proved to be highly effective in analyzing C programs, especially those involving pointers and dynamic data structures.

It provided deeper insight into memory management and program execution, improving understanding of complex concepts and helping in writing more reliable code.
