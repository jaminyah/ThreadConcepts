# Multithreading Concepts

This document contains a general overview of multithreading concepts that are important to application level software developers. Although the
primary motivation is to discuss concurrency using threads, a light examination of concurrency using processes is also conducted.  

## Table of Contents

    1. Process
    1.1 - Structure of a process
    1.2 - Concurrency using processes

    2. Threads
    2.1 - Concurrency using threads
    2.2 - Thread Structure
    2.3 - Synchronization
    2.3.1 - Synchronization Models
    2.3.2 - Mutex Lock
    2.3.3 - Read/Write Lock
    2.3.4 - Condition Variable
    2.3.5 - Semaphores
    2.3.5.1 - Counting Semaphores
    2.3.5.2 - Binary Semaphores
    2.3.6 - Barriers
    2.3.6 - Spinlock

3. PThreads

4. Objective Threads

5. Swift Threads

6. C++ Threads

7. Java Threads

8. Go Threads

## 1. Process
A process is a program that is loaded and running in memory.

### 1.1 Structure of a Process
* File handles
* Registers
* Program Counter (PC) - Is a register that contains the memory address of the next instruction that is to be executed.
* Process ID
* Process Group
* Stack
* Data Segments
* Heap
* Process State - waiting, ready, running, stopped. 

### 1.2 Concurrency using Process
Each process is allocated one thread by default.



## 2. Thread

A thread is a sequeunce of instructions within a process. These instructions can be executed independently by the operating system scheduler.

### 2.1 Concurrency using Threads


## 3. PThreads

### Compiling with PThreads

```bash:
clang -g -lpthread main.c -o main
```