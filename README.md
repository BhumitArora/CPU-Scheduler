<img src="https://img.shields.io/badge/Operating%20Systems-CPU%20Scheduling%20Algorithm-<green>"> <img src="https://img.shields.io/static/v1?label=Language&message=CPP&color=blue">
<br>

Implemented the following CPU scheduling algorithms in C++ with arrival time considerations: <br>
<br>

* First Come First Served (FCFS) <br>
* Shortest Job First (SJF) <br>
* Round Robin (RR) <br>
* Shortest Job Remaining First (SJRF) <br>
<br>
Key features of the implementation include: <br>

* Incorporation of Arrival Time <br>
* Random generation of process data <br>
* Tabular representation of individual process metrics such as Turnaround Time and Waiting Time <br>
* Calculation of Average Turnaround Time and Average Waiting Time <br>
<br>

## First Come First Served (FCFS) <br>

In this non-preemptive scheduling algorithm, processes are executed in the order they arrive. The process with the earliest arrival time is given priority and executed first.<br>
<br>

## Shortest Job First (SJF) <br>

This non-preemptive algorithm prioritizes processes based on their burst time, which indicates the CPU time required for execution. Processes are sorted by arrival time and then enqueued. The process with the shortest burst time is executed next.<br>
<br>

## Round Robin (RR) <br>

This preemptive algorithm ensures minimal process starvation by executing processes in a round-robin fashion with a specified time quantum. After a process is executed for the given time quantum, it is preempted and the next process is executed.<br>
<br>

## Shortest Job Remaining First (SJRF) <br>

This preemptive variant of SJF prioritizes processes based on remaining burst time. If a new process arrives with a burst time shorter than the current executing process, the CPU preempts the current process and switches to the new one.<br>

Working Snapshots <br>

<br>
<img src="working snaps/img1.JPG" alt="Working Snapshot 1">
<br>
<img src="working snaps/img2.JPG" alt="Working Snapshot 2">
<br>
<img src="working snaps/img3.JPG" alt="Working Snapshot 3">
<br>
