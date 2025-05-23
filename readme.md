linux is a kernel
kernel responsibilities:
1) alocating RAM
2) alocating CPU schedule
3) letting apps to interact with each other,like openning PDF using browser
4) acts between hardware & app (image1)

kernel => linus torvalds
app => stallman

[image 2]
shell => app that we use it to command kernel using terminal



terminal vs shell
Terminal is a user interface that allows us to communicate with the operating system.

Shell is a command interpreter that executes the commands we type.

The shell runs inside the terminal.

mounting

connecting a partion to a directory(mount point)

fhs(file hierchy system)
/boot => boot loader,grub
         linus kernel,vmlinuz

boot on / is only a pointer to /boot partion

/swap
when ram was full,it process on the hard

MIB vs mb
MB is decimal
miB is binary

ls -l diffrence in ubuntu & centos
drwxr-xr-x. => ACL => SELinux
DAC vs MAC

less command  loads file data in RAM


*) seeing aa5 5validating check

MBR (master boot record)
patitioning hards up to 2TB

q5) see first sector on linux

GPT
more volume than MBR
more partitions than MBR
content of first sector is stored in multiple places

q6) uefi(GPT) vs bios(MBR)

old hards (PATA) => hd
new hards (SATA) => sd
sda1 => partition 1 of hard 1
logical partitions => start from 5

sda1 => primary
sda2 => extended
sda5 => logical
