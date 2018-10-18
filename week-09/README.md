
## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (mphan12-stat660): What is one-to-one reading?
- Answer (mphan12-stat660): Use multiple SET statements in a DATA step to combine data sets. One-to-one reading combines rows from two or more data sets by creating rows that contain all of the columns from each contributing data set. Rows are combined based on their relative position in each data set. That is, the first row in one data set is combined with the first in the other, and so on. The data program stops after it has read the last row from the smallest data set.



[Course Textbook Chapter 13, Problem 2]
- Question (mphan12-stat660): What is interleaving?
- Answer (mphan12-stat660): Intersperses observations in order from two or more data sets, based on one or more common variables. It uses the SET and BY statement.  When you use a BY statement to concatenate data sets, the result is interleaving. To interleave SAS data sets, specify a list of data set names in the SET statement, and specify one or more BY variables in the BY statement.



[Course Textbook Chapter 13, Problem 3]
- Question (mphan12-stat660): What is concatenating?
- Answer (mphan12-stat660): Another way to combine SAS data sets with the SET statement is concatenating, which appends the observations from one data set to another data set. To concatenate SAS data sets, you specify a list of data set names in the SET statement. 



[Course Textbook Chapter 13, Problem 4]
- Question (mphan12-stat660): How is the data read in when concatenating data sets?
- Answer (mphan12-stat660): When a program concatenates data sets, all of the observations are read from the first data set listed in the SET statement. Then all of the observations are read from the second data set listed, and so on, until all of the listed data sets have been read. The new data set contains all of the variables and observations from all of the input data sets.



[Course Textbook Chapter 13, Problem 5]
- Question (mphan12-stat660): What happens to a varable with the same name in a MERGE statement?
- Answer (mphan12-stat660): If you have variables with the same name in more than one input data set, values of the same-named variable in the first data set in which it appears are overwritten by values of the same-named variable in subsequent data sets.



[Course Textbook Chapter 13, Problem 7]
- Question (mphan12-stat660): What is match-merging?
- Answer (mphan12-stat660): Matches observations from two or more data sets into a single observation in a new data set according to the values of a common variable.  Match-merging overwrites same-named variables in the first data set with same-named variables in subsequent data sets. 



[Course Textbook Chapter 13, Problem 9]
- Question (mphan12-stat660): How do you prevent a variable from being overwritten when merging tables with same name variable?
- Answer (mphan12-stat660): To prevent overwriting, you can rename variables by using the RENAME= data set option in the MERGE statement.



[Week 9 SAS Recipe: basic_recipe_for_combining_data_horizontally]
- Question (mphan12-stat660): Why is it necessary to use the LABEL statement?
- Answer (mphan12-stat660): 



[Week 9 SAS Recipe: adv_recipe_for_combining_data_horizontally]
- Question (mphan12-stat660): What does COALESCE function do?
- Answer (mphan12-stat660): Returns the first non-null or nonmissing value from a list of numeric arguments.


