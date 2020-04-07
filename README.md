DemoOs
======

Demo OS for multi tasks

## Target

This demo OS is designed to understand the principle of operating system. It contains almost all basic concepts of linux kernel, such as `GDT`, `LDT`, `IDT`, `BIOS`, `REAL MODE`, `PROTECTED MODE`, `USER MODE`, `KERNEL MODE`, `SYSTEM CALL`, `INTERRUPT` and so on.

## Detail

There are two tasks, one is `A`(task0), which displays the character `A`, while the another is `B`(task1), which displays the character `B`. There will be a time-interrupt every 10ms, and the OS will switch these two tasks when time-interrupt happens.

## Building

```bash
$ make
$ make disk
```

## Display

![](https://raw.githubusercontent.com/duyanghao/DemoOs/master/images/display.png)


