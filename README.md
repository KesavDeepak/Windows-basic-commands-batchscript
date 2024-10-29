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
```
mkdir %userprofile%\Desktop\MyLab
```
![image](https://github.com/user-attachments/assets/0f645b87-9285-4964-b408-72a20e3afcd5)


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
cd %userprofile%\Desktop\MyLab
```
![image](https://github.com/user-attachments/assets/97de106a-e447-4a52-99e5-898f64ed4281)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
type nul > MyFile.txt
```
![image](https://github.com/user-attachments/assets/e63556e4-8680-408a-a4b1-a23ff7332fd7)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
dir %userprofile%\Desktop\MyLab
```

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.


## COMMAND AND OUTPUT


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.







## OUTPUT





# RESULT:
The commands/batch files are executed successfully.

