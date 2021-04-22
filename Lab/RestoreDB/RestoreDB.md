# **RestoreDB**

1. After following the prerequisites, and installing **SQL Server 2019** in the VM; Install [SQL Server Management Studio](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15)

2. Once the .bak file has been downloaded in the VM, copy it and place it in :

**C:\Program Files\Microsoft SQL Server\MSSQL15.MSSQLSERVER\MSSQL\Backup**

[Backup](https://user-images.githubusercontent.com/83011430/115725010-16a56e00-a39f-11eb-88da-5967c5c00dae.png)

3. Open **SQL Server Management Studio**, and connect to the **VM SQL Server** :

[SQL Server Connect](https://user-images.githubusercontent.com/83011430/115725948-e6120400-a39f-11eb-8cab-c3d5c6b50c5b.png)

4. After successfully connecting to the SQL server, under **Object Explorer**, right-click **Databases** and select **Restore Database** :

[RestoreDB-Option](https://user-images.githubusercontent.com/83011430/115726546-70f2fe80-a3a0-11eb-9c71-55cb74400945.png)

5. Under the **General section**, under **Source**, select **Device** and click on the **button with 3 dots**, it should open up a pop-up window by the name **Select Backup Devices** :

[Select Backup Devices](https://user-images.githubusercontent.com/83011430/115727351-245bf300-a3a1-11eb-95d0-1fdb63331b57.png)

6. Click on **Add**, and then navigate to the **Backup** folder where you saved the .bak file, click on that file and click on Ok: 
 
[File Added](https://user-images.githubusercontent.com/83011430/115727819-992f2d00-a3a1-11eb-8744-febcc6425a4c.png)

7. Once done with this, under **Destination**, the database name should appear, and should look like this :

[Source & Destination Path](https://user-images.githubusercontent.com/83011430/115728399-1d81b000-a3a2-11eb-8add-993b937b1a0c.png)

8. Click on **Ok**, and the **Restoring Database operation** should begin.

9. Once this is complete, go back to **SQL Server Management Studio** and click on refresh button under **Object Explorer**, the database should show up :

