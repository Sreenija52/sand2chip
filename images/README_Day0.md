# RISC-V based SOC Tapeout program VSD

## Day 0
### TASK 1
Summary: 

### TASK 2
### <ins>Ubuntu setup and Tools Installation</ins>

### **System Requirements**
- 6 GB RAM
- 50 GB HDD
- Ubuntu 20.04 or higher
- 4 vCPU

### Ubuntu Setup
```
Oracle virtual machine link:https://www.virtualbox.org/wiki/Downloads
Ubuntu LTS version download link:https://ubuntu.com/download/desktop
```

### Resizing the ubuntu window to full screen
```
$ sudo apt update 
$ sudo apt install -y build-essential linux-headers-$(uname -r)
$ cd /media/sreenija/VBox_GAs_6.1.30 #open Guest Addition folder terminal
$ ./autorun.sh
```

### Tool Check
#### <ins>**Yosys**</ins>
```
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make  #If make is not installed please install it
$ sudo apt-get install build-essential clang bison flex \
 libreadline-dev gawk tcl-dev libffi-dev git \
 graphviz xdot pkg-config python3 libboost-system-dev \
 libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make
$ sudo make install
```
![Alt text](images/yosys_img.png)


#### <ins>iverilog</ins>
```
$ sudo apt-get update
$ sudo apt-get install iverilog
```
![Alt text](images/iverilog_img.png)

#### <ins>gtkwave</ins>
```
$ sudo apt-get update
$ sudo apt install gtkwave
```
![Alt text](images/gtkwave_img.png)

![Alt text](images/gtkwave_gui.png)











