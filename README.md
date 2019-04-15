# dynamic-priority-preemptive-scheduling
Description: The problem is to calculate the waiting time of the process and then calculate the average wait time of the process and the type of scheduling to be used is ‘preemptive priority scheduling’ and in this problem priority increases automatically for each process.For process waiting priority increases by 2 for each time quanta which is given as 1 and for the process executing priority increases by 1.and the process having highest number of priority has the highest priority.

Algorithm:
process p1[n];
queue(p1);
//operations on p1 suxch as decrement burst time.
Increment priority
Increment waiting time of the processes waiting in the queue.
Check for the burst time of the process if completed or not
If completed
Store in the result 
Else sort the array of process according to the priority.
Then again repeat the steps till burst time of all the processes becomes zero.
Then from result get the information needed.
3)	Calculate complexity of implemented algorithm.
Description: O(n^3).
4)	Explain all the constraints given in the problem. Attach the code snippet of the implemented constraint. 
Code snippet: 
Sorting according to arrival time.
Sorting according to priority.
Priority increment while executing.
Priority increment while waiting.
5)	If you have implemented any additional algorithm to support the solution, explain the need and usage of the same.
Description: Sorting.
6)	 Explain the boundary conditions of the implemented code. 
Description: Arrival time should be positive.
		   Burst time should be positive.
7)	 Explain all the test cases applied on the solution of assigned problem.
Description: 
Process	Arrival time	Burst time
P1		0		4
P2		1		1
P3		2		2
P4		3		1
