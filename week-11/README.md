
## Week 11 Quiz Questions and Answers

In order to prepare your Week 11 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-11" in your fork of this repo. Then, after all edits have been made/committed, your Week 11 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-11 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 15, Problem 1]
* Question (yli110-stat660): Can DO loops be used with PROC step?
* Answer (yli110-stat660): No, DO loops are DATA step statements, and cannot be conjuaged with PROC steps.



[Course Textbook Chapter 15, Problem 2]
* Question (yli110-stat660): How is the number of iterations determined in the DO statement?



[Course Textbook Chapter 15, Problem 3]
* Question (yli110-stat660): How do you avoid infinite loops in DO loops?



[Course Textbook Chapter 15, Problem 4]
* Question (yli110-stat660): How does DO loop stopy?
* Answer (yli110-stat660): When the index variable has a value that exceeds the stop value in do loop, the loop will stop. However the index variable will be stored as it's latest number.



[Course Textbook Chapter 15, Problem 5]
* Question (yli110-stat660): How does the OUTPUT in DO loop change the stored value of the index variable?
* Answer (yli110-stat660): Without the OUTPUT statement, index variable exceeds the stop value, and the loop writes out the observation with which the index has already exceeds the stop value. With OUTPUT statement, on the other hand, writes observations out at end of each iteration, thus the last observation will include the index variable with the stop value.



[Course Textbook Chapter 15, Problem 6]
* Question (yli110-stat660): How does SAS determine the number of observations written out in the OUTPUT statement in DO loop?



[Course Textbook Chapter 15, Problem 7]
* Question (yli110-stat660): When do you use nested DO loops?



[Course Textbook Chapter 15, Problem 8]
* Question (yli110-stat660): What is the difference between DO UNTIL and DO WHILE?



[Course Textbook Chapter 15, Problem 9]
* Question (yli110-stat660): How do you manipulate DO UNTIL and DO WHILE for them to produce the same results?



[Course Textbook Chapter 15, Problem 10]
* Question (yli110-stat660): What the difference of DO UNITL and DO WHILE in terms of the number of executions of the loop?



[Week 11 SAS Recipe: ddl-and-dml-sql-queries]
* Question (yli110-stat660)


