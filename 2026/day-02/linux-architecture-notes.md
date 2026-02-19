The core components of Linux (kernel, user space, init/systemd)

The kernel is the heart of the Linux operating system.

What it does:

Manages CPU and memory,Controls hardware devices,Handles file systems,Manages processes,Provides security and permissions

When you run a command, it doesn’t directly talk to hardware — it talks to the kernel, and the kernel handles everything.

User space is where:

Applications run (like vim, nginx, mysql),Shells run (bash, zsh), User programs execute

User space programs:Cannot access hardware directly,Must request services from the kernel using system calls
Example:
When you open a file using cat file.txt, the program requests the kernel to read the file.

Init System (systemd)

The init system is the first process started by the kernel.
