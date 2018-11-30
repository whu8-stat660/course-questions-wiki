
## Week 15 Quiz Questions and Answers

In order to prepare your Week 15 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-15" in your fork of this repo. Then, after all edits have been made/committed, your Week 15 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-15 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 18, Problem 1]
- Question (jduan10-stat660): What is the default delimiter in list input.?
- Answer (jduan10-stat660): Blank is default.
- Question (mphan12-stat660):  What is the default delimiter "dlm"?
- Answer (mphan12-stat660): Blank spaces.



[Course Textbook Chapter 18, Problem 2]
- Question (jduan10-stat660): Why column input is an appropriate choice for first field?
- Answer (jduan10-stat660): because the values can be read as standard character values and are located in fixed columns.
- Question (mphan12-stat660):  What are the different input style?



[Course Textbook Chapter 18, Problem 4]
- Question (jduan10-stat660): Does “length” step need to follow the “infile” step?
- Question (mphan12-stat660):  What is the difference between input FirstName $ 1-4 and input FirstName $?



[Course Textbook Chapter 18, Problem 5]
- Question (jduan10-stat660): How do SAS scan data with list input?
- Answer (jduan10-stat660): List input causes SAS to scan the input lines for values rather than reading from specific columns.
- Question (mphan12-stat660):  What does the dlm statement do?



[Course Textbook Chapter 18, Problem 7]
- Question (jduan10-stat660): When does SAS stop reading raw data?
- Answer (jduan10-stat660): SAS reads until it encounters two consecutive blanks, the defined length of the variable, or the end of the input line, whichever comes first.
- Question (mphan12-stat660):  How does SAS know to continue onto the next line?
- Answer (mphan12-stat660):  SAS reads the first field until it encounters a blank space. The blank space indicates the end of the field, and the data value is assigned to the program data vector for the first variable in the INPUT statement.



[Course Textbook Chapter 18, Problem 8]
- Question (jduan10-stat660): What values are suitable for using list input?
- Answer (jduan10-stat660): The last field values.
- Question (mphan12-stat660):  What values are suitable for using list input?
- Answer (mphan12-stat660):  The last field values.



[Course Textbook Chapter 18, Problem 10]
- Question (jduan10-stat660): Can we specify a range of variables using formatted input?
- Question (mphan12-stat660): When are variable attributes defined? 
- Answer (mphan12-stat660):  When the variable is first encountered in the DATA step.



[Week 15 SAS Recipe: summarize-data-using-sql]
- Question (jduan10-stat660): What is the function of  “*” in the PROC SQL statement?
- Question (mphan12-stat660):  What does the statement "having" in proc sql do?


