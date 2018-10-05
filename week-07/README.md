
## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 11, Problem 2]
- Question (whu8-stat660): Will temporary labels or formats that are assigned in a PROC step override permanent labels or formats that are assigned in a DATA step?
- Answer(whu8-stat660): Yes,it will.



[Course Textbook Chapter 11, Problem 6]
- Question (whu8-stat660): When if-then is used, will SAS check each condition even the first condition is already satisfied?
- Answer(whu8-stat660): Yes, SAS will check each if condition even previous condistion is met. 



[Course Textbook Chapter 11, Problem 7]
- Question (whu8-stat660): How can we determin the length of a new variable if there's no LENGTH statement nor assignment statement?
- Answer(whu8-stat660): In this case, the length of the variable's first reference in the DATA step will determin the length.



[Course Textbook Chapter 11, Problem 8]
- Question (whu8-stat660): In the IF-THEN-ELSE statement, can we write 'else' after two 'if-then' statements?
- Answer(whu8-stat660): No,the ELSE statement must immediately follow the IF-THEN statment in the program.



[Course Textbook Chapter 11, Problem 9]
- Question (whu8-stat660): If we want to set the length of a new variable using the LENGTH statement, where should we put it?
- Answer(whu8-stat660): The LENGTH statement must occur before any other reference to the variable in the DATA step.



[Course Textbook Chapter 11, Problem 10]
- Question (whu8-stat660): Can DORP or KEEP statement use in PROC steps?
- Answer(whu8-stat660): No, but you can use the DROP= or KEEP= data set options following a data set name in any DATA or PROC step.



[Week 7 SAS Recipe: print-to-log-with-macro-variables]
- Question (whu8-stat660): What's the meaning of '%put _user_'?
- Answer(whu8-stat660): It prints the names of all user-defined macro variables and their values,possibly along with some automatically generated macro variables.

