Active Directory xRay Script

I started this as a personal project to help me during my work days on customer´s sites and environments. The idea was to compile and put all the manual tests the validations I used to make in the customer´s environment at a simple place in the most automated way as possible. 

The script does not record, create or modify anything in the environment (except for creating a folder named “ADxRay” in C:\, and a file named “ADxRay_Report.htm”). 

The script must be run at a Domain Controller running at least Windows Server 2012. We have seen best results when the script is run from the Schema Master Domain Controller.

The script must be run by a user with Domain Admin privileges (Enterprise Admins would be better if dealing with multiple domains and forests).

The lastest version also creates log files in the C:\ADXRay folder for each step executed by the script.

This script may take several hours to complete!

Releases can be found at: [Releases](https://github.com/Merola132/ADxRay/releases)

![alt text](https://github.com/Merola132/ADxRay/0.png)
