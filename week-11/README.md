
## Week 11 Quiz Questions and Answers

In order to prepare your Week 11 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-11" in your fork of this repo. Then, after all edits have been made/committed, your Week 11 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-11 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 15, Problem 1]
- Question (anguyen152-stat660) : When to use DO loops ? 
- Answer (anguyen152-stat660) : When we need to iterate over parameters in an algorithm or indices in an array.



[Course Textbook Chapter 15, Problem 2]
- Question (anguyen152-stat660) : Why dont we need the "BY" increment statement sometimes in our DO loops ? 



[Course Textbook Chapter 15, Problem 3]
- Question (anguyen152-stat660) : Will the year values(1-15) will be included in the final dataset ? 



[Course Textbook Chapter 15, Problem 4]
- Question (anguyen152-stat660) : Why "do year=1990 to 2004;" but the stored value of year is 2005 ? 
- Answer (anguyen152-stat660) : At the end of the 15th iteration of the DO loop, the value for Year is incremented to 2005. Because this value exceeds the stop value, the DO loop ends. At the bottom of the DATA step, the current values are written to the data set.



[Course Textbook Chapter 15, Problem 5]
- Question (anguyen152-stat660) : What's the function of the OUTPUT statement in this case ? 
- Answer (anguyen152-stat660) : The OUTPUT statement overrides the automatic output at the end of the DATA step. On the last iteration of the DO loop, the value of Year, 2004, is written to the data set.



[Course Textbook Chapter 15, Problem 6]
- Question (anguyen152-stat660) : How many observations will the data set Work.Earn contain without the OUTPUT statement ? 



[Course Textbook Chapter 15, Problem 7]
- Question (anguyen152-stat660) :When will nested DO loops work ?



[Course Textbook Chapter 15, Problem 8]
- Question (anguyen152-stat660) : Does "DO WHILE" statement have its condition being evaluated at the bottom of the loop like the "DO UNTIL" statement ? 
- Answer (anguyen152-stat660) : No. DO WHILE loop is evaluated at the top of the loop, you specify the condition that must exist in order to execute the enclosed statements.



[Course Textbook Chapter 15, Problem 9]
- Question (anguyen152-stat660) : What does "gt" in this statement "do until(Capital gt 500000)" mean ?
- Answer (anguyen152-stat660) : "gt" means "greater than"



[Course Textbook Chapter 15, Problem 10]
- Question (anguyen152-stat660) : Does SAS have "DO WHEN" and "DO OVER" loops ?
- Answer (anguyen152-stat660) : No. Using "DO WHILE" and "DO UNTIL" instead



[Week 11 SAS Recipe: ddl-and-dml-sql-queries]
- Question (anguyen152-stat660) : What if we want to change the values of a specific row in the iris dataset ? 


