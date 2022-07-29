## Setup Automatic Biometric Integration in Task Scheduler
#### Step -1 : Open Ubuntu Subsystem in your windows and then moved to the biometric file
#### Step -2 : Create a shell script .sh file 
 * Eg Command - *vi hello.sh*
#### Step -3 : Inside of shell script file "hello.sh" we given the path of biometric server script file.
 * Eg Command - 
                <p> nano hello.sh </p> 
                <p>#!/bin/sh</p>
                <p> /home/administrator/biometric-attendance-sync-tool/* next line *python3 erpnext_sync.py </p>

Use these command and the save it and exit
#### Step -4 : Open the Task Scheduler by typing Task in the Windows search box
#### Step -5 : Select Create a Basic Task from the Actions list on the right
#### Step -6 Name the task
#### Step -7 Click Next and select When the computer starts Trigger
#### Step -8 Click Next and for the Action select Start a program
#### Step -9 For the Program/Script browse the wsl.exe fileand add the arguments "biometric script path file" 
#### Step - 10 : Before Finishing, select the Open the Properties dialog option
#### Step - 11 : In the General tab select Run whether user is logged in or not and Run with highest privileges

## Screenshots :

<img src="(https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624308.jpeg)">

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624308 (1).jpeg">

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624308 (2).jpeg">

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624308 (2).jpeg">

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624308 (3).jpeg" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624308 (4).jpeg" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624308 (5).jpeg" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624308 (6).jpeg" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624308 (7).jpeg" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624308 (8).jpeg" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624308 (9).jpeg" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/11.png" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/12.png" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/13.png" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/14.png" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/15.png" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/16.png" >

<img src="//home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/17.png" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/18.png" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/19.png" >

Create .sh File Command 
<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/20.png" >
Set path File Commands
<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/21.png" >

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/22.png" >

Whether given path is correct or wrong use this run and click okay button. 
use this command : bash /home/administrator/biometric-attendance-sync-tool/python3 erpnext_sync.py 

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/23.png" >

Permission for shell script command

<img src="/home/hr-emp-00016/frappe-bench/v13-bench/apps/thirvusoft-biometric/assests/photo1657624572.jpeg" >
