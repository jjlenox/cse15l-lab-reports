1. Log into ieng6

open the terminal

"up arrow key" "enter" to input ssh cs15lwi23ahq@ieng6.ucsd.edu
  
2. Clone your fork of the repository from your Github account
 
type "git clone" and then ctrl+v to copy the github link already in the cliptboard

3. Run the tests, demonstrating that they fail

cd lab7
  
ctrl+c run test command off of week 3 lab and run with ctrl+v <enter>
 
4. Edit the code file to fix the failing test

nano ListExamples.java
  
"down arrow key" multiple times until the 7th last line, "right arrow key" to index 1, and change index1 to index2
  
ctrl+x
  
ctrl+y
  
"enter"
  
5. Run the tests, demonstrating that they now succeed
  
"up arrow key" 3x "enter"
  
"up arrow key" 3x "enter"
  
to compile and run the tests again
  
6. Commit and push the resulting change to your Github account (you can pick any commit message!)

git add L "Tab" to fill in ListExamples.java
  
git commit -m "A"
  
git push origin main
