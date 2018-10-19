
## Week 9 Quiz Questions and Answers

In order to prepare your Week 9 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-9" in your fork of this repo. Then, after all edits have been made/committed, your Week 9 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-9 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 13, Problem 1]
- Question (anguyen152-stat660) : What's the difference between MERGE and SET statement in combining datasets ? 
- Answer (anguyen152-stat660) : The SET statement is used to concatenate the datasets , the MERGE statement is used to match and merge datasets, which often goes with "BY" statement after that



[Course Textbook Chapter 13, Problem 2]
- Question (anguyen152-stat660) : What is "interleaving" ? 
- Answer (anguyen152-stat660) :When you use a BY statement to concatenate data sets, the result is interleaving. Interleaving intersperses observations from two or more data sets, based on one or more common variables. Unlike concatenating datasets, interleaving command has the final data set sorted in the BY statement



[Course Textbook Chapter 13, Problem 3]
- Question (anguyen152-stat660) : How SAS concatenate 2 datasets without no variables in common ? 
- Answer (anguyen152-stat660) : It will appends the observations from one data set to another data set. The new data set contains the total number of records from all input data sets.



[Course Textbook Chapter 13, Problem 4]
- Question (anguyen152-stat660) : When should we use SET and when should we use MERGE ? 



[Course Textbook Chapter 13, Problem 5]
- Question (anguyen152-stat660) : What if the values are different for 2 same-name variables in "MERGE" step ? 
- Answer (anguyen152-stat660) :If you have variables with the same name in more than one input data set, values of the same-named variable in the first data set in which it appears are overwritten by values of the same-named variable in subsequent data sets.



[Course Textbook Chapter 13, Problem 7]
- Question (anguyen152-stat660) : What if I want to keep both "Blue" variables in 2 datasets without renaming it ? 



[Course Textbook Chapter 13, Problem 9]
- Question (anguyen152-stat660) : How to eliminate some specific records out of the final dataset after merging the 2 ?



[Week 9 SAS Recipe: basic_recipe_for_combining_data_horizontally]
- Question (anguyen152-stat660) : Why do we have 2 INPUT statement at the end of the recipe ?



[Week 9 SAS Recipe: adv_recipe_for_combining_data_horizontally]
- Question (anguyen152-stat660) : What's the "full join" command mean in this recipe? 


