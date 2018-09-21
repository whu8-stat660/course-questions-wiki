
## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 6, Problem 1]
- Question (mphan12-stat660): When fileref is used to specify a delimited file to import, what is the default logical record length (LRECL) and what is the maximum.
- Answer (mphan12-stat660): The default LRECL is 256 and the maximum value that the IMPORT procedure supports is 32767.
- Question (whu8-stat660): What’ the function of filename statement?
- Answer(whu8-stat660): Filename statement is used to point to the location of the external file that contains the data. Its syntax is “FILENAME fileref 'filename';”.
- Question (jduan10-stat660): When referring a file in an aggregate storage location, can the file extension be omitted?
- Answer (jduan10-stat660): If the file extension is omitted, SAS looks for a .dat file.



[Course Textbook Chapter 6, Problem 2]
- Question (mphan12-stat660): What is fileref?
- Answer (mphan12-stat660): A fileref is a SAS name that is associated with the physcial location of the output file. To assign fileref, use the FILENAME statement.
- Question (whu8-stat660): What is fileref?
- Answer(whu8-stat660): Filerefs perform the same function as librefs: they temporarily point to a storage location for data. However, librefs reference SAS libraries, whereas filerefs reference external files.
- Question (jduan10-stat660): What’s the maximum characters can the fileref name has?
- Answer (jduan10-stat660): The name must be 1 to 8 characters long.



[Course Textbook Chapter 6, Problem 6]
- Question (mphan12-stat660): What are the two statements used to read in raw data?
- Answer (mphan12-stat660): The INFILE and INPUT statements are used in the DATA step for read in raw data.
- Question (whu8-stat660): How to use the input statement?
- Answer(whu8-stat660):Input statment is used to read specific fields. You must specify the variable name, identify character variables with a $, and specify the correct starting and ending column for each field. 
- Question (jduan10-stat660): How to limit the number of observations that SAS reads?
- Answer (jduan10-stat660): Adding OBS=n to the INFILE statement enables you to process records only 1 through n.



[Course Textbook Chapter 6, Problem 7]
- Question (mphan12-stat660): What is the syntax for reading in character variable?
- Answer (mphan12-stat660): INPUT <VARIABLE> $ X-Y (where X is the starting position and Y is the ending position).
- Question (whu8-stat660): Does order matter in the Input statement?
- Answer(whu8-stat660): Yes.
- Question (jduan10-stat660): If there exists invalid data, does DATA step fail?
- Answer (jduan10-stat660): No, the DATA step does not fail because of the invalid data but continues to execute.



[Course Textbook Chapter 6, Problem 8]
- Question (mphan12-stat660): What happens to the variable, if the variable appears on both side of the equal sign?
- Answer (mphan12-stat660): The original value on the right is used to evaluate the expression. The result is assigned to the variable on the left side of the equal sign.
- Question (whu8-stat660): How to redefine the values of variables?
- Answer(whu8-stat660): In an assignment statement, the variable name is specified on the left side of the equal sign and an appropriate expression including the variable name on the right side of the equal sign.
- Question (jduan10-stat660): What will the assignment statement do if the arithmetic operator is missing?



[Week 5 SAS Recipe: basic_recipe_for_creating_analytic_datasets]
- Question (mphan12-stat660): What does the RETAIN statement do?
- Answer (mphan12-stat660): It causes a variable that is created by an INPUT or assignment statement to retain its value from one iteration of the DATA step to the next. In addition, the RETAIN statement can set variable order.
- Question (whu8-stat660): What’s the difference between keep and retain steps？
- Answer(whu8-stat660): Keep and retain steps modify by different aspects of the program data vector aka the PDB that SAS uses to compile and execute a data stuff.
- Question (jduan10-stat660): Does the column list order in keep statement matters?



[Week 5 SAS Recipe: adv_recipe_for_creating_analytic_datasets]
- Question (mphan12-stat660): Why is PROC SQL preferred over DATA step?
- Question (whu8-stat660): What’s the limitation of proc sql in SAS?
- Answer(whu8-stat660): Instead of loading records one-by-one, the proc sql loads all the data into memory at one time. This means only dataset that fits the memory can be processed with proc sql.
- Question (jduan10-stat660): What's the maximum dataset that can fit into memory with PROC SQL?


