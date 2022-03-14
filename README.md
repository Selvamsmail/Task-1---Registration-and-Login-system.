Task 1 - Registration and Login system.

Basic features:
Email:
The program contains the features to find the basic syntax of an email and would not register if the syntax dose not match.
(e.g.) sherlock@gmail.com, it does not ask for a Gmail or Yahoo though.
The program also requires "@" and "." symbols as mandatory for the Emails.

Password:
Just like the Email, the password also has quality set of rules, the total character should be at least of 5 in length and
16 at a max. It also askes for the password with special characters and also casing like upper and lower.

Code Blocks:
The program has 4 functions:
register ()
login ()
forgot ()
fileret ()

register ():
This function was the critical part where all the rule had to be considered and in some platforms like co-lab,
The file that was created to store the data got deleted in an hour or so... in that case. The program creates the file,
Throwing no error. Also when the file is created for the first time the program cannot immediately access the file.
So after registering the data the program basically quits. That’s how it has been designed as it will throw an error
If the file can’t be accessed by other functions.

login ():
This basically is a function to check the stored data and retrieve the password information for the corresponding Email.
it also gives a feedback if the file is not found and also suggests to start registration if the user will be interested.

forgot ():
This function's job is to find the password unpacking the txt, for the corresponding Email.
This function also takes the user to the registration part if the details are not found.

fileret ():
The function is used by two other functions like (login and forgot), it has nothing to do with the user.
This function's basic duty is to retrieve the data stored in the txt file, converts to dictionary and
Share the results with other functions.

Conclusion:
The program is an error free one as it was tested multiple times on co lab py-charm etc..
The resulted output was worth the time and efforts
The project was an interesting one had a good brush-up through all the learned skills.
