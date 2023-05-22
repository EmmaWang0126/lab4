#Reproduce the Task from Timing Tasks                                        
4. Log into ieng6                         
![image]()                                    
Type in ```cs15lsp23xx@ieng6.ucsd.edu``` and then your password.             
Then ```<enter>```. 

5.Clone your fork of the repository from your github account:   
![image]()
Enter ```git clone``` in the terminal, then go to github and find the file you need to clone, click ```code``` and copy paste the URL to the command line 
right after the ```git clone```. Then ```<enter>```. 

6.Run the tests, demonstrating they they fail
![image]()            
Type in the Junit test code, so cd into lab7, copy from the week3 meterial **crtl-c**, and **ctrl-v** the test code to the command line, for the end of java part, change the  to ListExamplesTests

```
# code block
javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java
java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ListExamplesTests
```

7.Edit the code file to fix the failing test

8.Run the tests, demonstrating that they now succeed

9.Commit and push kthe resulting change to your Github account(you can pick any cimmit message!)
