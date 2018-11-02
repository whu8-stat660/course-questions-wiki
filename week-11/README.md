
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
- Question (whu8-stat660):Can DO loops be used in PROC steps?
- Answer (whu8-stat660):No.



[Course Textbook Chapter 15, Problem 2]
- Question (mphan12-stat660): What are the possible expression of specification of index-variable?
- Answer (mphan12-stat660):Possible expressions are '='/'until'/'while' condition expressions.
- Question (whu8-stat660):What determins the number of iterations?
- Answer (whu8-stat660):The DO statement's stop valued determins the number of iterations.



[Course Textbook Chapter 15, Problem 3]
- Question (mphan12-stat660): How do you decrement a DO loop's index variable?
- Answer (mphan12-stat660): You can decrement a DO loop's index variable by specifying a negative value for the BY clause. For example, the specification in this iterative DO statement decreases the index variable by -1, resulting in values of 5, 4, 3, 2, and 1. 
- Question (whu8-stat660):What are the possible expression of specification of index-variable?
- Answer (whu8-stat660):It could be a value ranges or 'until'/'while' condition expression.



[Course Textbook Chapter 15, Problem 4]
- Question (mphan12-stat660): What is the difference between the stored index value and stopped value of index?
- Question (whu8-stat660):Is the stored index value always the same as the stopped value of index?



[Course Textbook Chapter 15, Problem 5]
- Question (mphan12-stat660): Can DO loops be written in PROC statements?
- Answer (mphan12-stat660): No, DO loops are DATA step statements therefore must between written between the DATA and RUN statements.
- Question (whu8-stat660):What's the difference bewtween last index stored value and last output index value?



[Course Textbook Chapter 15, Problem 6]
- Question (mphan12-stat660): When the does the DO statements stop?
- Answer (mphan12-stat660): When the logic becomes FALSE.
- Question (whu8-stat660):Is the number of observations based on the number of times the OUTPUT statement executes?
- Answer (whu8-stat660):Correct.



[Course Textbook Chapter 15, Problem 7]
- Question (mphan12-stat660): What is Nesting DO loops?
- Answer (mphan12-stat660): Iterative DO statements can be executed within a DO loop. Putting a DO loop within a DO loop is called nesting.  In order for nested DO loops to execute correctly, you must assign a unique index-variable name in each iterative DO statement and END each DO loop with an END statment.
- Question (whu8-stat660):What's the use of nested Do loops?



[Course Textbook Chapter 15, Problem 8]
- Question (mphan12-stat660): How does the DO UNTIL statement executes?
- Answer (mphan12-stat660):The DO UNTIL statement executes a DO loop until the expression becomes true.  The DO UNTIL statements enable you to execute statements conditionally and that the iterative DO statement enables you to execute statements a set number of times, unconditionally.
- Question (whu8-stat660):Where is the do until condition evaluated in the loop?
- Answer (whu8-stat660):It's evaluated at the bottom of the loop,so the enclosed statement are always executed at least once.



[Course Textbook Chapter 15, Problem 9]
- Question (mphan12-stat660): How does the DO WHILE statement execute?
- Answer (mphan12-stat660):  The DO WHILE statement executes DO loops conditionally. You can use the DO WHILE statement to execute a DO loop while the expression is true.
- Question (whu8-stat660):What's the difference between DO UNTIL and DO WHILE conditon?
- Answer (whu8-stat660):The DO UNTIL condition is evaluated at the bottom of the loop while the DO WHILE loop is evaluated at the top of the loop.



[Course Textbook Chapter 15, Problem 10]
- Question (mphan12-stat660): What is the difference between DO WHILE and DO UNTIL statements? 
- Answer (mphan12-stat660): The difference between the DO UNTIL and DO WHILE statements is that the DO WHILE expression is evaluated at the top of the DO loop. If the expression is false the first time it is evaluated, the DO loop never executes. 
- Question (whu8-stat660):Can we only put a equal sign in the DO UNTIL and DO WHILE condition?
- Answer (whu8-stat660):I don't think so.



[Week 11 SAS Recipe: ddl-and-dml-sql-queries]
- Question (mphan12-stat660): What is DDL and DML?
- Answer (mphan12-stat660): Data-definition-language (DDL) task, such as defining, obtaining, or modifying column information for a table.  And data-manipulation-language (DML) task, such as obtaining, creating, or modifying the rows of data in a table.
- Question (whu8-stat660):What is DDL and DML?
- Answer (whu8-stat660):DDL is the data-definition language, meaning they define, obtain, or modify column information in a table or delete a table entirely. DML is the data-manipulation language,meaning they obtain, create, modify or delete rows of data in a table.


