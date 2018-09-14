
## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 6, Problem 1]
- Question (mphan12-stat660): When fileref is used to specify a delimited file to import, what is the default logical record length (LRECL) and what is the maximum.
- Answer (mphan12-stat660): The default LRECL is 256 and the maximum value that the IMPORT procedure supports is 32767.



[Course Textbook Chapter 6, Problem 2]
- Question (mphan12-stat660): What is fileref?
- Answer (mphan12-stat660): A fileref is a SAS name that is associated with the physcial location of the output file. To assign fileref, use the FILENAME statement.


[Course Textbook Chapter 6, Problem 6]
- Question (mphan12-stat660): What are the two statements used to read in raw data?
- Answer (mphan12-stat660): The INFILE and INPUT statements are used in the DATA step for read in raw data.


[Course Textbook Chapter 6, Problem 7]
- Question (mphan12-stat660): What is the syntax for reading in character variable?
- Answer (mphan12-stat660): INPUT <VARIABLE> $ X-Y (where X is the starting position and Y is the ending position).



[Course Textbook Chapter 6, Problem 8]
- Question (mphan12-stat660): What happens to the variable, if the variable appears on both side of the equal sign?
- Answer (mphan12-stat660): The original value on the right is used to evaluate the expression. The result is assigned to the variable on the left side of the equal sign.


[Week 5 SAS Recipe: basic_recipe_for_creating_analytic_datasets]



[Week 5 SAS Recipe: adv_recipe_for_creating_analytic_datasets]


