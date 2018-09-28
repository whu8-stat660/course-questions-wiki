
## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 7, Problem 1]
- Question (anguyen152-stat660): What does SAS create during compilation phase ?
- Answer (anguyen152-stat660) : At the bottom of the DATA step — in most cases, when a RUN statement is encountered — the compilation phase is complete, and the descriptor portion of the new SAS data set is created.



[Course Textbook Chapter 7, Problem 2]
- Question (anguyen152-stat660): Will SAS point out the exact syntax errors (if exist) for me ?  
- Answer (anguyen152-stat660) : If SAS can interpret a syntax error, the DATA step compiles and executes; if SAS cannot interpret the error, the DATA step compiles but doesn't execute. 



[Course Textbook Chapter 7, Problem 3]
- Question (anguyen152-stat660): How does SAS process records with missing values ? 
- Answer (anguyen152-stat660): SAS assigns missing values to prevent problems from arising. If you use a missing value in an arithmetic calculation, SAS sets the result of that calculation to missing. Then, if you use that result in another calculation, the next result is also missing. This action is called propagation of missing values. SAS prints notes in the log to notify you which arithmetic expressions have missing values and when they were created; however, processing continues.



[Course Textbook Chapter 7, Problem 4]
- Question (anguyen152-stat660): Why the values of the remaining variables are set "missing" ?



[Course Textbook Chapter 7, Problem 5]
- Question (anguyen152-stat660): Will SAS still run after errors ?



[Course Textbook Chapter 7, Problem 6]
- Question (anguyen152-stat660): What occurs at the end of an iteration of the DATA step?



[Week 6 SAS Recipe: obtain-column-information]
- Question (anguyen152-stat660): Can we print out the dataset and then choose the names of the columns manually ? 



