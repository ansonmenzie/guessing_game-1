My game has five questions about my dog Finn.
The five questions are stored in an array.
A second array stores the answers to each question.

Using a for loop, the user is prompted to respond to each question.
The for loop calls a few functions.  the functions do the following:
1. check for garbage answers and throw an alert when garbage is entered.  Also, rewinds loop by 1 so question is reasked.
2. checks (non garbage) answers for whether they are correct.  if asnwer is correct, correct message is displayed; if not, incorrect message is displayed.  The way it checks for a correct answer is matching the index of the question array with the index of the answer array and check for equality.

Existing bug in game - if garbage answer provided on last question, doesnt rewind to ask for another answer.
