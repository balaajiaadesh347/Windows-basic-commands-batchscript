# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"
<img width="613" height="160" alt="1" src="https://github.com/user-attachments/assets/025c503d-f935-4c62-9533-0f8b9a6543e8" />



## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="670" height="90" alt="2" src="https://github.com/user-attachments/assets/80a576e8-a51b-428a-af02-7b7325906a12" />


## COMMAND AND OUTPUT
Create the file Rose.txt

<img width="712" height="425" alt="3" src="https://github.com/user-attachments/assets/80945f0d-06a4-4848-a711-d467bbc60f8e" />


## COMMAND AND OUTPUT

<img width="606" height="151" alt="4" src="https://github.com/user-attachments/assets/bacf9371-5c81-4d1a-817e-9f725882e48e" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="574" height="129" alt="5" src="https://github.com/user-attachments/assets/41061e1f-0fcb-40d1-acbb-d16134860690" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="570" height="224" alt="6" src="https://github.com/user-attachments/assets/ef02de8f-988f-4417-9762-7cbc61807117" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="570" height="224" alt="6" src="https://github.com/user-attachments/assets/5cf1ad17-3406-4e8e-ab37-41b272835de4" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT


<img width="555" height="718" alt="7" src="https://github.com/user-attachments/assets/5d359b31-2a13-415f-a927-80fe52801028" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="667" height="224" alt="8" src="https://github.com/user-attachments/assets/f8274f22-e81c-4d32-a4a6-2a5d717ddbc3" />



Compare the file hello.txt and rose.txt



## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

