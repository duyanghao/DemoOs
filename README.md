DemoOs
=================

Demo OS for multi tasks

## Target
This demo OS is designed for understanding the principle of operating system.It includes the base application of GDT,LDT,IDT,BIOS,REAL MODE,PROTECTED MODE,USER MODE,KERNEL MODE,SYSTEM CALL and INTERRUPT.

## Introduction
There are two tasks,one is A(task0),displaying the character A,Another is B(task1),displaying the character B.And there will be a time-interrupt every 10ms,the OS will switch task when time-interrupt happens.

## Building
#### Required
Linux 0.12 kernel required!
```
make
make disk

```
## Display
![](https://raw.githubusercontent.com/duyanghao/DemoOs/master/images/display.png)


