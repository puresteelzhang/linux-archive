#
# Makefile for the linux kernel.
#

extra-y := vmlinux.lds.s

obj-y := process.o traps.o ptrace.o ints.o \
	 sys_h8300.o time.o semaphore.o signal.o \
         setup.o gpio.o init_task.o syscalls.o

obj-$(CONFIG_MODULES) += module.o h8300_ksyms.o 
