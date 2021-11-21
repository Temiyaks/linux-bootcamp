# linux-bootcamp
Linux Cloud Engineer Bootcamp
 
 LAB 1
 
 With Microsoft Azure, I was able to launch my cloud shell
 
 After launching my cloud shell, I was abale to create a resource group
 
 I created  and connected to a Virtual Manchine
 
I was able to  installed  nginx  on my  VM

LAB 2

I created a virttual images which is used to deployed my second virtual manchine.

The code "az vm image list --output table" returns the most popular images on azure which conatins the offer, publisher, sku and urn.

The one i ran on my microsoft azure is openlogic: centos-HPPC: 7.7: latest.

At the end, I was able to deployed  centos-HPPC: 7.7 to virtual manchine.


VM SIZE

VM size is the memeory available  in the azure.

I was able to see the list of sizes availabel on my azure using the az vm list-sizes. It listed lots of sizes

I created a VM usiung the size(Standard_Dsl).

A size can be resized to increase or decrease resource allocation.

NOTE: Before reziing, It is important to check if the size is available on azure. When trying it, the SIZE(Standard_Dsl_V2)  was not availabLE. I had to DEALLOCATE using the command line az vm deallocate.

Once deallocation is done, We can now  resize and start.

REASONS OF RESIZING

1. To increased the resource allocation
2. To decrease the resource allocation

POWER STATE

This basically means the current state of the virtual manchine

It is listed below:
- Starting
- Running
- Stopping
-Stopped
-Deallocating
- Deallocated
-  - i.e It is unknown

MANAGEMENT TASKS

In management task we can run many commands like start, stop and delete.

To delete resource group we used the command line az group delete -- name <state the name of the resource group.



LAB 3

AZURE DISKS MANAGEMENT WITH AZURE CLI

INTRODUCTION

Azure virtual machines (VMs) use disks to store the operating system, applications, and data.

I learnt that when a azure virtual manchine is created, two disks is automatically attched to it .

- Operating system disks

- Temporary disks













