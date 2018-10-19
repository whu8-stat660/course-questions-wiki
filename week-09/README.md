
## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (whu8-stat660):What would the number of observations in the result if the second data set has more observations than the first one when doing one-to-one matching?
- Answer(whu8-stat660): The number of observations in the new data set is the number of observations in the smallest original data set.



[Course Textbook Chapter 13, Problem 2]
- Question (whu8-stat660):What's the use of BY statement in interleaving combining?



[Course Textbook Chapter 13, Problem 3]
- Question (whu8-stat660):What is concatenating?
- Answer(whu8-stat660): Concatenating appends the observations from one data set to another data set. The new data set contains the total number of records from all input data sets,and all the variables from all the input data sets appear in the new data set.


[Course Textbook Chapter 13, Problem 4]
- Question (whu8-stat660):What's the difference between concatenating and merging data sets?



[Course Textbook Chapter 13, Problem 5]
- Question (whu8-stat660):What would happen when merging data sets with same name variables in more than one input data set?
- Answer(whu8-stat660): Values of the same-named variable in subsequent data sets will overwrite the first data set.


[Course Textbook Chapter 13, Problem 7]
- Question (whu8-stat660):How to prevent overwriting the same-named variables when merging data sets?
- Answer(whu8-stat660): Rename variables by using the RENAME= data set option in the MERGE statement.


[Course Textbook Chapter 13, Problem 9]
- Question (whu8-stat660):Will there be duplicate values in the BY statement variable when merging data sets?
- Answer(whu8-stat660): No, the new data set contains one observation for each unique value of the variables in BY statement.


[Week 9 SAS Recipe: basic_recipe_for_combining_data_horizontally]
- Question (whu8-stat660):What's the use of BY statment in match-merging?
- Answer(whu8-stat660): The BY statment is used to name the unique columns which specify how rows are to be matched up when combing the datasets.


[Week 9 SAS Recipe: adv_recipe_for_combining_data_horizontally]
- Question (whu8-stat660):What are the differences between sql and proc sql?

