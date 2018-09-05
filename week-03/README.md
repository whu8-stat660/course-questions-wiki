
## Week 3 Quiz Questions and Answers

In order to prepare your Week 3 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-3" in your fork of this repo. Then, after all edits have been made/committed, your Week 3 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-3 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 5, Problem 1]
- Question (mphan12-stat660): Why is the label option turned on, yet the columns are still column names rather than label names in the table?



[Course Textbook Chapter 5, Problem 3]
- Question (mphan12-stat660): What is another way of select RANCH, SPLIT, or TWOSTORY?
- Answer (mphan12-stat660): Where style = 'RANCH' or style = 'SPLIT' or style = 'TWOSTORY'



[Course Textbook Chapter 5, Problem 4]
- Question (mphan12-stat660): How is the data set saved if out=calc instead of out= work.calc?
- Answer (mphan12-stat660): The calc data set will still be created in the temporary directory work.



[Course Textbook Chapter 5, Problem 7]
- Question (mphan12-stat660): What correction must be made to have this script run without error?
- Answer (mphan12-stat660): The code should read: 
- - proc sort data=clinic.diabetes;
 - - - by age;
- - run;
- - proc print data=clinic.diabetes;
 - - - var age height weight pulse;
 - - - where sex='F';
- - run;



[Course Textbook Chapter 5, Problem 9]
- Question (mphan12-stat660): What should you consider when writing mathematical expression?
- Answer (mphan12-stat660): Order of operation matters, apply PEMDAS rule in SAS. 



[Course Textbook Chapter 5, Problem 10]
- Question (mphan12-stat660): What does PROC PRINT display by default?
- Answer (mphan12-stat660): PROC PRINT displays all observations and variables in the data set, a column for observation numbers on the far left, and variables in the order in which they occur in the data set.



[Week 3 SAS Recipe: recipe_to_check_for_duplicates]



[Week 3 SAS Recipe: recipe_for_sorting_data]



[Week 3 SAS Recipe: recipe_for_printing_values]


