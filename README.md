Operating System: From 0 to 1
=============================

This book helps you gaining the foundation knowledge to write an operating system from scratch. Hence the title, 0 to 1. 

After completing this book, at the very least:

- How to write an operating system from scratch by reading hardware datasheets. In the real world, it works like that. You won't be able to consult Google for a quick answer. 

- Write code independently. It's pointless to copy and paste code. Real learning happens when you solve problems on your own. Some examples are given to kick start, but most problems are yours to conquer. However, the solutions are available online for you to examine after giving a good try.

- A big picture of how each layer of a computer related to each other, from hardware to software.

- Linux as a development environment and how to use common tools for low-level programming.

- Understand x86 assembly in-depth.

- How a program is structured so that an operating system can run.

- How to debug a program running directly on hardware with gdb and QEMU.

- Linking and loading on bare metal x86_64, with pure C. No standard library. No runtime overhead.

[Download the book](github.com/tuhdo/os01/zipball/master)

# Status:
* Part 1
   - Chapter 1: Complete
   - Chapter 2: Complete
   - Chapter 3: Almost. Currently the book relies on the Intel Manual for fully explaining x86 execution environment.
   - Chapter 4: Complete
   - Chapter 5: Complete
   - Chapter 6: Complete
* Part 2
   - Chapter 7: Complete
   - Chapter 8: Complete
* Part 3
   - Chapter 9: Incomplete
   - Chapter 10: Incomplete
   - Chapter 11: Incomplete
   - Chapter 12: Incomplete
   - Chapter 13: Incomplete

# Sample OS
[This repository](https://github.com/tuhdo/sample-os) is the sample OS of the book that is intended as a reference material for part 3. It covers 10 chapters of the "System Programming Guide" (Intel Manual Volume 3), along with a simple keyboard and video driver for input and output. However, at the moment, only the following features are implmeneted:

- Protected mode.
- Creating and managing processes with TSS (Task State Structure).
- Interrupts
- LAPIC.

Paging and I/O are not yet implemented. I will try to implement it as the book progresses.