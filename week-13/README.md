
## Week 13 Quiz Questions and Answers

In order to prepare your Week 13 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-13" in your fork of this repo. Then, after all edits have been made/committed, your Week 13 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-13 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 17, Problem 1]
- Question (anguyen152-stat660) : Why dont I see any "@" here ? 
* Question(yli110-stat660): What is the difference between column input and formatted input?
* Answer(yli110-stat660): Column input is used for reading standard values only, and formatted input can be used to read both standard and nonstandard data in fixed fields.
- Question (llopez37-stat660) would we get different results if we switch which data set is first versus second?
- Answer (llopez37-stat660) it seems only difference is the order in which it is read in
- Question (whu8-stat660):Are beginning and ending column locations needed to be specified in the column input statement?
- Answer (whu8-stat660):Yes, but if it starts in column 1 which is the default column pointer location, the beginning column location doesn't need to be specified.
- Question (mphan12-stat660): What is the difference between column and formatted inputs?
- Answer (mphan12-stat660): Column input is used for reading standard values only, and formatted input can be used to read both standard and non-standard fixed fields.



[Course Textbook Chapter 17, Problem 5]
- Question (anguyen152-stat660) : How to use input function to read characters ? 
- Answer (anguyen152-stat660) : Using the dollar sign ($) before the w value 
* Question(yli110-stat660): What is the informat you use to read in a character value?
* Answer(yli110-stat660): $w.
- Question (llopez37-stat660) Do all the observations also get replaced with the new datasets?
- Question (whu8-stat660):What does 'w' represent in the '$w' informat?
- Answer (whu8-stat660):The w represents the field width of the data value or the total number of columns that contain the raw data field.
- Question (mphan12-stat660): What does 'w' represent in the $w informat?
- Answer (mphan12-stat660): The w represents the field width.



[Course Textbook Chapter 17, Problem 7]
- Question (anguyen152-stat660) : Why do we have to "+6" but not "+7" in this case ? 
* Question(yli110-stat660): How many ways can you use to locate the positions of pointer control in formatted input?
* Answer(yli110-stat660): You could use either @n or +(-)n.
- Question (llopez37-stat660) In what order would the rename statement go? 
- Question (whu8-stat660):How the +n pointer control works?
- Answer (whu8-stat660):It moves the pointer ahead with n columns.
- Question (mphan12-stat660): What are the possible ways to locate the positions of the pointer control in formatted input?
- Answer (mphan12-stat660):  @n or +(-)n can locate the positions of the pointer control.



[Course Textbook Chapter 17, Problem 8]
- Question (anguyen152-stat660) : Why dont we need to define the "d" value here ? 
- Answer (anguyen152-stat660) : Because the data value contains decimal places, a d value is not needed.
* Question(yli110-stat660): What's the purpose of using informat COMMAw.d?
* Answer(yli110-stat660): First to read data in, second it removes any special signs like dollar sign, comma, percent et al.
[Course Textbook Chapter 17, Problem 8] 
- Question (llopez37-stat660) What syntax would we use to sort the data? 
- Question (whu8-stat660):What's the use of COMMAw.d informat?
- Answer (whu8-stat660):The COMMAw.d informat strips out special characters, such as commas,dollar signs, and percent signs, from numeric data and stores only numeric values in a SAS data set.
- Question (mphan12-stat660): What does the COMMAw.d function do?
- Answer (mphan12-stat660): The COMMAw.d informat strips out special characters (commas, dollar signs, and percent signs) from a numeric data and stores only numeric values in a SAS data set.



[Course Textbook Chapter 17, Problem 9]
- Question (anguyen152-stat660) : What should be noted when using COMMAw.d function ? 
- Answer (anguyen152-stat660) : A period should always follow the "w."
* Question(yli110-stat660): What's the order of variables that SAS reads from the raw files?
- Question (llopez37-stat660) why do some observations appear such as ( . ) veruss a blank statement?
- Answer (llopez37-stat660) This is based off of character and numeric variable. 
- Question (whu8-stat660):How to use the w.d informat to read standard numeric data?
- Answer (whu8-stat660):The w specifies the field width of the raw data value, the period serves as a delimiter,and the d specifies the number of implied decimal places for the value.
- Question (mphan12-stat660): What does the d in "w.d" informat represent?
- Answer (mphan12-stat660): The w specifies the field width of the raw data value, the period serves as a delimiter,and the d specifies the number of implied decimal places for the value.



[Week 13 SAS Recipe: basic_recipe_to_load_remote_delimited_file]
- Question (anguyen152-stat660) : Why there are so many "invalid data.." notification when I ran this example ? 
* Question(yli110-stat660): What the DELIMITER statement should be if you want to import a tab-separated values file?
- Question (llopez37-stat660) Why not just save the data in a comma delimited file version?
- Question (whu8-stat660):What's the meaning of 'dbms'?
- Question (mphan12-stat660): What is the DELIMITER statement for importing a tab-separated values file?
- Answer (mphan12-stat660): "09"x



[Week 13 SAS Recipe: adv_recipe_to_load_remote_delimited_file]
- Question (anguyen152-stat660) : How the "informat" and "input" functions are used here ? 
- Answer (anguyen152-stat660) : The informat statement sets each column type to character-values with width 100.  The input statement specifies the columns to have their values read and
must appear in the same order as the columns appear in the input dataset.
* Question(yli110-stat660): What are the basic statements in the DATA step when you try to read temporary data files into SAS?
* Answer(yli110-stat660): Despite DATA, you still need INFILE, INFORMAT, and INPUT to get data into SAS.
- Question (llopez37-stat660) Is this in order to read the data into a proper data set and have the columns properly aligned? 
- Answer (llopez37-stat660) It seems this is the case as to avoid improper reading of the file
- Question (whu8-stat660):What the use of the input statement?
- Answer (whu8-stat660):The input statement specifies the columns to have their values read and must appear in the same order as the columns appear in the input dataset.
- Question (mphan12-stat660): What is the purpose of "informat" when reading in raw data?


