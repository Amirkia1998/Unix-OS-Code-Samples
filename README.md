# Operating Systems Lab Code

Contains code examples from the Operating Systems course lab, specifically focusing on Shell Programming. This repository includes examples related to Shell Programming, Inter-Process Communication (IPC), and Process Management.

**Note: These code examples are part of the Shell Programming component for the Operating Systems lab. They are intended to be run on Unix-like operating systems and contain Unix-like system calls such as `fork()` and `exec()`.**

## IPC (Inter-Process Communication) Examples

The `ipc` folder contains code examples related to various IPC mechanisms in operating systems, including:

- **Pipes**: Demonstrates how to use pipes for communication between processes.
- **Client and Server**: Provides client-server communication examples.
- **Signals**: Illustrates signal handling between processes.
- **Message Queues (MQ)**: Examples of message queues, including "drop one" and "take one" operations.
- **Shared Memory (SHM)**: Demonstrates shared memory usage between client and server.
- **Semaphores**: Shows how to use semaphores for synchronization.

## Process Management Examples

The `processes` folder contains code examples related to process management, including:

- **Fork**: Examples of the `fork()` system call for creating child processes.
- **Exec**: Demonstrates the `execl()` and `execvp()` functions for executing programs.
- **Atexit**: Shows how to register functions to be called at program termination.
- **Shell**: Provides a simple shell implementation, allowing for command execution.
- **Zombies**: Explains the concept of zombie processes and how to avoid them.
- **Wait**: Demonstrates the use of `wait()` and `waitpid()` for process synchronization.

## Getting Started

1. Clone this repository to your local machine:

   ```shell
   git clone https://github.com/your-username/operating-systems-lab.git

2. Navigate to the specific folder (e.g., ipc or processes) containing the code examples you want to explore.
3. Compile and run the C code examples using your preferred compiler (e.g., gcc).
4. Explore the code to understand how different IPC and process management concepts are implemented.

## Acknowledgments
I would like to acknowledge the **Yildiz Technical University** for providing the Operating Systems course and the opportunity to work on these lab exercises.

