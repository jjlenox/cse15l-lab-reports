## How to log into a course-specific account on ieng6
# By Joshua Waters

link: https://jjlenox.github.io/cse15l-lab-reports/Instructions

- 1

First install visual code studios by opening up this link 
[VCS](https://code.visualstudio.com/) and click the download option for your provided operating system. Click yes to any windows defender or firewall pop-ups, this is normal. 

**VCS looks like this:**

![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-01-12%20123611.png)
---
- 2 

Open up VCS and open up the terminal by clicking "terminal", then "new terminal". At the top right of the terminal click the drop down menu next to the plus sign, and click "bash" to open a bash terminal. 
Once in the terminal, type the command:

'''ssh cs15lwi23*@ieng6.ucsd.edu'''

The star in the command is your personal letters for your account.
The terminal will have yes or no questions, say yes to everything and then enter your password.

**It should look like this:**

![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-01-12%20123844.png)
---
- 3

Now try some commands like:

'''cd'''

'''pwd'''

'''ls'''

and try to access different directories like

/home/linux/ieng6/cs15lwi23/cs15lwi23*

where the star are the personal letters of a student.

**some command inputs looks like this:**

![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-01-12%20123936.png)

The '''cd''' command is the change directory command. It's used by typing cd and then a file or folder in the current directory.
The '''pwd''' command provides the current directory the terminal is accessed at the moment.
THe '''ls''' command provides the files or folders that are in the current directory. 
