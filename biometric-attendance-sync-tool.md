Steps to install Biometric Attendance Sync Tool(For ERPNext)

Requirements:
	python3.6+
	    -> sudo apt update
	    -> sudo apt install software-properties-common
	    -> sudo apt install python3.8
	    -> sudo apt install python3-pip
	    -> python -m pip install pip


Clone biometric attendance sync tool from github
	git clone https://github.com/frappe/biometric-attendance-sync-tool.git
Enter into biometric-attendance-sync-tool folder
	cd biometric-attendance-sync-tool
Create a virtual environment
	python3 -m venv venv
Activate the virtual environment
	source venv/bin/activate
Install the requirements
	pip install -r requirements.txt
Duplicate local_config.py.template file and name it as local_config.py
Run this script using python3 erpnext_sync.py

open local_config.py and fill the Api key, Api secret, ERPNext URL, Device IP
