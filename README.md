# Intelligent-CPU-Scheduler-Simulator

<!-- output of FCFS -->
PID     Arrival Burst   Completion      Turnaround Waiting
1       0       5       5               5 0
2       1       3       8               7 4
3       2       8       16              146

<!-- SJF output -->
Enter number of processes: 4
Enter Burst Time for each process:
P1: 2
P2: 3
P3: 6
P4: 21

Process Burst Time      Waiting Time    Turnaround Time
P1      2               0               2  
P2      3               2               5
P3      6               5               11 
P4      21              11              32 

Average Waiting Time: 4.5
Average Turnaround Time: 12.5


<!-- Priority Scheduling (Non-Preemptive) in C++ -->
Enter number of processes: 4
Enter Burst Time and Priority for each process:
P1 Burst Time: 6
P1 Priority: 3
P2 Burst Time: 2
P2 Priority: 2
P3 Burst Time: 14
P3 Priority: 1
P4 Burst Time: 6
P4 Priority: 4
A
Process Burst Time      Priority      Waiting Time     Turnaround Time        
P3      14              1             14
6               22
P4      6               4             22               28

Average Waiting Time: 13
Average Turnaround Time: 20
<!-- Output of Round Robin -->
Enter number of processes: 3
Enter time quantum: 2
Enter Burst Time for P1: 10
Enter Burst Time for P2: 5
Enter Burst Time for P3: 8

P2      5               10            15
P3      8               13            21

Average Waiting Time: 12
Average Turnaround Time: 19.6667
