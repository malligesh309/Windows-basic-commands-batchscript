# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
mkdir %userprofile%\Desktop\MyLab

![image](https://github.com/malligesh309/Windows-basic-commands-batchscript/assets/140491043/f1385737-a8f7-4c20-8d28-26f1bc690d58)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
cd %userprofile%\Desktop\MyLab
![image](https://github.com/malligesh309/Windows-basic-commands-batchscript/assets/140491043/0a57bbcc-1b03-4082-8cc1-49556ad17b23)
![image](https://github.com/malligesh309/Windows-basic-commands-batchscript/assets/140491043/c4809614-be45-4758-a5d2-6b8ec59edf03)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
dir %userprofile%\Desktop\MyLab
![image](https://github.com/malligesh309/Windows-basic-commands-batchscript/assets/140491043/831584b1-a06b-4fce-9b8d-795b3587209b)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
mkdir %userprofile%\Desktop\Backup
mkdir %userprofile%\Desktop\Backup

![image](https://github.com/malligesh309/Windows-basic-commands-batchscript/assets/140491043/1a39764e-6b14-4c7b-a449-f1f5549bc706)
![image](https://github.com/malligesh309/Windows-basic-commands-batchscript/assets/140491043/53f11c21-8677-4f44-b212-a080c5006612)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents
![image](https://github.com/malligesh309/Windows-basic-commands-batchscript/assets/140491043/ee1cdf84-00dc-4c72-b076-6e4f372f0558)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.


@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!




## OUTPUT
![image](https://github.com/malligesh309/Windows-basic-commands-batchscript/assets/140491043/c6abd3b5-9d05-4ab5-8d37-53f0af0284a3)

## RESULT:

The commands/batch files are executed successfully.






