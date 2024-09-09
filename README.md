Process Scheduler Project
This Java project implements a basic process scheduler with various scheduling algorithms. The system simulates the execution of processes with different priorities and resource requirements. The supported scheduling algorithms include First-Come, First-Serve (FCFS), Guaranteed-Burst-Time (GBG), Round Robin (RR), and a Mixed Scheduler.

Project Structure
Dispatcher.java: The main class orchestrating the process scheduling.
Process.java: Class representing a process with associated properties.
MemoryBlock.java, Printer.java, Scanner.java, Modem.java, CDDrive.java: Resource classes.
FCFS.java, GBG.java, RR.java: Classes implementing specific scheduling algorithms.
MixedScheduler.java: Class for dynamically selecting and executing scheduling algorithms.
