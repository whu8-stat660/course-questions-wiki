
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
* Question (yli110-stat660): In one-to-one matching, how does SAS determine the number of observations in the new data set?
- Question (llopez37-stat660) Why does it not combine all and leave missing for some observations?
- Question (whu8-stat660):What would the number of observations in the result if the second data set has more observations than the first one when doing one-to-one matching?
- Answer(whu8-stat660): The number of observations in the new data set is the number of observations in the smallest original data set.
- Question (anguyen152-stat660) : What's the difference between MERGE and SET statement in combining datasets ? 
- Answer (anguyen152-stat660) : The SET statement is used to concatenate the datasets , the MERGE statement is used to match and merge datasets, which often goes with "BY" statement after that



[Course Textbook Chapter 13, Problem 2]
- Question (mphan12-stat660): What is interleaving?
- Answer (mphan12-stat660): Intersperses observations in order from two or more data sets, based on one or more common variables. It uses the SET and BY statement.  When you use a BY statement to concatenate data sets, the result is interleaving. To interleave SAS data sets, specify a list of data set names in the SET statement, and specify one or more BY variables in the BY statement.
* Question (yli110-stat660): What is the difference between concatenating and interleaving?
- Question (llopez37-stat660) In order to preserve all observations is the by statement necessary?
- Answer (llopez37-stat660) It seems that the by statement preserves all observations in that variable
- Question (whu8-stat660):What's the use of BY statement in interleaving combining?
- Question (anguyen152-stat660) : What is "interleaving" ? 
- Answer (anguyen152-stat660) :When you use a BY statement to concatenate data sets, the result is interleaving. Interleaving intersperses observations from two or more data sets, based on one or more common variables. Unlike concatenating datasets, interleaving command has the final data set sorted in the BY statement



[Course Textbook Chapter 13, Problem 3]
- Question (mphan12-stat660): What is concatenating?
- Answer (mphan12-stat660): Another way to combine SAS data sets with the SET statement is concatenating, which appends the observations from one data set to another data set. To concatenate SAS data sets, you specify a list of data set names in the SET statement. 
* Question (yli110-stat660): In concatenating, what happens when the two data sets in the SET statement have different variables?
- Question (llopez37-stat660) So if no by statement is used then the smallest size of observations is what follows? 
- Answer (llopez37-stat660) From googling it seems that if the size of the output matches it will follow through together without drop off as opposed to problem 1
- Question (whu8-stat660):What is concatenating?
- Answer(whu8-stat660): Concatenating appends the observations from one data set to another data set. The new data set contains the total number of records from all input data sets,and all the variables from all the input data sets appear in the new data set.
- Question (anguyen152-stat660) : How SAS concatenate 2 datasets without no variables in common ? 
- Answer (anguyen152-stat660) : It will appends the observations from one data set to another data set. The new data set contains the total number of records from all input data sets.



[Course Textbook Chapter 13, Problem 4]
- Question (mphan12-stat660): How is the data read in when concatenating data sets?
- Answer (mphan12-stat660): When a program concatenates data sets, all of the observations are read from the first data set listed in the SET statement. Then all of the observations are read from the second data set listed, and so on, until all of the listed data sets have been read. The new data set contains all of the variables and observations from all of the input data sets.
* Question (yli110-stat660): What is the difference between SET and MERGE?
* Answer (yli110-stat660): Basically, SET stacks two data sets vertically, and MERGE combines two data sets horizontally.
- Question (llopez37-stat660) Is this due to the fact that there are multiple ID variables with observation 2?
- Question (whu8-stat660):What's the difference between concatenating and merging data sets?
- Question (anguyen152-stat660) : When should we use SET and when should we use MERGE ? 



