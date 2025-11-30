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

## COMMAND AND OUTPUT

<img width="376" height="46" alt="image" src="https://github.com/user-attachments/assets/205f42b1-c5f7-40e1-bc71-49da0b1178db" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="387" height="44" alt="image" src="https://github.com/user-attachments/assets/4ed28b47-d11d-4057-aae1-13b9d5b21cd0" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="531" height="129" alt="image" src="https://github.com/user-attachments/assets/6ed87a67-e160-40bc-a34a-cbe362885081" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="593" height="101" alt="image" src="https://github.com/user-attachments/assets/3eb59c5b-661e-4436-bdfe-b916b423103c" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="529" height="134" alt="image" src="https://github.com/user-attachments/assets/1ad87470-0773-460f-9ed1-b3c6f0316d6a" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="396" height="22" alt="image" src="https://github.com/user-attachments/assets/6d1b025a-c0af-4063-8aa6-a90919954088" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="428" height="169" alt="image" src="https://github.com/user-attachments/assets/5cbefe1c-042e-4580-91b8-19ffe497d273" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="420" height="236" alt="image" src="https://github.com/user-attachments/assets/21008e6e-e72c-46e8-8227-722246a5d2c2" />

Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="516" height="189" alt="image" src="https://github.com/user-attachments/assets/3e934db7-68ab-4c6d-af8b-96068fe5cd27" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="372" height="88" alt="image" src="https://github.com/user-attachments/assets/ee245666-f676-4700-bc0a-2cb80ee7caf8" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="590" height="226" alt="image" src="https://github.com/user-attachments/assets/e2768518-d1a5-4325-a9a9-2111954cee9b" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="333" height="176" alt="image" src="https://github.com/user-attachments/assets/e2284a23-66aa-4b89-a5df-8ad8cba9108a" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="606" height="223" alt="image" src="https://github.com/user-attachments/assets/537bc9d4-673a-4544-81d8-f7c1d1a9e167" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="476" height="401" alt="image" src="https://github.com/user-attachments/assets/077cb1ba-d074-4287-af1b-a50f2787c1e5" />



# RESULT:
The commands/batch files are executed successfully.

