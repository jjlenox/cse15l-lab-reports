Website: https://jjlenox.github.io/cse15l-lab-reports/index5

1. Log into ieng6

open the terminal

"up arrow key" "enter" to input ssh cs15lwi23ahq@ieng6.ucsd.edu, this command logs into the ieng6 server and the command was very recently used so I went to the history.

![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2010.29.39%20PM.png)
  
2. Clone your fork of the repository from your Github account
 
type "git clone" and then ctrl+v to copy the github link already in the cliptboard, it will clone the repository from github.

![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.31.48%20PM.png)

3. Run the tests, demonstrating that they fail

cd lab7, to access the lab7 folder that was just copied.
  
ctrl+c run test command off of week 3 lab and run with ctrl+v enter, to compile the tests
  
ctrl+c run test command off of week 3 lab and run with ctrl+v enter, but change the file name at the end to ListExamplesTests, to run the tets
  
![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.10.23%20PM.png) 
 
4. Edit the code file to fix the failing test

nano ListExamples.java, to open the file editor for that file
  
"down arrow key" multiple times until the 7th last line, "right arrow key" to index 1, and change index1 to index2, to fix the mistake
  
ctrl+x, to exit
  
y, to confirm the change
  
"enter", to save under the same name
  
![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.21.06%20PM.png) 
  
![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.21.23%20PM.png) 
  
5. Run the tests, demonstrating that they now succeed
  
"up arrow key" 3x "enter", to run first test command again, to compile the tests
  
"up arrow key" 3x "enter", to run the second test command again, to run the tests
  
to compile and run the tests again, they are in the command history
  
![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.21.39%20PM.png) 
  
6. Commit and push the resulting change to your Github account (you can pick any commit message!)

git add L "Tab" to fill in ListExamples.java, to add that file to the changes
  
git commit -m "A", commit it with the comment "A" becuase it is quickly to type
  
git push origin main, push the changes to github
  
![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.24.24%20PM.png) 
