# CPU Scheduling Simulator

A CPU scheduling simulator implemented in C with dynamic memory allocation. The program compares four scheduling algorithms: FCFS, SJF, SRTF, and Round Robin.

## Features

- First Come First Serve (FCFS)
- Shortest Job First (SJF)  
- Shortest Remaining Time First (SRTF)
- Round Robin with configurable time quantum
- Dynamic memory allocation
- Gantt chart generation
- Performance comparison with turnaround and waiting times


## Usage

1. Run the program
2. Enter arrival time and burst time for each process
3. Choose whether to add more processes (1 for yes, 0 for no)
4. View the results comparing all four algorithms

## Input Format

For each process:
- Arrival time (non-negative integer)
- Burst time (positive integer)

## Output

The program displays:
- Gantt charts for each algorithm
- Average turnaround time and waiting time
- Best performing algorithm based on lowest turnaround time

## Example

```
Process 0:
   Enter arrival time (≥0): 0
   Enter burst time (>0): 5
   Add another process? (1=Yes, 0=No): 1

Process 1:
   Enter arrival time (≥0): 2
   Enter burst time (>0): 3
   Add another process? (1=Yes, 0=No): 0
```

## Memory Management

The program uses dynamic memory allocation with automatic array resizing and complete memory cleanup to prevent memory leaks.
