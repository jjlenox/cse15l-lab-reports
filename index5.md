1. Log into ieng6

open the terminal

"up arrow key" "enter" to input ssh cs15lwi23ahq@ieng6.ucsd.edu

![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2010.29.39%20PM.png)
  
2. Clone your fork of the repository from your Github account
 
type "git clone" and then ctrl+v to copy the github link already in the cliptboard

![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.31.48%20PM.png)

3. Run the tests, demonstrating that they fail

cd lab7
  
ctrl+c run test command off of week 3 lab and run with ctrl+v <enter>
  
![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.10.23%20PM.png) 
 
4. Edit the code file to fix the failing test

nano ListExamples.java
  
"down arrow key" multiple times until the 7th last line, "right arrow key" to index 1, and change index1 to index2
  
ctrl+x
  
ctrl+y
  
"enter"
  
![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.21.06%20PM.png) 
  
![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.21.23%20PM.png) 
  
5. Run the tests, demonstrating that they now succeed
  
"up arrow key" 3x "enter"
  
"up arrow key" 3x "enter"
  
to compile and run the tests again
  
![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.21.39%20PM.png) 
  
6. Commit and push the resulting change to your Github account (you can pick any commit message!)

git add L "Tab" to fill in ListExamples.java
  
git commit -m "A"
  
git push origin main
  
![Image](https://jjlenox.github.io/cse15l-lab-reports/Screenshot%202023-02-27%20at%2011.24.24%20PM.png) 
