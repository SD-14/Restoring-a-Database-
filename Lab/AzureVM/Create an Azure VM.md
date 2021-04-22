# **Create an Azure VM**

1.After logging in to the Azure portal, In the search bar, type virtual machines and click on that:

[Search VM](https://user-images.githubusercontent.com/83011430/115717971-53ba3200-a398-11eb-85de-37f117873ef2.png)

2.Then, click on Add button, and select Virtual-Machine:

[Add VM](https://user-images.githubusercontent.com/83011430/115718614-e78bfe00-a398-11eb-8d05-7b7d5e563838.png)

3.It will take you to Create a Virtual Machine page:
 -Select the subscription you'll be using for creating this VM.
 -Select on create **new resource group**, and give a name to your **resource group**.
 -Give a name to your Virtual machine, select region, select image as **Windows Server 2016 Datacenter-Gen1**.
 -Select size, and select the one which costs you the least.
 -Under **Administrator account**, give a **username**, **password**, and confirm the **same password**.
 -Under **Inbound port rules**, let the ports be default.
 -Click on **Next:Disks**
 -Under **Disk options**, you can select any of the **OS disk type** (But, recommended to use Standard or Premium SSD for faster loading time).
 -Let the encryption type be default.
 -Click on **Next:Networking**
 -You don't need to configure anything here,as by default a virtual network is created public ip is assigned; let the rest be default.
 -You can directly move to **Review+create** from **Networking** as you don't need to worry about the remaining sections.
 
 
