# OS Simulator

A C++ based Operating System Simulator that demonstrates and implements fundamental Operating System concepts.

## Features

- CPU Scheduling
- Deadlock Detection
- Disk Scheduling
- Dynamic Semaphore
- Memory Management
- Page Replacement

## Project Structure

    os/
    ├── CPU_TEST.cpp
    ├── CPU_TEST.h
    ├── deadlock_detection.cpp
    ├── deadlock_detection.h
    ├── disk_scheduling.cpp
    ├── disk_scheduling.h
    ├── dynamic_semaphore.cpp
    ├── dynamic_semaphore.h
    ├── memory_management.cpp
    ├── memory_management.h
    ├── page_replacement.cpp
    ├── page_replacement.h
    ├── main.cpp
    ├── README.md
    └── .gitignore

## Technologies Used

- C++
- Standard C++ Libraries
- Operating System Concepts

## Concepts Implemented

### CPU Scheduling

Implements CPU scheduling algorithms to demonstrate how processes are selected and executed by the CPU.

### Deadlock Detection

Simulates deadlock detection between processes and resources.

### Disk Scheduling

Implements disk scheduling algorithms to determine the order in which disk requests are serviced.

### Dynamic Semaphore

Demonstrates process synchronization and resource management using semaphores.

### Memory Management

Implements fundamental memory allocation and management concepts.

### Page Replacement

Simulates page replacement algorithms used in virtual memory management.

## How to Run

Clone the repository:

    git clone https://github.com/riteshkumar32/os-simulator.git

    cd os-simulator

Compile the project:

    g++ main.cpp CPU_TEST.cpp deadlock_detection.cpp disk_scheduling.cpp dynamic_semaphore.cpp memory_management.cpp page_replacement.cpp -o os_simulator

Run the program on Windows:

    os_simulator.exe

Run the program on Linux/macOS:

    ./os_simulator

## Purpose

This project provides practical implementations of fundamental Operating System concepts and demonstrates how different OS mechanisms work through simulation.

## Author

Ritesh Kumar

GitHub: https://github.com/riteshkumar32