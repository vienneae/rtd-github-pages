Getting Started On Windows
============================


Downloading Python
--------------------

First, we need to download the software for the programming language that we want to
code in, the language we'll use is called Python.

Download from the following link: https://www.python.org/downloads/windows/


Opening Your Command Line Interface
---------------------------------------

In order to use a computer, we need some way of interacting with the computer's
functions and services. Luckily, every operating system (Mac, Windows, etc.) comes 
with user-interfaces. The one that you are probably most familiar with is the
graphical user interface (GUI), which allows users to interact with files, folders,
programs, etc. using graphical icons (e.g. Finder on Mac and My Computer on Windows).
The other kind of user interface is called a command line interface (CLI). This differs
from a GUI in that it is text-based, the user enters commands and executes them. The CLI
is what programmers use to navigate their computer and run programs, so it is important
to become familiar with it. Each operating system's (OS') CLI differs in name and some syntax, 
but that’s about it. 

Window’s CLI is called Command Prompt, in order to open it, click Start, type 
”cmd” in the search bar, and press Enter. 


Basic Navigation Commands
----------------------------

Data on a computer is kept in files which are organized into directories (aka folders)
These files and directories are accessed and manipulated by repeatedly typing 
commands into the CLI and pressing Enter. Every directory in your computer is defined 
by a path. The path is just the set of all directories that leads to the specific 
directory that you are currently in. 

Each OS has unique basic commands which you type into the CLI and then press enter to execute. 
Some important commands are given in the table below:

.. list-table:: Navigation Commands
   :widths: 25 50 
   :header-rows: 1

   * - Command
     - Function
   * - cd
     - | Displays the path to your current directory. For example, if it displays, 
       | \\User\\Desktop\\School, then you are currently in the School directory,
       | which is in the ”Desktop” directory, which is itself in the ”User” directory.
   * - dir
     - | Displays the files and directories that are stored in your current directory.
   * - cd <directory>
     - | Moves you to a different directory. If the directory that you wish to go to 
       | is in your current directory, then simply type cd NameOfDirectory.
       | Otherwise, you will need to specify the path to the directory by typing
       | something like cd /User/Desktop/School/NameOfDirectory.
   * - <fileName>.extension
     - | Used to open files. If you wanted to open a file named ”data.csv”, you 
       | would type, ”data.csv”. 
   * - <programName>.py
     - | Executes a program that is written in the Python programming language. 
       | Python files are designated with the extension, .py. All programming 
       | languages have files with their own extensions.


Writing Your First Program
----------------------------

There are many ways to program/write code. 

We will provide information on two of the primary ways, using a notebook and using a text editor.


Online Notebook
-------------------

For students with minimal experience, we recommend starting off with a notebook. 
A notebook allows users to input a chunk of code, and then run that chunk. This is great because it
allows you to quickly find out whether or not your code works. As opposed to writing an entire program
and then finding out it doesn't work.
We'll use JupyterHub, which is an open-source web application for programming.
All McMaster students can access the phys-ugrad (McMaster's physics server) JupyterHub by:
    - downloading Cisco AnyConnect VPN and connecting to sslvpn.mcmaster.ca (Instructions found |link8|)
    - navigating to the following link, which will open up the McMaster phys-ugrad notebook |link9|
Now you can create a new Python file by selecting 'New' and then 'Python 3'. Now type the following line:

.. |link8| raw:: html

   <a href="https://www.mcmaster.ca/uts/network/vpn" target="_blank">here</a>

.. |link9| raw:: html

   <a href="https://physics.mcmaster.ca/jupyter" target="_blank">here</a>
  


print("Hello World!")

Then hit Run to execute that line of code. If "Hello World" appears below the line of code, then you have
successfully run the line of code! If nothing appears, then you probably made a mistake, which is the best
way to become a better programmer. If you can't figure out your error, feel free to post it on the Python Bootcamp
course Discussion board on Avenue, or look it up on Google. Programmers spend a lot of time googling issues, it is
a natural part of the process, and shouldn't be looked down upon. So Google away!

Text Editor 
--------------

Once we become comfortable with our coding skills, we will want to write more complicated programs that
can be packaged and shared with others. The best way to do this is by writing a program in what is called
a text editor. After writing, we save the program as a file with the .py extension, and then run the program in 
the command line. Lets download a text editor, Sublime Text is free and widely used. It can be dowloaded from the 
following link (make sure to choose the correct download for your OS):

|link13|

.. |link13| raw:: html

   <a href="https://www.sublimetext.com/3" target="_blank">Sublime Text</a>


Let’s write and run one of the simplest programs ever, just to get an idea of what 
the programming process looks like. Once downloaded, open Sublime Text and create a 
new file. Since we want to code in Python, make sure that the file has the .py extension 
after the name. Save it to any directory you want, but I recommend the Desktop for easy 
accessibility. In your empty file, type the following:

print(”Hello, World!”)

Then save the file. Now open your CLI and navigate to the directory that contains your 
file. Once there, use the appropriate command from the previous slide to execute the program. 
If ”Hello, World” appears in your CLI window, then you have successfully run the program!

Next Step
-------------

Now that you can write and run programs, feel free to go to:

    - :doc:`Python Basics <pythonbasics>`: to learn Python syntax and test your knowledge with Avenue quizzes
    - :doc:`Python For Science <whypython>`: to explore Python templates that can be used for scientific data analysis
