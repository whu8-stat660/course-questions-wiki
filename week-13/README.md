
## Week 13 Quiz Questions and Answers

In order to prepare your Week 13 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-13" in your fork of this repo. Then, after all edits have been made/committed, your Week 13 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-13 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 17, Problem 1]
- Question (mphan12-stat660): What is the difference between column and formatted inputs?
- Answer (mphan12-stat660): Column input is used for reading standard values only, and formatted input can be used to read both standard and non-standard fixed fields.



[Course Textbook Chapter 17, Problem 5]
- Question (mphan12-stat660): What does 'w' represent in the $w informat?
- Answer (mphan12-stat660): The w represents the field width.



[Course Textbook Chapter 17, Problem 7]
- Question (mphan12-stat660): What are the possible ways to locate the positions of the pointer control in formatted input?
- Answer (mphan12-stat660):  @n or +(-)n can locate the positions of the pointer control.



[Course Textbook Chapter 17, Problem 8]
- Question (mphan12-stat660): What does the COMMAw.d function do?
- Answer (mphan12-stat660): The COMMAw.d informat strips out special characters (commas, dollar signs, and percent signs) from a numeric data and stores only numeric values in a SAS data set.



[Course Textbook Chapter 17, Problem 9]
- Question (mphan12-stat660): What does the d in "w.d" informat represent?
- Answer (mphan12-stat660): The w specifies the field width of the raw data value, the period serves as a delimiter,and the d specifies the number of implied decimal places for the value.



[Week 13 SAS Recipe: basic_recipe_to_load_remote_delimited_file]
- Question (mphan12-stat660): What is the DELIMITER statement for importing a tab-separated values file?
- Answer (mphan12-stat660): "09"x



[Week 13 SAS Recipe: adv_recipe_to_load_remote_delimited_file]
- Question (mphan12-stat660): What is the purpose of "informat" when reading in raw data?


