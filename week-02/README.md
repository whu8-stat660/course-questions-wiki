
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 2, Problem 1]
- Question (anguyen152-stat660):What are "observations" and "variables?"
- Answer (anguyen152-stat660):"Observations" can be counted as "rows" and "variables" can be counted as "columns" 



[Course Textbook Chapter 2, Problem 2]
- Question (anguyen152-stat660): What is the purpose of the 2nd line "infile jobs;" ? 
- Answer (anguyen152-stat660): INFILE statement identifies the file to read. In this case, "table" is the input dataset and "jobs" is the file to read. 



[Course Textbook Chapter 2, Problem 3]
- Question (anguyen152-stat660):What are the differences between numeric and character variables? 



[Course Textbook Chapter 2, Problem 5]
- Question (anguyen152-stat660): What makes a valid variable name in SAS ?



[Course Textbook Chapter 2, Problem 8]
- Question (anguyen152-stat660): Can we define the length for numeric variables ? and how ? 


[Course Textbook Chapter 3, Problem 5]
- Question (anguyen152-stat660):What is the "set" command used for ? for example:
```data mysales.totals; 
    set sales_99.salesanalysis; 
    if totalsales>50000; 
run;```



[Course Textbook Chapter 3, Problem 6]
- Question (anguyen152-stat660):What is the YEARCUTOFF option used for ?



[Course Textbook Chapter 4, Problem 1]
- Question (anguyen152-stat660):Why indentation should be paid intention to while SAS programming?



[Course Textbook Chapter 4, Problem 3]
- Question (anguyen152-stat660): Can I find the answer to this problem without understanding every code line ?



[Course Textbook Chapter 4, Problem 4]
- Question (anguyen152-stat660):How are syntax errors reported in SAS programs ?



[Course Textbook Chapter 4, Problem 5]
- Question (anguyen152-stat660): What are common types of syntax errors in SAS ? 
- Answer (anguyen152-stat660): These are common syntax errors in SAS: misspelled SAS keyword, unmatched quotation marks, missing a semicolon, invalid statement option, invalid data set option.



[Course Textbook Chapter 4, Problem 7]
- Question (anguyen152-stat660):Are typos errors automatically detected in SAS ?
- Answer (anguyen152-stat660): No



[Course Textbook Chapter 4, Problem 9]
- Question (anguyen152-stat660):What to do if the active window displays the message DATA step running for a long time?



[Week 2 SAS Recipe: basic_recipe_for_loading_data_from_remote_Excel_file]
- Question (anguyen152-stat660):Can we edit the dataset after imported ?



[Week 2 SAS Recipe: bonus_advanced_recipe_for_loading_data_from_remote_Excel_file]
- Question (anguyen152-stat660):Are macros in SAS of the same use as functions in C++ ? How often is macro used in SAS ?




