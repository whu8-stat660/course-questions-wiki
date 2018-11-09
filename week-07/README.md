
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
- Question (anguyen152-stat660): What types of formats can we assign to a variable in SAS ? 
- Question (jduan10-stat660): If we assign temporary labels or formats within a PROC step, will they override any permanent labels or formats during the DATA step?
* Question (yli110-stat660): What is the difference between assigning labels and formats temporarily and permanently?
* Answer (yli110-stat660): Temporary labels and formats are applicable only for the duration of the step. If you assign temporary labels or formats with a PROC step, they override any permanent labels and formats that were assigned during the DATA step.



[Course Textbook Chapter 11, Problem 6]
- Question (mphan12-stat660): What is another alternative of writing IF-THEN statement?
- Answer (mphan12-stat660): An alternative control statement in SAS is the SELECT-WHEN statement. The SELECT-WHEN statement enables you to conditionally execute statements based on the value of a single categorical variable.
- Question (whu8-stat660): When if-then is used, will SAS check each condition even the first condition is already satisfied?
- Answer(whu8-stat660): Yes, SAS will check each if condition even previous condistion is met. 
- Question(llopez37-stat660) Would this be the case with an else statement or would it be skipped since the first statement would have been true? 
- Answer (llopez37-stat660) In this case the two if-then statements allow for both steps to process.
- Question (anguyen152-stat660): Do we have to put a ";" after an if-then statement that's followed by a "do-end" statement?  
- Answer (anguyen152-stat660): No, the "do" and "then" steps are not separated by a ";"
- Question (jduan10-stat660): What’s the order of logical comparisons?
- Answer (jduan10-stat660): Logical comparisons that are enclosed in parentheses are evaluated as true or false before they are compared to other expressions. 
* Question (yli110-stat660): What does the statement *count +1* do?
* Answer (yli110-stat660): it adds one to the variable *count* for each observation as SAS processes the step.



[Course Textbook Chapter 11, Problem 7]
- Question (mphan12-stat660): Where should the length statement be written at in DATA step.
- Answer (mphan12-stat660): The length of a variable is determined by its first reference in the DATA step. Therefore the first reference to a new variable made with a LENGTH statement should be placed before the SET or MERGE statement.
- Question (whu8-stat660): How can we determin the length of a new variable if there's no LENGTH statement nor assignment statement?
- Answer(whu8-stat660): In this case, the length of the variable's first reference in the DATA step will determin the length.
- Question(llopez37-stat660) Can you set up different formats and lengths for specific variable names? 
- Question (anguyen152-stat660): Are the "Length" values numeric all the time ? 
- Question (jduan10-stat660): Can we use LENGTH statement after the first value is referenced in the DATA step?
* Question (yli110-stat660): What are the possilbe ways to determine the length of a new variable?



[Course Textbook Chapter 11, Problem 8]
- Question (mphan12-stat660): How would you write similar IF-THEN statement in PROC SQL?
- Question (whu8-stat660): In the IF-THEN-ELSE statement, can we write 'else' after two 'if-then' statements?
- Answer(whu8-stat660): No,the ELSE statement must immediately follow the IF-THEN statment in the program.
- Question(llopez37-stat660)Is else-if required if the only other statement is an otherwise statement? 
- Answer (llopez37-stat660) From what I could find it seems its the proper syntax.
- Question (anguyen152-stat660): Can we use "and" for multiple conditions in if-then statement ?
- Question (jduan10-stat660): How to test the conditional logic?
- Answer (jduan10-stat660): Use the PUT statement.
* Question (yli110-stat660): What is the advantage to use IF-THEN/ELSE instead of repeated IF-THEN?
* Answer (yli110-stat660): ELSE executes only if the previous IF-THEN/ELSE statement is false, thus avoids to execute each IF statement in order.



[Course Textbook Chapter 11, Problem 9]
- Question (mphan12-stat660): Why did the LENGTH statement not work?
- Answer (mphan12-stat660): The length of a new variable is determined by the first reference in the DATA step, not by data values. In this case, the length of Type is determined by the value Fixed. The LENGTH statement is in the wrong place; it must occur before any other
reference to the variable in the DATA step.
- Question (whu8-stat660): If we want to set the length of a new variable using the LENGTH statement, where should we put it?
- Answer(whu8-stat660): The LENGTH statement must occur before any other reference to the variable in the DATA step.
- Question(llopez37-stat660) So no matter the length you put, it will stop on the highest length name that exists?
- Answer(llopez37-stat660) Correct, but it seems that with numerical values this could add unnecessary zeros. 
- Question (anguyen152-stat660): What if there are 2 length statements for 1 same variable in a program ? 
- Question (jduan10-stat660): Why do we need to use a $ before the variable name?
- Answer (jduan10-stat660): Because TestLength is a character variable.
* Question (yli110-stat660): What is the correct position of LENGTH statement if you want to define the length of a new variable?



[Course Textbook Chapter 11, Problem 10]
- Question (mphan12-stat660): Why did the drop statement not work in PROC PRINT procedure?
- Answer (mphan12-stat660): You cannot use DROP or KEEP statements in PROC steps.
- Question (whu8-stat660): Can DORP or KEEP statement use in PROC steps?
- Answer(whu8-stat660): No, but you can use the DROP= or KEEP= data set options following a data set name in any DATA or PROC step.
- Question(llopez37-stat660) Is this due to the fact that drop and keep needs to be in the beginning parts of the data step?
- Question (anguyen152-stat660): In a dataset of 10 variables, if we use "keep" statement to keep 3 variables , will the other 7 variables be dropped ?
- Answer (anguyen152-stat660): Yes, the other 7 variables will not be written out. The KEEP statement causes a DATA step to write only the variables that you specify to one or more SAS data sets. The KEEP statement applies to all SAS data sets that are created within the same DATA step and can appear anywhere in the step. If no KEEP or DROP statement appears, all data sets that are created in the DATA step contain all variables. 
- Question (jduan10-stat660): Can we use DROP or KEEP statement in the SAS procedure steps?
* Question (yli110-stat660): What are the differences between DROP or KEEP statement and DROP= or KEEP= data set options?



[Week 7 SAS Recipe: print-to-log-with-macro-variables]
- Question (mphan12-stat660): What does "%put _user_;" do?
- Answer (mphan12-stat660): Prints out all user-defined macro variable name and their value.
- Question (whu8-stat660): What's the meaning of '%put _user_'?
- Answer(whu8-stat660): It prints the names of all user-defined macro variables and their values,possibly along with some automatically generated macro variables.
- Question(llopez37-stat660) Is the use case for this in order to collaborate with others when it comes to writing code or what is the benefit of printing this directly to the log window? 
- Question (anguyen152-stat660): What does a %put macro do ? 
- Answer (anguyen152-stat660): It's the simplest way to display macro variable values, which writes text to the SAS log. 
- Question (jduan10-stat660): Do we need to write Quit or Run in the macro demand?
* Question (yli110-stat660): What is the difference when dereferencing a macro variable by using *&varialbe.* and *&=variable.*


