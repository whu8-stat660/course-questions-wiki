
## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 11, Problem 2]
- Question (mphan12-stat660): What statement is used to create a variable that adds a variable's sum?
- Answer (mphan12-stat660): To add the result of an expression to an accumulator variable use a sum statement in your DATA step.
- Question (whu8-stat660): Will temporary labels or formats that are assigned in a PROC step override permanent labels or formats that are assigned in a DATA step?
- Answer(whu8-stat660): Yes,it will.
- Question(llopez37-stat660) Will the labels and formats always be determined upon the last one in the program? 



[Course Textbook Chapter 11, Problem 6]
- Question (mphan12-stat660): What is another alternative of writing IF-THEN statement?
- Answer (mphan12-stat660): An alternative control statement in SAS is the SELECT-WHEN statement. The SELECT-WHEN statement enables you to conditionally execute statements based on the value of a single categorical variable.
- Question (whu8-stat660): When if-then is used, will SAS check each condition even the first condition is already satisfied?
- Answer(whu8-stat660): Yes, SAS will check each if condition even previous condistion is met. 
- Question(llopez37-stat660) Would this be the case with an else statement or would it be skipped since the first statement would have been true? 
- Answer (llopez37-stat660) In this case the two if-then statements allow for both steps to process.



[Course Textbook Chapter 11, Problem 7]
- Question (mphan12-stat660): Where should the length statement be written at in DATA step.
- Answer (mphan12-stat660): The length of a variable is determined by its first reference in the DATA step. Therefore the first reference to a new variable made with a LENGTH statement should be placed before the SET or MERGE statement.
- Question (whu8-stat660): How can we determin the length of a new variable if there's no LENGTH statement nor assignment statement?
- Answer(whu8-stat660): In this case, the length of the variable's first reference in the DATA step will determin the length.
- Question(llopez37-stat660) Can you set up different formats and lengths for specific variable names? 



[Course Textbook Chapter 11, Problem 8]
- Question (mphan12-stat660): How would you write similar IF-THEN statement in PROC SQL?
- Question (whu8-stat660): In the IF-THEN-ELSE statement, can we write 'else' after two 'if-then' statements?
- Answer(whu8-stat660): No,the ELSE statement must immediately follow the IF-THEN statment in the program.
- Question(llopez37-stat660)Is else-if required if the only other statement is an otherwise statement? 
- Answer (llopez37-stat660) From what I could find it seems its the proper syntax.



[Course Textbook Chapter 11, Problem 9]
- Question (mphan12-stat660): Why did the LENGTH statement not work?
- Answer (mphan12-stat660): The length of a new variable is determined by the first reference in the DATA step, not by data values. In this case, the length of Type is determined by the value Fixed. The LENGTH statement is in the wrong place; it must occur before any other
reference to the variable in the DATA step.
- Question (whu8-stat660): If we want to set the length of a new variable using the LENGTH statement, where should we put it?
- Answer(whu8-stat660): The LENGTH statement must occur before any other reference to the variable in the DATA step.
- Question(llopez37-stat660) So no matter the length you put, it will stop on the highest length name that exists?
- Answer(llopez37-stat660) Correct, but it seems that with numerical values this could add unnecessary zeros. 



[Course Textbook Chapter 11, Problem 10]
- Question (mphan12-stat660): Why did the drop statement not work in PROC PRINT procedure?
- Answer (mphan12-stat660): You cannot use DROP or KEEP statements in PROC steps.
- Question (whu8-stat660): Can DORP or KEEP statement use in PROC steps?
- Answer(whu8-stat660): No, but you can use the DROP= or KEEP= data set options following a data set name in any DATA or PROC step.
- Question(llopez37-stat660) Is this due to the fact that drop and keep needs to be in the beginning parts of the data step?



[Week 7 SAS Recipe: print-to-log-with-macro-variables]
- Question (mphan12-stat660): What does "%put _user_;" do?
- Answer (mphan12-stat660): Prints out all user-defined macro variable name and their value.
- Question (whu8-stat660): What's the meaning of '%put _user_'?
- Answer(whu8-stat660): It prints the names of all user-defined macro variables and their values,possibly along with some automatically generated macro variables.
- Question(llopez37-stat660) Is the use case for this in order to collaborate with others when it comes to writing code or what is the benefit of printing this directly to the log window? 


