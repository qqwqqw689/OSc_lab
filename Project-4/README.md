# Project 4: Scheduling Algorithms

Scheduling Algorithms. (Operating System Concepts, 10th Edition, Chapter 5)

## Description

This project involves implementing several different process scheduling algorithms, including FCFS, SJF, Priority, RR and Priority with RR.

## Environment

- OS: Ubuntu 22.04
- Compiler: GCC 11.3.0

## Basic Ideas

With the provided code framework, simply implement each algorithm according to its definition.

Completing this project will require writing the following C files:

schedule_fcfs.c
schedule_sjf.c
schedule_rr.c
schedule_priority.c
schedule_priority_rr.c

The supporting files invoke the appropriate scheduling algorithm. 

For example, to build the FCFS scheduler, enter

make fcfs

which builds the fcfs executable file.

./fcfs example_tasks.txt

which execute the scheduler.

And the screenshot:

![screenshot](./screenshot.png)

