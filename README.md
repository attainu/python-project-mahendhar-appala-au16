Junk File Organizer with Python


Basically, as a lazy programmer my desktop is full of files (Junk Files). Due to the large number of files, it is a daunting task to sit and organize each file. To make that task easy the below Python script comes handy and all the files are organized in a well-manner within seconds.

for using without any outside library installed, download this file and use it
Main functionality of this code
Organize by extension
Organize by size
Organize by last used date

How to Use the Project:
Organize by extension:
1.Go to byextension.py file in Visual Studio Code
2.Execute the program
3.It will ask you for your target path 
4.Paste the path directory of your folder
5.Run the project

Organize by Size:
1.Go to bysize.py program in Visual Studio Code
2.Execute the program
3.It will ask you for your target path 
4.Paste the path directory of your folder
5.Run the project

Organize by Date:
1.Go to bydate.py file in Visual Studio Code
2.Execute the program
3.It will ask you for your target path 
4.Paste the path directory of your folder
5.Run the project

1. Organize by extension
by using this option user can organize their files by their file extension in a given folder, folder will be created according to file extension and finally all files will be moved to a created folder.

2. Organize by size
by using this option user can organize their files by their file size, according to file sizes random folders will be created and respective files will be moved to them.

3. Organize by Last used/accessed date
by using this option user can organize their files by last used date. random folders will be created according to file's last used date and files will be moved to them.

what i used :
I used many built-in libraries like- shutil for file movement,datetime for get the date of the files,argparse for the command line parsing and etc.

future improvement:
We can design the ui for the program so a normal user can easily interact with it. We can add more features like deleting the junk files after a certain period of time.

Note: if the use not provide the argument then program will perform the operation on the current directory.
