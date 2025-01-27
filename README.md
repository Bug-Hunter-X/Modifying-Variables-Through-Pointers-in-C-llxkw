# Modifying Variables Through Pointers in C
This repository demonstrates a common C programming error related to modifying variables through pointers. The primary file, `bug.c`, contains code that modifies a variable indirectly through a pointer.  The solution, in `bugSolution.c`, illustrates a correct and safer approach.  This simple example helps highlight a potential source of subtle bugs in C programs.

**Understanding the Problem**
Directly modifying variables using pointers is powerful but can be error-prone if not done correctly.  It's crucial to understand the implications and manage pointer usage effectively. The example code shows how even a small oversight in pointer manipulation can lead to unexpected results, especially in larger, more complex programs.