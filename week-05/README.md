
## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 6, Problem 1]
- Question (anguyen152-stat660): What's fileref and what's filename ? 
- Answer(anguyen152-stat660): You assign a fileref by using a FILENAME statement in the same way that you assign a libref by using a LIBNAME statement.



[Course Textbook Chapter 6, Problem 2]
- Question (anguyen152-stat660): How to cancel a FILENAME statement ? 



[Course Textbook Chapter 6, Problem 6]
- Question (anguyen152-stat660): What does "infile" statement do ? What does "input" statement do ? 
- Answer(anguyen152-stat660):  The INFILE statement opens an external file for input or, if the file is already open, makes it the current input file. Meanwhile, the INPUT statement creates a variable using the name that you assign to each field. 



[Course Textbook Chapter 6, Problem 7]
- Question (anguyen152-stat660):  What's the dollar signs ($) used for in "input" statement ? 
- Answer(anguyen152-stat660): The dollar sign ($) identifies the variable type as character (if the variable is numeric, then nothing appears here).



[Course Textbook Chapter 6, Problem 8]
- Question (anguyen152-stat660): Do we need any SAS statement to redefine the values like that ? 



[Week 5 SAS Recipe: basic_recipe_for_creating_analytic_datasets]
- Question (anguyen152-stat660): How to distinguish "keep" and "retain" ? 
- Answer(anguyen152-stat660): "retain" is used to set variable order, and "keep" is used to explicitly list the columns to keep in output.



[Week 5 SAS Recipe: adv_recipe_for_creating_analytic_datasets]
- Question (anguyen152-stat660): Why do I see some SQL statements here ? Is it better to use PROC SQL ? 
- Answer(anguyen152-stat660): SQL is one of the many languages built into the SAS System. PROC SQL is a powerful Base SAS Procedure that combines the functionality of DATA and PROC steps into a single step. That's why we can use SQL statements under "PROC SQL". 




