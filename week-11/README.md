
## Week 11 Quiz Questions and Answers

In order to prepare your Week 11 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-11" in your fork of this repo. Then, after all edits have been made/committed, your Week 11 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-11 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 15, Problem 1]
- Question (mphan12-stat660): How are DO loops useful?
- Answer (mphan12-stat660): DO loops process a group of statements repeatedly rather than once. This can greatly reduce the number of statements required for a repetitive calculation. DO loop enables you to achieve the same results with fewer statements.



[Course Textbook Chapter 15, Problem 2]
- Question (mphan12-stat660): 
- Answer (mphan12-stat660):



[Course Textbook Chapter 15, Problem 3]
- Question (mphan12-stat660): How do you decrement a DO loop's index variable?
- Answer (mphan12-stat660): You can decrement a DO loop's index variable by specifying a negative value for the BY clause. For example, the specification in this iterative DO statement decreases the index variable by -1, resulting in values of 5, 4, 3, 2, and 1. 



[Course Textbook Chapter 15, Problem 4]
- Question (mphan12-stat660): 
- Answer (mphan12-stat660):




[Course Textbook Chapter 15, Problem 5]
- Question (mphan12-stat660): Can DO loops be written in PROC statements?
- Answer (mphan12-stat660): No, DO loops are DATA step statements therefore must between written between the DATA and RUN statements.



[Course Textbook Chapter 15, Problem 6]
- Question (mphan12-stat660): When the does the DO statements stop?
- Answer (mphan12-stat660): When the logic becomes FALSE.



[Course Textbook Chapter 15, Problem 7]
- Question (mphan12-stat660): What is Nesting DO loops?
- Answer (mphan12-stat660): Iterative DO statements can be executed within a DO loop. Putting a DO loop within a DO loop is called nesting.  In order for nested DO loops to execute correctly, you must assign a unique index-variable name in each iterative DO statement and END each DO loop with an END statment.



[Course Textbook Chapter 15, Problem 8]
- Question (mphan12-stat660): How does the DO UNTIL statement executes?
- Answer (mphan12-stat660):The DO UNTIL statement executes a DO loop until the expression becomes true.  The DO UNTIL statements enable you to execute statements conditionally and that the iterative DO statement enables you to execute statements a set number of times, unconditionally.


[Course Textbook Chapter 15, Problem 9]
- Question (mphan12-stat660): How does the DO WHILE statement execute?
- Answer (mphan12-stat660):  The DO WHILE statement executes DO loops conditionally. You can use the DO WHILE statement to execute a DO loop while the expression is true.



[Course Textbook Chapter 15, Problem 10]
- Question (mphan12-stat660): What is the difference between DO WHILE and DO UNTIL statements? 
- Answer (mphan12-stat660): The difference between the DO UNTIL and DO WHILE statements is that the DO WHILE expression is evaluated at the top of the DO loop. If the expression is false the first time it is evaluated, the DO loop never executes. 



[Week 11 SAS Recipe: ddl-and-dml-sql-queries]
- Question (mphan12-stat660): 
- Answer (mphan12-stat660):


