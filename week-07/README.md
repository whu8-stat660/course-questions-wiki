
## Week 7 Quiz Questions and Answers

In order to prepare your Week 7 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-7" in your fork of this repo. Then, after all edits have been made/committed, your Week 7 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-7 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 11, Problem 2]
- Question (anguyen152-stat660): What types of formats can we assign to a variable in SAS ? 



[Course Textbook Chapter 11, Problem 6]
- Question (anguyen152-stat660): Do we have to put a ";" after an if-then statement that's followed by a "do-end" statement?  
- Answer (anguyen152-stat660): No, the "do" and "then" steps are not separated by a ";"



[Course Textbook Chapter 11, Problem 7]
- Question (anguyen152-stat660): Are the "Length" values numeric all the time ? 



[Course Textbook Chapter 11, Problem 8]
- Question (anguyen152-stat660): Can we use "and" for multiple conditions in if-then statement ?



[Course Textbook Chapter 11, Problem 9]
- Question (anguyen152-stat660): What if there are 2 length statements for 1 same variable in a program ? 



[Course Textbook Chapter 11, Problem 10]
- Question (anguyen152-stat660): In a dataset of 10 variables, if we use "keep" statement to keep 3 variables , will the other 7 variables be dropped ?
- Answer (anguyen152-stat660): Yes, the other 7 variables will not be written out. The KEEP statement causes a DATA step to write only the variables that you specify to one or more SAS data sets. The KEEP statement applies to all SAS data sets that are created within the same DATA step and can appear anywhere in the step. If no KEEP or DROP statement appears, all data sets that are created in the DATA step contain all variables. 



[Week 7 SAS Recipe: print-to-log-with-macro-variables]
- Question (anguyen152-stat660): What does a %put macro do ? 
- Answer (anguyen152-stat660): It's the simplest way to display macro variable values, which writes text to the SAS log. 


