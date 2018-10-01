
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



[Course Textbook Chapter 11, Problem 6]
- Question (mphan12-stat660): What is another alternative of writing IF-THEN statement?
- Answer (mphan12-stat660): An alternative control statement in SAS is the SELECT-WHEN statement. The SELECT-WHEN statement enables you to conditionally execute statements based on the value of a single categorical variable.



[Course Textbook Chapter 11, Problem 7]
- Question (mphan12-stat660): Where should the length statement be written at in DATA step.
- Answer (mphan12-stat660): The length of a variable is determined by its first reference in the DATA step. Therefore the first reference to a new variable made with a LENGTH statement should be placed before the SET or MERGE statement.



[Course Textbook Chapter 11, Problem 8]
- Question (mphan12-stat660): How would you write similar IF-THEN statement in PROC SQL?
- Answer (mphan12-stat660): 



[Course Textbook Chapter 11, Problem 9]
- Question (mphan12-stat660): Why did the LENGTH statement not work?
- Answer (mphan12-stat660): The length of a new variable is determined by the first reference in the DATA step, not by data values. In this case, the length of Type is determined by the value Fixed. The LENGTH statement is in the wrong place; it must occur before any other
reference to the variable in the DATA step.



[Course Textbook Chapter 11, Problem 10]
- Question (mphan12-stat660): Why did the drop statement not work in PROC PRINT procedure?
- Answer (mphan12-stat660): You cannot use DROP or KEEP statements in PROC steps.



[Week 7 SAS Recipe: print-to-log-with-macro-variables]
- Question (mphan12-stat660): What does "%put _user_;" do?
- Answer (mphan12-stat660): Prints out all user-defined macro variable name and their value.


