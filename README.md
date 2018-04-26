# Wk4practice_project
practice project from Python Programming Essentials

1. Build a helper function name_to_number(name) that converts the string name into a number between 0 and 4.  This function should use a sequence of if/elif/else clauses.  You can use conditions of the form name == "paper, etc to distinguish the cases.  To make debugging your code easier, we suggest including a final else clause that catches cases when name does not match any of the 5 correct inputs (Rock = 0, Spock = 1, paper = 2, lizard = 3, scissors = 4) and prints an appropriate error message.  

2. Next, you should build a second helper function number_to_name(number) that converts a number in the range 0 - 4 into its corresponding name as a string. Again, we suggest including a final else clause that catches cases when number is not in the correct range.

3. Implement the first part of the main function rpsls(player_choice).  Print a blank line (to separate consecutive games followed by a line with an appropriate message describing the player's choice.  Then compute the number player_number between 0 and 4 corresponding to the player's choice by calling the helper function name_to_number() using player_choice.

4. Implement the second part of rpsls() that generates the computer's guess and prints out an appropreate message for that guess.  Inparticular, compute a randome number comp_number between 0 and 4 that corresponds to the computer's guess using the function random.randrange().  We suggest experimenting with randrange in a separate CodeSkulptor window before deciding on how to call it to make sure that you do not accidentally generate numbers in the wrong range.  Then compute the name comp_choice corresponding to the computer's number using the finction number_to_name() and print an appropriate message with the computer's choice to the console.

5. Implement the last part of rpsls() that determines and prints out the winner.  Specifically, compute the difference between comp_number and player_number taken module 5.  Then write an if/elif/else statement whose conditions test the various possible values of the difference and then prints an appropriate message concerning the winner.  If you have trouble deriving the conditions for the clauses of this if/elif/else statement.