[Course Textbook Chapter 13, Problem 5]
- Question (mphan12-stat660): What happens to a varable with the same name in a MERGE statement?
- Answer (mphan12-stat660): If you have variables with the same name in more than one input data set, values of the same-named variable in the first data set in which it appears are overwritten by values of the same-named variable in subsequent data sets.
* Question (yli110-stat660): When merging two data sets, what happens if you have variables with the same name but different values?
* Answer (yli110-stat660): If having variables with the same name but different values, values of the same-named ariable in the first data set will be overwritten by values of the same-named variable in subsequent data sets.
- Question (llopez37-stat660) Is there a way to have data set 1 overwrite data set 2 in case you have the improper order of data sets for when you merge?
- Question (whu8-stat660):What would happen when merging data sets with same name variables in more than one input data set?
- Answer(whu8-stat660): Values of the same-named variable in subsequent data sets will overwrite the first data set.
- Question (anguyen152-stat660) : What if the values are different for 2 same-name variables in "MERGE" step ? 
- Answer (anguyen152-stat660) :If you have variables with the same name in more than one input data set, values of the same-named variable in the first data set in which it appears are overwritten by values of the same-named variable in subsequent data sets.



[Course Textbook Chapter 13, Problem 7]
- Question (mphan12-stat660): What is match-merging?
- Answer (mphan12-stat660): Matches observations from two or more data sets into a single observation in a new data set according to the values of a common variable.  Match-merging overwrites same-named variables in the first data set with same-named variables in subsequent data sets. 
* Question (yli110-stat660): how do you prevent the overwriting scenario described in the last question?
* Answer (yli110-stat660): To prevent overwriting, rename variables by using the RENAME= data set option in the MERGE statement.
- Question (llopez37-stat660) Why does ths prevent blue from being overwritten does it rename it as it process the code or what is the stack look like in this process? 
- Question (whu8-stat660):How to prevent overwriting the same-named variables when merging data sets?
- Answer(whu8-stat660): Rename variables by using the RENAME= data set option in the MERGE statement.
- Question (anguyen152-stat660) : What if I want to keep both "Blue" variables in 2 datasets without renaming it ? 



[Course Textbook Chapter 13, Problem 9]
- Question (mphan12-stat660): How do you prevent a variable from being overwritten when merging tables with same name variable?
- Answer (mphan12-stat660): To prevent overwriting, you can rename variables by using the RENAME= data set option in the MERGE statement.
* Question (yli110-stat660): When merging data sets, what happens when the BY variable is not sorted?
- Question (llopez37-stat660) If we did not use the by statement here, then it would only be 4 observations?
- Question (whu8-stat660):Will there be duplicate values in the BY statement variable when merging data sets?
- Answer(whu8-stat660): No, the new data set contains one observation for each unique value of the variables in BY statement.
- Question (anguyen152-stat660) : How to eliminate some specific records out of the final dataset after merging the 2 ?



[Week 9 SAS Recipe: basic_recipe_for_combining_data_horizontally]
- Question (mphan12-stat660): Why is it necessary to use the LABEL statement?
* Question (yli110-stat660): What statement is used to merge dataset horizontally in SAS?
- Question (llopez37-stat660) How exactly does merge differ from combining the sets with what we learned in the chapter? 
- Answer (llopez37-stat660) It seems that merge will force combine the data sets but with the other method it will base it off of by statements or the size of rows on the second data set.
- Question (whu8-stat660):What's the use of BY statment in match-merging?
- Answer(whu8-stat660): The BY statment is used to name the unique columns which specify how rows are to be matched up when combing the datasets.
- Question (anguyen152-stat660) : Why do we have 2 INPUT statement at the end of the recipe ?



[Week 9 SAS Recipe: adv_recipe_for_combining_data_horizontally]
- Question (mphan12-stat660): What does COALESCE function do?
- Answer (mphan12-stat660): Returns the first non-null or nonmissing value from a list of numeric arguments.
* Question (yli110-stat660): What is the disadvantage of using PROC SQL to combine data sets horizontally.
- Question (llopez37-stat660) Is proc sql limitations on memory or why do we not focus on proc sql since it seems so powerful? 
- Question (whu8-stat660):What are the differences between sql and proc sql?
- Question (anguyen152-stat660) : What's the "full join" command mean in this recipe? 


