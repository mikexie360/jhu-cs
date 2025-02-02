response time is also called execution time.
    The total time required for the computer to complete a task, including disk access, memory access, I/O activities, operating system overhead, CPU execution time, and so on.

thoughput also called bandwidth
    number of tasks completed per unit of time.

Performance = 1/Execution Time

The lower the execution time, the more performance.

X is n times as fast as Y means

PerformanceX/PerformanceY = n
or
ExecutionY/ExecutionX = n

CPU execution time. The actual time the CPU spends computing for a specific task.

user CPU time. The CPU time spent in a program itself

system CPU time. The CPU time spent in the operating system performing tasks on behalf of the program.

clock cycle, the time for one clock period
clock period, the length of each clock cycle.

CPU execution time for a program = CPU clock cycles for a program * clock cycle time
CPU execution time for a program = CPU clock cycles for a program / clock rate
CPU time = CPU clock cycles * clock cycle time

CPU clock cycles = Instructions for a program * Average Clock cycles per instruction

CPU times = Instruction count * CPI * clock cycle time
CPU times = (Insturction count * CPI) / Clock rate

time = seconds/program = (Instructions/program) * (clock cycles/Instructions) * (seconds/clock cycle)

Execution time after improvement = (execution time affected by improvement / amount of improvement) + execution time unaffected


