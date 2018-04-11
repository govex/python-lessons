### Installation Guide and Running your First Python Script

#### Running Python in Windows or Linux
- Download and install Python from appropriate installer at the bottom of this page: https://www.python.org/downloads/release/python-365/
- You can use the command line to run codes, but for learning, the IDLE program (packaged with Python) can be helpful.
- When you run IDLE, you'll automatically be in the interactive interpreter mode where you can run Python commands one at a time.
  - To create a new file from IDLE, go to File > New Window.  A new, blank screen will open up where you can create your Python projects.
  - When you have a Python file open in IDLE, you can run it at any time by pressing **F5**.
- From the command line, run python3 shell and you'll enter the interpreter where you can run Python commands one at a time, similar to IDLE.
  - You can create Python files in any text editor, and run them in the command line by writing "python3 " and then the path to your file.
  
#### Running Python on a Mac

Python 2.7 comes bundled with Macs already, so be careful to use **python3** and **pip3** or you might encounter unexpected errors.

**You should probably make it easy on yourself and download [Sublime Text 3](http://www.sublimetext.com/3), which will allow you to run Python files straight from your editor.**

#### Mac: Running Python commands one at a time (using the interactive interpreter)
- Open a terminal window (from the Finder, search for Terminal)
- Type **python3** and hit enter
- Your command prompt should change from a dollar sign (**$**) to three greater than signs (**>>>**)
- The command prompt is a signal of where you are -- terminal is **$**; python is **>>>**
- Once you have the **>>>** prompt, you can enter as many Python commands as you like.
- Type **exit()** to quit and return to the command prompt.

#### Mac: Running Python Files from the Terminal
- Open a terminal window (from the Finder, search for Terminal)
- When you open the terminal window, the words before your username are the folder you're in.
- You're probably on your desktop to start. I recommend creating a folder on your desktop to put your Python scripts in.
- For this example, let's say I named the folder pyscripts.
- Go back to the terminal and type in **cd pyscripts** -- this will __c__hange the __d__irectory the terminal is working in to pyscripts.
- When you create a Python script for Python to run, you should create it in TextEdit, TextWrangler, or some other text editor that can save files in **plain text** format -- any other kind of format will confuse Python!
- Let's also assume that I created a Python script called **lesson1_pbj.py**, and that file lives in **pyscripts** on the desktop.
- To run lesson1_pbj.py, I would type into the terminal: **python3 lesson1_pbj.py**

#### Mac: Troubleshooting Running Python Files from the Terminal
- Make sure you're in the correct folder! You can check which folder the terminal is looking in by typing **pwd**
- Similarly, make sure the file you want to run is in the folder you're in! Type **ls** to see all of the files in the folder terminal is currently working in.
- Remember that when you see the dollar sign prompt (**$**), you're working in terminal, and can run scripts at the command line.  But when you see the **>>>** prompt, you're in Python's interactive interpreter mode, and you'll need to type **exit()** to get back.
