# Practice: Managing Files and Directory Permission

## Practice Exercise 1: Create Partition and Mounting
​
As a system admin of Phoenix Corp., you have been asked to add two separate partitions of 1GB each for the  sales and finance department. ​

Create two partitions of 1GB each and make them logical partitions.​

Assign filesystem EXT4 to both.​

Create two directories with the name of /home/sales and /finance.​

Mount both partitions on /home/sales and /home/finance directory, respectively.​

Note : please use the virtual box VM "Ubuntu-02" present in VLAB for this exercise.
## Practice Exercise 2: Set Advance Linux Permission​ using sticky-bit

At Phoenix Corp., both David and Richard are members of the sales group. Both members have the read, write and execute permissions on the /home/david/data directory.​

​

This creates a situation where both users can modify each others’ data. This needs to be fixed.​

​

You have been asked to setup permissions so that only the owner of the files can make modifications.​

Tasks:

Create a group with the name “sales”.​

Add two users, "David" and "Richard" to this group​

Create a directory named "data" in the /home/david directory.​

Make "sales" the group owner of the  /home/david/data directory.​

Provide read, write, and execute permissions to sales group.​

Enable Sticky bit on the folder to prevent the issue.​

​
​
## Practice Exercise 3: SetGID**​

At Phoenix Corp, Andrew works in the sales department. As a system admin, you have been asked to create a sales directory for this department. ​

​

You have provided group ownership of the sales directory to the sales department group. As part of this, the group owner has the read, write, and execute permissions on the directory. However, when Andrew creates a new file, the group ownership changes to Andrew. ​

You, as the system admin need to set it up so that group owner will be the sales department group.​

Tasks:

Create a user with the name Andrew.​

Create the sales directory in /home directory.​

Create a group with the name “sales”.​

Provide read, write, and execute permission over the directory /home/sales to the sales group.​

Enable the SGID bit over the directory.​

​

​
