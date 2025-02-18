# TrumpfMetamation_Task_Alarm
Create a GitHub Repository
	1.	Go to GitHub and sign in.
	2.	Click the + icon in the top-right and select New repository.
	3.	Name the repository: TrumpfMetamation_Task_Alarm.
	4.	Select Public or Private as needed.
	5.	Check “Add a README file”.
	6.	Click Create repository.

Step 2: Clone the Repository Locally

Open Command Prompt (cmd) or Git Bash and run:

git clone https://github.com/YOUR_USERNAME/TrumpfMetamation_Task_Alarm.git
cd TrumpfMetamation_Task_Alarm

Step 3: Install Required NuGet Packages

Run these commands in the terminal inside your project folder:

dotnet add package Appium.WebDriver
dotnet add package Selenium.WebDriver

Step 4: Implement the C# Automation Script

Create a New C# Console Application

Run:

dotnet new console -n AlarmAutomation
cd AlarmAutomation
dotnet add package Appium.WebDriver
dotnet add package Selenium.WebDriver

Then, create a file AlarmAutomation.cs and add the following script:

Step 5: Add a README.md

Inside your repository, create a file README.md with the following content:

# TrumpfMetamation_Task_Alarm

## Overview
This project automates the Windows Clock app to:
- Create multiple alarms with input data.
- Verify that alarms are created.
- Delete alarms and validate removal.

## Prerequisites
- Windows 10/11 with the default *Clock app*.
- [WinAppDriver](https://github.com/microsoft/WinAppDriver) installed and running.
- .NET Core SDK installed.
- Appium.WebDriver package installed.

## Installation
Clone the repository:
sh
git clone https://github.com/YOUR_USERNAME/TrumpfMetamation_Task_Alarm.git
cd TrumpfMetamation_Task_Alarm/AlarmAutomation
dotnet build

Running the Automation Script

Start WinAppDriver:

WinAppDriver

Run the C# script:

dotnet run

Expected Output
	•	The script creates alarms.
	•	Validates their creation.
	•	Deletes alarms and confirms removal.

Contributing
	1.	Fork the repo.
	2.	Create a new branch: git checkout -b feature-branch.
	3.	Commit changes: git commit -m "Your message".
	4.	Push to branch: git push origin feature-branch.
	5.	Submit a Pull Request.

---

### **Step 6: Commit and Push to GitHub**
Run the following commands:

sh
git add .
git commit -m "Initial commit - Added alarm automation script"
git push origin main

Step 7: Verify in GitHub
	1.	Go to your repository on GitHub.
	2.	Check if all files are present (AlarmAutomation.cs, README.md, etc.).
	3.	If needed, update any missing files and push changes.

Now your repository is set up with a full-fledged C# test automation script for Windows Clock alarms! Let me know if you need any modifications
