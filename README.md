# My solution for MIT [6.828](https://pdos.csail.mit.edu/6.828/2014)

A Unix-like operating system.

## Lab1
* Bootloader and kdebug. Debugging with QEMU and gdb.

## Lab2
* Memory management:
 * The first component is a physical memory allocator for the kernel, so that the kernel can allocate memory and later free it.

 * The second component of memory management is virtual memory, which maps the virtual addresses used by kernel and user software to addresses in physical memory.

## Lab3
* This lab implements the basic kernel facilities required to get a protected user-mode environment (i.e., "process") running.
