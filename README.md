# AZURE--TASK-2

Step 0: Log in to the Azure Portal (https://portal.azure.com/).

Task 1 :
--> Create a private and public subnets in the above Vnet

Steps are given below:

Step 1: Log in to the Azure Portal and navigate to the virtual network you want to create the subnets in.

Step 2: Select "Subnets" under the "Settings" section.

Step 3: Click the "+Add" button to create a new subnet.

Step 4: In the "Name" field, enter a name for the subnet (e.g. "PrivateSubnet")

Step 5: In the "Address range" field, enter the range of IP addresses for the subnet (e.g. 10.0.1.0/24).

Step 6: Select the virtual network from the "Virtual network" drop-down menu

Step 7: Select the "No" for "Assign public IP address" for the private subnet

Step 8: Repeat the above steps for creating Public subnet, but select "yes" for "Assign public IP address"




Task 2:



--> Create a Virtual Network [VM] and attach multiple NIC with it.

Steps are given below:

Step 1: Navigate to Virtual Machines in menu bar [Located in top left corner of home] (or) you can search Virtual machines in Search bar.

Step 2: Select Azure Virtual Machine.

Step 3: Enter the following details:

      -> Resource Group: you can create a new one or select the existing one.   [ your choice ]
      -> Virtual Machine name
      -> Region
      -> Image
      -> Size
      -> In administrator account : enter Username, password and Confirm Password.
Step 4: fill the required information for each NIC such has , name,  IP address and VN(virtual networks)

Step 5:  check the above informaton correctly.

Step 6: Click on "REVIEW + CREATE".

Step 7: once reviewed, click on "CREATE" to create the Virtual Machine.

Step 8: Once deployment is complete, you can click on go to resource to view the Virtual Machine.

Thus NICs have been attached Correctly….





HENCE THE DAY – 2 TASK FINSHED !!!!.....
