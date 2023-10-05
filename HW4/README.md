# 28SEPT23: Computer and Network Security HW4 by Ethan To 
## 2: Creating AD Users
Me and the group have created our user accounts for the Microsoft Active Directory.
![alttext](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW4/2User.png)
![alttext](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW4/2user2.png)

## 3: Logon wiht User Acount
As seen below, I have created and entered my acount in Active Directory:

![alttext](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW4/Screenshot%202023-09-27%20203339.png)

## 4.1: Change Powershell Permissions
I have altered my account settings to be able to access Powershell Scripts using

`Set_ExecutionPolicy -ExecutionPolicy Bypass -Scope CurrentUser`

We can list the Powershell permissions as seen below:

![alttext](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW4/4.1.png)

## 4.2: Test Powershell Script Execution
I created a powershell script named `show_all_exes.ps1`

It can find all the executables in the Program Files Folder:

![alttext](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW4/execute.png)

## 4.3: Create More AD Objects
The group and I created more Active Directory users and objects through Bad Blood. The output can be seen below:

![alttext](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW4/4.2_1.png)

![alttext](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW4/4.3_2.png)

![alttext](https://github.com/toethan777/To-CNS-Lab-2023/blob/main/HW4/4.3_3.png)
