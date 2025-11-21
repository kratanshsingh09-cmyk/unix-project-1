# Process Analyzer 

This project is a Linux system process analyzer built using Bash scripting.
It provides three major functionalities:

## CPU-heavy processes list

Memory-heavy processes list

Live auto-refreshing process monitor

The tool is completely terminal-based and works on any Unix/Linux environment.

##  Features
### 1️⃣ CPU Usage Analyzer

Shows top CPU-consuming processes

User chooses how many entries to display (1–10)

Displays: PID, USER, CPU%, MEM%, COMMAND

Sorted in descending order of CPU usage

### 2️⃣ Memory Usage Analyzer

Shows top memory-consuming processes

Same format as CPU analyzer

Sorted in descending order of memory usage

### 3️⃣ Live Monitor (Auto-Refresh)

Real-time monitoring of:

Top CPU processes

Top Memory processes

System time

Uptime

Auto-refresh every 4 seconds

## Menu Options

1) Show CPU-heavy processes
2) Show Memory-heavy processes
3) Live Monitor (auto-refresh)
4) Quit

## Command Uses

### Command	Purpose
ps -eo	Show all processes in custom format
pid,user,pcpu,pmem,comm	Columns: ID, user, CPU%, memory%, command
--sort=-pcpu	Sort by highest CPU usage
--sort=-pmem	Sort by highest memory usage
head -n	Show only top N results
read -p	Prompt user input
clear	Clear the screen
sleep	Pause to slow output
trap	Handle Ctrl + C without crashing menu
Press Ctrl + C to exit back to main menu

<img width="721" height="245" alt="image" src="https://github.com/user-attachments/assets/de0f11d7-6019-4d85-9709-7b0d3b9cd96c" />
