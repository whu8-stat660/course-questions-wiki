
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 2, Problem 1]
- Question (whu8-stat660): Although all kinds data can be used in SAS, only the SAS data set can be processed in SAS program?
- Answer(whu8-stat660): Yes. Although SAS supports all kinds of raw data files such as excel and etc, these raw data files need to covert to SAS data set for further analysis in SAS.



[Course Textbook Chapter 2, Problem 2]
- Question (whu8-stat660): What’s step boundaries?
- Answer(whu8-stat660): Every step has a beginning and ending boundary, these are the step boundaries.



[Course Textbook Chapter 2, Problem 3]
- Question (whu8-stat660): Are character and numeric the only two data value types accepted in SAS data set?
- Answer(whu8-stat660):Yes.



[Course Textbook Chapter 2, Problem 5]
- Question (whu8-stat660): What are the requirements for variable names in SAS?



[Course Textbook Chapter 2, Problem 8]
- Question (whu8-stat660): Is the length for numeric variable are fixed?
- Answer(whu8-stat660):Yes, it's 8 bytes.


[Course Textbook Chapter 3, Problem 5]
- Question (whu8-stat660):- Question (whu8-stat660): What’s the difference between temporary and Permanente library? 



[Course Textbook Chapter 3, Problem 6]
- Question (whu8-stat660): What’s the highest level of organization for information within SAS?
- Answer(whu8-stat660):Library.



[Course Textbook Chapter 4, Problem 1]
- Question (whu8-stat660): Can we omit run statements?
- Answer(whu8-stat660): Yes, but it's better to have.



[Course Textbook Chapter 4, Problem 3]
- Question (whu8-stat660): What would happen if you have unequal quotations in the codes?
- Answer(whu8-stat660): The program would not be excuted, and an error message would show in the log.



[Course Textbook Chapter 4, Problem 4]
- Question (whu8-stat660): What’s global statements?
- Answer(whu8-stat660):Global statements generally provide information to SAS, request information or data, move between different modes of execution, or set values for system options. You can use global statements anywhere in a SAS program. Global statements are not executable; they take effect as soon as SAS compiles program statements



[Course Textbook Chapter 4, Problem 5]
- Question (whu8-stat660): What’s the syntax error in SAS?




[Course Textbook Chapter 4, Problem 7]
- Question (whu8-stat660): Although all kinds data can be used in SAS, only the SAS data set can be processed in SAS program?
- Answer(whu8-stat660): Yes. Although SAS supports all kinds of raw data files such as excel and etc, these raw data files need to covert to SAS data set for further analysis in SAS.



[Course Textbook Chapter 4, Problem 9]
- Question (whu8-stat660): What’s the difference between two types of comments?
- Answer(whu8-stat660):There are two types of comments: block comments and comment statements. The block comments can be any length, and can contains semicolons. But they can’t be nested. You should avoid placing block comment symbols in the first or second columns. While comment statements are complete statements which could start in the first or second columns, and  they can’t contain internal semicolons.



[Week 2 SAS Recipe: basic_recipe_for_loading_data_from_remote_Excel_file]
- Question (whu8-stat660): Why do we need to clear the file ref?
- Answer(whu8-stat660): This allows sex in particular to free up the file name and the temporary storage location in order to better use resources and not create the possibility of some type of memory leak.



[Week 2 SAS Recipe: bonus_advanced_recipe_for_loading_data_from_remote_Excel_file]
- Question (whu8-stat660): Can a macro load sever times with different data value?
- Answer(whu8-stat660):I think the answer is yes, we can call macro as many time as we want, we could also load different values to macro variables each time we call.


