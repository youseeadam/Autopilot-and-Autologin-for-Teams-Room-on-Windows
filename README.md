In this for part series I go over the basics of getting AutoPilot and AutoLogin for Teams Rooms on Windows.
The contents of these videos are derived from Microsoft's learn page on this subject: https://learn.microsoft.com/en-us/microsoftteams/rooms/autopilot-autologin  

Part 1: Configuration  
Part 2: Lenovo + Logitech: Autopilot Setup Made Easy  
Part 3: Manual Enrollment  
Part 4: Basic Troubleshooting  

# Part 1: Configuration  
This part covers the following steps  

00:38 Why use AutoPilot and AutoLogin  
01:15 Portals  
01:25 Prerequsites  
01:41 Permissions  
02:11 Configuration  
02:19 Conditional Access  
03:03 Teams Room Account  
03:36 Create the Group  
05:03 Teams Room App  
06:37 Enrollment Status Page  
07:34 Profile  
08:36 Local Administrator Password Solution  
09:59 Enrollment  
10:41 AutoLogin  
11:59 The OUt of Box Experience  
12:28 Logging in as Admin with LAPS  

[https://youtu.be/G65rcOqfhGg](https://youtu.be/G65rcOqfhGg)

IMPORTANT: Group Names must begin with MTR- this is not case sensitive  
Download the intune win app: https://aka.ms/mtrp/autopilot-tool  
The Group Query: ```(device.devicePhysicalIds -any _ -startswith"[OrderID]:MTR-")```  

# Part 2: Lenovo + Logitech: Autopilot Setup Made Easy  
This Part covers the following steps 

00:34 Process Overview  
01:47 First Time Enrollment  
02:34 AutoPilot + Lenovo Thinksmart Manager  

https://youtu.be/8AYuIQEjDj0

SKU for AutoPilot: 5MS0R49023

# Part 3: Manual Enrollment  
This Part covers the following steps  

00:47 The CSV file format  
01:03 OOBE Process  
01:22 THe output of the CSV file    
02:30 Shutting down the computer  

https://youtu.be/_xiMO7T7WN4?si=UbFnvOXbTemqmMdY

Download the Microsoft Script: https://learn.microsoft.com/en-us/autopilot/add-devices#save-the-hardware-hash-locally-on-a-device-as-a-csv-file  
Download the Logitech Script(Pending digital signature)  

# Part 4: Basic Troubleshooting 
This Part covers the following steps  

00:34 Common Errors  
00:57 Log FIles  
01:47 Resetting the Device    
02:33 Deleting the Device  

[Youtube Link](https://youtu.be/-rvLpo61w0s)





