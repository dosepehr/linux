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

hard extentions
vdi => oracle
vhd => microsoft
vmdk => vmware

q0)
terminal vs shell
q1)
virtual size & actual size
20GB - 2 MB

mounting

connecting a partion to a directory(mount point)

fhs(file hierchy system)
/boot => boot loader,grub
         linus kernel,vmlinuz

boot on / is only a pointer to /boot partion

/swap
when ram was full,it process on the hard
q2)

MIB vs mb

q3)
ls -l diffrence in ubuntu & centos
DAC vs MAC

less command  loads file data in RAM

q4) why we have many kernels in /boot

PATA
pararell ATA
for data transfer
master slave
noises
slow

SATA
faster that PATA

MBR
patitioning hards up to 2TB

q5) see first sector on linux

GPT
more volume than MBR
more partitions than MBR
content of first sector is stored in multiple places

q6) uefi vs bios


old hards (PATA) => hd
new hards (SATA) => sd
sda1 => partition 1 of hard 1
logical partitions => start from 5

sda1 => primary
sda2 => extended
sda5 => logical

/dev => every detected device 
