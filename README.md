When running this in Repl.it you should do the following:

Make a file that is simply called ".replit" 
In this file put the following commands:
run = "bash run_button.sh"
language = "java10"

Then make a file called "run_button.sh"
In this file put the following commands:
javac *.java
java Hello

Now the Run button SHOULD run Hello.java as expected
