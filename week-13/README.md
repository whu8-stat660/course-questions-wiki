
## Week 13 Quiz Questions and Answers

In order to prepare your Week 13 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-13" in your fork of this repo. Then, after all edits have been made/committed, your Week 13 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-13 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 17, Problem 1]
- Question (whu8-stat660):Are beginning and ending column locations needed to be specified in the column input statement?
- Answer (whu8-stat660):Yes, but if it starts in column 1 which is the default column pointer location, the beginning column location doesn't need to be specified.



[Course Textbook Chapter 17, Problem 5]
- Question (whu8-stat660):What does 'w' represent in the '$w' informat?
- Answer (whu8-stat660):The w represents the field width of the data value or the total number of columns that contain the raw data field.



[Course Textbook Chapter 17, Problem 7]
- Question (whu8-stat660):How the +n pointer control works?
- Answer (whu8-stat660):It moves the pointer ahead with n columns.



[Course Textbook Chapter 17, Problem 8]
- Question (whu8-stat660):What's the use of COMMAw.d informat?
- Answer (whu8-stat660):The COMMAw.d informat strips out special characters, such as commas,dollar signs, and percent signs, from numeric data and stores only numeric values in a SAS data set.



[Course Textbook Chapter 17, Problem 9]
- Question (whu8-stat660):How to use the w.d informat to read standard numeric data?
- Answer (whu8-stat660):The w specifies the field width of the raw data value, the period serves as a delimiter,and the d specifies the number of implied decimal places for the value.



[Week 13 SAS Recipe: basic_recipe_to_load_remote_delimited_file]
- Question (whu8-stat660):What's the meaning of 'dbms'?



[Week 13 SAS Recipe: adv_recipe_to_load_remote_delimited_file]
- Question (whu8-stat660):What the use of the input statement?
- Answer (whu8-stat660):The input statement specifies the columns to have their values read and must appear in the same order as the columns appear in the input dataset.

