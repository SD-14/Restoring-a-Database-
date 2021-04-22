# **Create an Azure VM**

1.After logging in to the Azure portal, In the search bar, type virtual machines and click on that:

[Search VM](https://user-images.githubusercontent.com/83011430/115717971-53ba3200-a398-11eb-85de-37f117873ef2.png)

2.Then, click on Add button, and select Virtual-Machine:

[Add VM](https://user-images.githubusercontent.com/83011430/115718614-e78bfe00-a398-11eb-8d05-7b7d5e563838.png)

3.It will take you to Create a Virtual Machine page:
 - Select the subscription you'll be using for creating this VM.
 - Select on create **new resource group**, and give a name to your **resource group**.
 - Give a name to your Virtual machine, select region, select image as **Windows Server 2016 Datacenter-Gen1**.
 - Select size, and select the one which costs you the least.
 - Under **Administrator account**, give a **username**, **password**, and confirm the **same password**.
 - Under **Inbound port rules**, let the ports be default.
 - Click on **Next:Disks**
 - Under **Disk options**, you can select any of the **OS disk type** (But, recommended to use Standard or Premium SSD for faster loading time).
 - Let the encryption type be default.
 - Click on **Next:Networking**
 - You don't need to configure anything here,as by default a virtual network is created public ip is assigned; let the rest be default.
 - You can directly move to **Review+create** from **Networking** as you don't need to worry about the remaining sections.
 
 You should arrive at this page:
 
 [Review Page](https://user-images.githubusercontent.com/83011430/115721096-523e3900-a39b-11eb-8f11-e21b4e6b6121.png)
 
 Click on **Create**, and your deployment should begin.
 
4. Wait for the deployment to be completed, and click on **Go to resource**

5. Select the **Virtual Machine**
 - You'll be taken to the **Overview** section, and click on **public IP address** and it'll copy the IP just like the below picture where I've highlighted the IP address in yellow:
 
[Public IP Address](https://user-images.githubusercontent.com/83011430/115722078-41da8e00-a39c-11eb-9e1f-ccc5fa5987f7.png)

6. Next, you can either connect to the VM by clicking on the connect option present on the **Overview section** or open **Remote-Desktop-Connection(RDP)**

7. Paste the IP address, and click on **Connect**

8. It should ask you for your **Username** and **Password**, enter the same username and password provided while creating the VM:

[Authentication](https://user-images.githubusercontent.com/83011430/115723001-28861180-a39d-11eb-9e04-96665e516599.png)

9. Click on **Ok**, and it should start the remote session which should look like this:

[Remote Session](https://user-images.githubusercontent.com/83011430/115723314-7b5fc900-a39d-11eb-82ff-572f86175dbc.png)

10. VM was successfully created, and the user was able to successfully log into the VM
