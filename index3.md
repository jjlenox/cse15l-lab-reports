[cs15lwi23ahq@ieng6-202]:skill-demo1-data:264$ less -X written_2/

total 16
drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 ./

drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 ../

drwxr-s--- 3 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 non-fiction/

drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 travel_guides/

————————————————-————————————————-

[cs15lwi23ahq@ieng6-202]:skill-demo1-data:265$ less -X written_2/non-fiction/

total 12

drwxr-s--- 3 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 ./

drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 ../

drwxr-s--- 8 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 OUP/



The -X command keeps the list open on the terminal. This is helpful for when you want to refer back to the list without opening it back up again. 



[cs15lwi23ahq@ieng6-202]:skill-demo1-data:267$ less -o less_results.txt written_2

[cs15lwi23ahq@ieng6-202]:skill-demo1-data:268$ ls

less_results.txt  written_2

[cs15lwi23ahq@ieng6-202]:skill-demo1-data:269$ cat less_results.txt 

total 16

drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 ./

drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 ../

drwxr-s--- 3 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 non-fiction/

drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 travel_guides/

————————————————-————————————————-

[cs15lwi23ahq@ieng6-202]:skill-demo1-data:267$ less -o less_results2.txt written_2/non-fiction/

[cs15lwi23ahq@ieng6-202]:skill-demo1-data:272$ cat less_results2.txt 

total 12

drwxr-s--- 3 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 ./

drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 ../

drwxr-s--- 8 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 OUP/

[cs15lwi23ahq@ieng6-202]:skill-demo1-data:273$ 



-o command prints the result to a text file. Can be helpful to refer back to what was in a file before it gets changed.



[cs15lwi23ahq@ieng6-202]:skill-demo1-data:267$ less -i written_2/non-fiction/OUP/Castro



/chp



-rwxr-x--- 1 cs15lwi23ahq ieng6_cs15lwi23 41470 Feb  9 10:37 chP.txt* //this is highlighted

-rwxr-x--- 1 cs15lwi23ahq ieng6_cs15lwi23  8274 Feb  9 10:37 chQ.txt*

-rwxr-x--- 1 cs15lwi23ahq ieng6_cs15lwi23 33420 Feb  9 10:37 chR.txt*

-rwxr-x--- 1 cs15lwi23ahq ieng6_cs15lwi23 19909 Feb  9 10:37 chV.txt*

-rwxr-x--- 1 cs15lwi23ahq ieng6_cs15lwi23  6724 Feb  9 10:37 chW.txt*

-rwxr-x--- 1 cs15lwi23ahq ieng6_cs15lwi23  5424 Feb  9 10:37 chY.txt*

-rwxr-x--- 1 cs15lwi23ahq ieng6_cs15lwi23  5431 Feb  9 10:37 chZ.txt*



————————————————-————————————————-



[cs15lwi23ahq@ieng6-202]:skill-demo1-data:267$ less -i written_2/non-fiction/OUP/Berk



/ch4



-rwxr-x--- 1 cs15lwi23ahq ieng6_cs15lwi23 103491 Feb  9 10:37 CH4.txt* //this is highlighted

-rwxr-x--- 1 cs15lwi23ahq ieng6_cs15lwi23  92355 Feb  9 10:37 ch1.txt*

-rwxr-x--- 1 cs15lwi23ahq ieng6_cs15lwi23 102942 Feb  9 10:37 ch2.txt*

-rwxr-x--- 1 cs15lwi23ahq ieng6_cs15lwi23  66887 Feb  9 10:37 ch7.txt*



-i commmand makes it easier to find files without worrying if there is a capital. This is useful for a human to find something if they do not know if a 
file is capitalised or not. 



[cs15lwi23ahq@ieng6-202]:skill-demo1-data:286$ less -F written_2/

total 16

drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 ./

drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb 13 18:45 ../

drwxr-s--- 3 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 non-fiction/

drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 travel_guides/



————————————————-————————————————-



[cs15lwi23ahq@ieng6-202]:skill-demo1-data:287$ less -F written_2/non-fiction/

total 12

drwxr-s--- 3 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 ./

drwxr-s--- 4 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 ../

drwxr-s--- 8 cs15lwi23ahq ieng6_cs15lwi23 4096 Feb  9 10:37 OUP/

[cs15lwi23ahq@ieng6-202]:skill-demo1-data:288$ 



-F command automatically exits if all files can be displayed. Makes it faster to search multiple small folders since you dont have to exit everytime.








