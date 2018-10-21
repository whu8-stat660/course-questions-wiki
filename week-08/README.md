
## Week 8 Quiz Questions and Answers

In order to prepare your Week 8 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-8" in your fork of this repo. Then, after all edits have been made/committed, your Week 8 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-8 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 12, Problem 1]
- Question (llopez37-stat660) Why does the following keep not override the drop statement given its order?
* Question (yli110-stat660): What is the difference between the DROP= option in DATA step and in SET statement?



[Course Textbook Chapter 12, Problem 2]
- Question (llopez37-stat660) Would the drop not override the keep like in the previous problem still dropping the variable?
- Answer (llopez37-stat660) It appears that I might be misunderstanding the question and they refer to removing drop
* Question (yli110-stat660): What are the temporary variables created when using BY statement with SET statement?
* Answer (yli110-stat660): FIRST.variable and LAST.variable are created and they are not stored in the dataset.



[Course Textbook Chapter 12, Problem 3]
- Question (llopez37-stat660) What is the purpose of the first and last variable if they are temp?
* Question (yli110-stat660): How do you write a single observation out into a new data set?
* Answer (yli110-stat660): by using POINT= option with OUTPUT and STOP statements.



[Course Textbook Chapter 12, Problem 7]
- Question (llopez37-stat660) Is this because they serve a similar function?
- Answer (llopez37-stat660) It appears this is the case.
* Question (yli110-stat660): Can you use both END= and POINT= option in the same SET statement?
* Answer (yli110-stat660): No, END= and POINT= are imcompactible in the same SET statement.



[Course Textbook Chapter 12, Problem 8]
- Question (llopez37-stat660) If we had added first as well would we have gotten two observations? 
* Question (yli110-stat660): What does the pdv look like at the compilation phase at the beginning of DATA step?



[Week 8 SAS Recipe: recipe_for_isolating_all_duplicates]
- Question (llopez37-stat660) Is this similar to our github workflow in which we work outside of the master through a fork? 
- Answer (llopez37-stat660) After going through various forums on sas it seems that this is common practice amongst many when trying different approaches to data sets.
* Question (yli110-stat660): What is the difference when isolating duplicates using first.variable and last.variable with BY statement, between using nodupkey/noduprecs?



[Week 8 SAS Recipe: recipe_for_drop_and_swap]
- Question (llopez37-stat660) Do we leave the values as characters to make the output readable for others or what is the purpose of leaving it as character? 
* Question (yli110-stat660): For a character column which includes both characters and numbers, how do you extract the numberic parts out and store them into a new variable?


