# Assisgnment 6:Part 1: Understanding APT & System Updates (15 min) 
### Here is the code which i had perfermed to complete this task 

```
apt --version
```
```
sudo apt update
```
```
 sudo apt upgrade -y
 ```
 ```
 apt list --upgradable
 ```
 ```
  apt search image editor
```
```
 read zim
```
```
apt show "zim"
```
```
sudo apt install "zim" -y
```
```
 apt list --installed | grep "zim"
```
```
 sudo apt remove "zim" -y
```
```
 sudo apt purge "$zim" -y
```
```
sudo apt clean
```
```
 sudo add-apt-repository universe
```
```
 sudo apt update
```
```
sudo apt install fakepackage
```
```
read hold_package
```
```
 sudo apt-mark hold "zim"
```
```
sudo apt-mark unhold "zim"
```
------------
### So here are the pictures for the Assisgnment 
![alt text](<Screenshot 2025-03-04 204717.png>) ![alt text](<Screenshot 2025-03-04 204726.png>) ![alt text](<Screenshot 2025-03-04 204754.png>) ![alt text](<Screenshot 2025-03-04 204803.png>) ![alt text](<Screenshot 2025-03-04 204816.png>) ![alt text](<Screenshot 2025-03-04 204825.png>) ![alt text](<Screenshot 2025-03-04 204911.png>) ![alt text](<Screenshot 2025-03-04 204927.png>) ![alt text](<Screenshot 2025-03-04 204936.png>)





# Assignment 7: Linux Virtualization 
**Date:** 2025-02-19
**Author:** Aayush shrestha  (amk1006019@student.hamk.fi) 

## Part 1: Virtualization Concepts

Virtualization

The process of creating a virtual version of something, such as hardware, storage, or network resources.

Hypervisor

Software that creates and manages virtual machines (VMs). Examples include KVM, VMware, and Hyper-V.

Virtual Machines (VMs)

Emulations of physical computers that run their own operating systems.

Containers

Lightweight, isolated environments that share the host OS kernel but have their own file systems and libraries.

### **VMs vs Containers**

- The difference between VMs and Containers in terms of Architecture, Resource Utilization and Isolation

| **Aspect**    | **VMs**                                          | **Containers**    |
|----------------------|------------------------------------------------|------------------------------|
| **Architecture**     | Requires a full OS for each instance            | Shares the host OS kernel      |
| **Resource Utilization** | Requires more resources                        | More lightweight and efficient   |
| **Isolation**        | Provides strong isolation since each VM has its own OS | Provides a lower level of isolation, as it shares the host OS kernel |