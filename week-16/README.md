
## Week 16 Quiz Questions and Answers

In order to prepare your Week 16 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-16" in your fork of this repo. Then, after all edits have been made/committed, your Week 16 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-16 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 20, Problem 1]
* Question (yli110-stat660): How do you specify the record from which values are read if information for one observation was spread out over several records?
* Answer (yli110-stat660): line pointer controls



[Course Textbook Chapter 20, Problem 2]
* Question (yli110-stat660): What is the purpose of forward slash (/) line pointer control?
* Answer (yli110-stat660): read multiple records sequentially.



[Course Textbook Chapter 20, Problem 3]
* Question (yli110-stat660): What is the purpose of #n line pointer control?
* Answer (yli110-stat660): read multiple records non-sequentially.



[Course Textbook Chapter 20, Problem 4]
* Question (yli110-stat660): Where should you place the (/) line pointer control?



[Course Textbook Chapter 20, Problem 5]
* Question (yli110-stat660): What is the difference between #n, @n and +n?



[Course Textbook Chapter 20, Problem 6]
* Question (yli110-stat660): What is the reason that the number of records for each observation should be the same?



[Course Textbook Chapter 20, Problem 7]
* Question (yli110-stat660): When do you use the & modifier for modified list input?



[Course Textbook Chapter 20, Problem 8]
* Question (yli110-stat660): What are the two kinds of line pointer controls?



[Course Textbook Chapter 20, Problem 9]
* Question (yli110-stat660): What is the purpose of using (:) modifier in modified list input?



[Course Textbook Chapter 21, Problem 1]
* Question (yli110-stat660): What is the major difference between (@) and (@@)?
* Answer (yli110-stat660): @@ holds a record across multiple iterations of DATA steps until the end of the record is reached, while @ releases a record when control returns to the top of the DATA step.



[Course Textbook Chapter 21, Problem 2]
* Question (yli110-stat660): When does @@ release a record?
* Answer (yli110-stat660): the input pointer moves past the end of the record, or until an INPUT statement without line-hold specifiers executed.



[Course Textbook Chapter 21, Problem 3]
* Question (yli110-stat660): When does @ release a record?
* Answer( (yli110-stat660): @ doesn't toggle on and off, if another INPUT without tailing @ executed, the hold is still effective. It will automatically release the record when control returns to the top of the DATA step.



[Course Textbook Chapter 21, Problem 4]
* Question (yli110-stat660): Where should you put @ or @@?



[Course Textbook Chapter 21, Problem 6]
* Question (yli110-stat660): How do you use OUTPUT statement to control the observation outputted to the SAS data file?



[Course Textbook Chapter 21, Problem 10]
* Question (yli110-stat660): What does MISSOVER option in the INFILE statement do?



[Week 16 SAS Recipe: summarize-data-using-proc-report]
* Question (yli110-stat660): How do you use PROC REPORT to summarize data? What is the difference between PROC REPORT and PROC SQL when summarizing data?


