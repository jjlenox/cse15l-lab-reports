Website: https://jjlenox.github.io/cse15l-lab-reports/index6

Before we did the races for lab in week 8 I was already thinking about writing a bash script. 
For the lab4 report, I would have had 2 different bash scripts. 
The reason for 2 different scripts is that I don't know how to interact with nano with a bask script. 
The first one would be consist of the following commands. 

ssh cs15lwi23ahq@ieng6.ucsd.edu // open up the server

git clone git@github.com:jjlenox/lab7.git // clone the repository

cd lab7 // go into the newly cloned lab7 folder

javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java // compile the tests

java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner. JUnitCore ListExamplesTests // run the tests

nano ListExamples.java // open up the nano editor for the tests file

Once the nano editor is open I'll go and make the changes by going all the way down the page and change the error, change "index1" to "index2"

I'll close nano with ^X press Y to confirm changes and then the enter key to save it as the same name. 

I'll run the 2nd bash script with the following lines of code. 

javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java // compile the tests

java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner. JUnitCore ListExamplesTests // run the tests

git add ListExamples.java // to add that file to the changes

git commit -m "A" // commit it with the comment "A" becuase it is quickly to type

git push origin main // to push the changes to github

In the future I want to find a way to use nano with the bash script, and also maybe impliment parts of the grade.sh so it will only open up nano if there is a failure. 
