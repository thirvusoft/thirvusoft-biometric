## Setup Automatic Biometric Integration in Task Scheduler
#### Step -1 : Open Ubuntu Subsystem in your windows and then moved to the biometric file
#### Step -2 : Create a shell script .sh file 
 * Eg Command - *vi hello.sh*
#### Step -3 : Inside of shell script file "hello.sh" we given the path of biometric server script file.
 * Eg Command - 
                <p> nano hello.sh </p> 
                <p>#!/bin/sh</p>
                <p>cd /home/administrator/biometric-attendance-sync-tool/* next line *python3 erpnext_sync.py </p>

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

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624308.jpeg">

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624308%20(1).jpeg">

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624308%20(2).jpeg">

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624308%20(2).jpeg">

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624308%20(3).jpeg" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624308%20(4).jpeg" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624308%20(5).jpeg" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624308%20(6).jpeg" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624308%20(7).jpeg" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624308%20(8).jpeg" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624308%20(9).jpeg" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/11.png" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/12.png" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/13.png" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/14.png" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/15.png" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/Screenshot from 2022-11-08 10-54-48.png" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/16.png" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/17.png" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/18.png" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/19.png" >

Create .sh File Command 
<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/20.png" >
Set path File Commands
<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/21.png" >

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/22.png" >

Whether given path is correct or wrong use this run and click okay button. 
use this command : bash /home/administrator/biometric-attendance-sync-tool/python3 erpnext_sync.py 

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/23.png" >

Permission for shell script command

<img src="https://github.com/thirvusoft/thirvusoft-biometric/blob/latest_branch/assests/photo1657624572.jpeg" >
