
## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 13, Problem 1]
* Question (yli110-stat660): In one-to-one matching, how does SAS determine the number of observations in the new data set?



[Course Textbook Chapter 13, Problem 2]
* Question (yli110-stat660): What is the difference between concatenating and interleaving?



[Course Textbook Chapter 13, Problem 3]
* Question (yli110-stat660): In concatenating, what happens when the two data sets in the SET statement have different variables?



[Course Textbook Chapter 13, Problem 4]
* Question (yli110-stat660): What is the difference between SET and MERGE?
* Answer (yli110-stat660): Basically, SET stacks two data sets vertically, and MERGE combines two data sets horizontally.



[Course Textbook Chapter 13, Problem 5]
* Question (yli110-stat660): When merging two data sets, what happens if you have variables with the same name but different values?
* Answer (yli110-stat660): If having variables with the same name but different values, values of the same-named ariable in the first data set will be overwritten by values of the same-named variable in subsequent data sets.



[Course Textbook Chapter 13, Problem 7]
* Question (yli110-stat660): how do you prevent the overwriting scenario described in the last question?
* Answer (yli110-stat660): To prevent overwriting, rename variables by using the RENAME= data set option in the MERGE statement.



[Course Textbook Chapter 13, Problem 9]
* Question (yli110-stat660): When merging data sets, what happens when the BY variable is not sorted?



[Week 9 SAS Recipe: basic_recipe_for_combining_data_horizontally]
* Question (yli110-stat660): What statement is used to merge dataset horizontally in SAS?



[Week 9 SAS Recipe: adv_recipe_for_combining_data_horizontally]
* Question (yli110-stat660): What is the disadvantage of using PROC SQL to combine data sets horizontally.
