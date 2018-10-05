
## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 11, Problem 2]
* Question (yli110-stat660): What is the difference between assigning labels and formats temporarily and permanently?
* Answer (yli110-stat660): Temporary labels and formats are applicable only for the duration of the step. If you assign temporary labels or formats with a PROC step, they override any permanent labels and formats that were assigned during the DATA step.



[Course Textbook Chapter 11, Problem 6]
* Question (yli110-stat660): What does the statement *count +1* do?
* Answer (yli110-stat660): it adds one to the variable *count* for each observation as SAS processes the step.



[Course Textbook Chapter 11, Problem 7]
* Question (yli110-stat660): What are the possilbe ways to determine the length of a new variable?



[Course Textbook Chapter 11, Problem 8]
* Question (yli110-stat660): What is the advantage to use IF-THEN/ELSE instead of repeated IF-THEN?
* Answer (yli110-stat660): ELSE executes only if the previous IF-THEN/ELSE statement is false, thus avoids to execute each IF statement in order.



[Course Textbook Chapter 11, Problem 9]
* Question (yli110-stat660): What is the correct position of LENGTH statement if you want to define the length of a new variable?



[Course Textbook Chapter 11, Problem 10]
* Question (yli110-stat660): What are the differences between DROP or KEEP statement and DROP= or KEEP= data set options?



[Week 7 SAS Recipe: print-to-log-with-macro-variables]
* Question (yli110-stat660): What is the difference when dereferencing a macro variable by using *&varialbe.* and *&=variable.*

