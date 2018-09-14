
## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 8, Problem 3]
- Question (whu8-stat660): What’s the requirement of the name of format with the VALUE statment?
- Answer(whu8-stat660): The new format’s name can’t end with a number, can’t end with a period, and can’t be the name of a SAS format. The name must begin with a dollar sign if used with a character variable.



[Course Textbook Chapter 8, Problem 4]
- Question (whu8-stat660):What’s the use of ‘lib=’ in the proc format?
- Answer(whu8-stat660):It's used to specify the library of the format.



[Course Textbook Chapter 8, Problem 5]
- Question (whu8-stat660):What are the types of value can be specified in the format value statement?
- Answer(whu8-stat660):A single or a range of numeric or character values, but not a mix of both.



[Course Textbook Chapter 8, Problem 6]
- Question (whu8-stat660):What’s label in format function?



[Course Textbook Chapter 8, Problem 7]
- Question (whu8-stat660):What’s the meaning of ‘low’ or ‘high’ in value statement?
- Answer(whu8-stat660):These two keywords are referred to the lowest or highest value in the variables exclude missing value.



[Course Textbook Chapter 8, Problem 8]
- Question (whu8-stat660):What’s the difference between format statement used in a DATA step and format statement used in a PROC step?
- Answer(whu8-stat660):If format statement is used in a data step, it permanently associates the formats with variable in the data set, while the format statement in a proc step is used only to set the format.



[Course Textbook Chapter 9, Problem 1]
- Question (whu8-stat660):What are the default statistics produced by the means procedure?
- Answer(whu8-stat660):N-count(without missing value), mean,minimum,maximum and standard deviation.



[Course Textbook Chapter 9, Problem 2]
- Question (whu8-stat660):What’s the function of ‘var’ statement in proc means analysis?
- Answer(whu8-stat660):It’s used to select the variables which are to be calculated.



[Course Textbook Chapter 9, Problem 4]
- Question (whu8-stat660):What’s the difference between ‘class’ and ‘by’ processing?
- Answer(whu8-stat660):Unlike class processing, by-group processing requires that your data already be indexed or sorted in the order of by variables. Sort procedure may be needed before proc means with a by group.



[Course Textbook Chapter 9, Problem 7]
- Question (whu8-stat660):If no variable is specified in the var statement, what would be the result for proc freq applied to a data set？
- Answer(whu8-stat660):There will be a frequency result table for each variables in the data set.



[Course Textbook Chapter 9, Problem 8]
- Question (whu8-stat660):Can ID column be used in proc freq?
- Answer(whu8-stat660):It can be used in proc freq, but both continuous values and unique values will result in lengthy, meaningless tables.  



[Course Textbook Chapter 9, Problem 10]
- Question (whu8-stat660):What's the use of asterisk in a table statement?
- Answer(whu8-stat660):The asterisk is used to join the variables in a two-way tables statement.



[Week 4 SAS Recipe: recipe_for_summarizing_quantitative_values]
- Question (whu8-stat660):If the class statement together with var used in the proc mean, both variables will be joined in the result table? 
- Answer(whu8-stat660):I think so, just like the use of asterisk in the proc freq.



[Week 4 SAS Recipe: recipe_for_summarizing_qualitative_values]
- Question (whu8-stat660):If the option nlevels  is omitted, what would be the result?



[Week 4 SAS Recipe: recipe_for_temporarily_binning_values]
- Question (whu8-stat660):Where does SAS save the online data files which is got from proc http function?

