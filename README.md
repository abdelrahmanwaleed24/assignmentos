# assignmentos
##SHORTEST JOB FIRST
Shortest job first scheduling algorithm can also be known as shortest job next scheduling. It is very easy to implement and efficient in reducing average response time. Now we will see how it will work with the example and its implementation.

In shortest job first, we should know the execution time of each process before running. This we can estimate in many ways. This is the prerequisite for SJF.
Suppose we have set of processes are in ready queue. The SJF scheduling algorithm will choose the job which has shortest remaining time to complete. We have 2 variations of this SJF algorithm that are preemptive and non-preemptive. Preemptive version of SJF also known as SRTF
1-Sort all the processes according to the arrival time. 
2-Then select that process that has minimum arrival time and minimum Burst time. 
3-After completion of the process make a pool of processes that arrives afterward till the completion of the previous process and select that process among the pool which is having minimum Burst time. 

##ROUND ROBIN
The Round Robin Algorithm Working Process
The Round Robin scheduling algorithm executes the process within the time quantum if the burst time is less than or equal to the time quantum. When a process' burst time exceeds a time quantum, the process gets executed until it reaches the time quantum (TQ)
1-A ready queue gets established for all processes.
2-Each process' burst time gets compared to the CPU's time quantum.
3-The Round Robin scheduling algorithm executes the process within the time quantum if the burst time is less than or equal to the time quantum.
4-When a process' burst time exceeds a time quantum, the process gets executed until it reaches the time quantum (TQ).
5-The time quantum expires, and the process checks to see if it has finished.
6-As soon as the process is complete, it terminates. Otherwise, the process returns to the ready state.
