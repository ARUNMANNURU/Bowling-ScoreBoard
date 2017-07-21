# Bowling-ScoreBoard
Using Shell Scripting


(SC1) Write a shell script that accepts the name of a bowler on the command line. If the bowler does not put the name on the command line, your script should ask him for it. Once the name has been entered (either from the command line or interactively), the name is echoed back to the screen. [command line variables, echo, if, ]
 

b. (SC2) Amend script 1 to give an error message if no name is given on the command line or interactively. The error message should have a “ usage” suggestion [if]

 

c. (SC3) Amend Script 2  to prevent the user from not entering a name. The script should insist that a name is entered. [while]

 

d. (SC4) Amend Script 3 to prevent the user for exiting the script before a name is entered via standard interrupts [trap].

 

e. (SC5) Create another script that accepts scores from the one or two balls thrown and reports back to you the result of that that frame. The script should do data checking to make sure that the numbers entered are valid [0-9] and do not add up to more than 10. The script can also accept an “X” or “x” to indicate the bowler has thrown a strike (only on the first ball) . If after two balls the bowler’s score adds up to 10 then the script should report back that you rolled a “spare” or “/”  [let]

 

f. (SC6) Amend script 5 to allow the process in script 5 to happen 9 times sequentially. Capture a cumulative score of each frame and report it to the user as he bowls. [while, function, variable array]

 

g. (SC7) Amend Script 6 to now capture the first 9 frames score in full accordance with the rules of bowling. You must now account for the special rules for spares and strikes.  Please see my explanation above…

 

h. (SC8) Amend Script 7 and add a 10th frame function to allow for up to 3 balls to be thrown in a special 10th frame handler. Please see my explanation of the 10th frame above….

 

i. (SC9) Amend the script 8 to eliminate the alphanumeric input and present the user with a menu of choices for frames 1-9 and the 10th frame. Remember, you menu choices may change depending if you are throwing the 1st, 2nd or (in the 10th frame) 3rd ball. [select]

 

j. (SC10) Combine Script 4 and script 9 for an interactive scoring session that captures a bowler’s name, and each of his rolls and then computes his final score. Please then add a function to redirect the score to a file call bowler.txt so we can look up the scores later on. bowler.txt should have the name in column 1, the date in column 2 (please use the “date” command to retrieve today’s date) followed by 21 columns each representing the score for each ball thrown with the final score in the 23rd column. All data should be separated by a [Tab] [redirect]

 

k. 
write a nawk script or command that will find the bowler with the most strikes from bowlers.txt.

write a nawk script or command that will find the bowler with the best average from bowlers.txt 
