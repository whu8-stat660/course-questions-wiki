
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
- Question (anguyen152-stat660): What's fileref and what's filename ? 
- Answer(anguyen152-stat660): You assign a fileref by using a FILENAME statement in the same way that you assign a libref by using a LIBNAME statement.
* Question (yli110-stat660): What are the similarities between FILENAME and LIBNAME, and what are their differences?
* Answer (yli110-stat660): FILENAME is used to associate a fileref with a raw data file, whereas LIBNAME associate a libref with a SAS library. Other than that, you use FILENAME in the same way that you assign a libref.



[Course Textbook Chapter 6, Problem 2]
- Question (mphan12-stat660): What is fileref?
- Answer (mphan12-stat660): A fileref is a SAS name that is associated with the physcial location of the output file. To assign fileref, use the FILENAME statement.
- Question (whu8-stat660): What is fileref?
- Answer(whu8-stat660): Filerefs perform the same function as librefs: they temporarily point to a storage location for data. However, librefs reference SAS libraries, whereas filerefs reference external files.
- Question (jduan10-stat660): What’s the maximum characters can the fileref name has?
- Answer (jduan10-stat660): The name must be 1 to 8 characters long.
- Question (anguyen152-stat660): How to cancel a FILENAME statement ? 
* Question (yli110-stat660): Is FILENAME global? How long does it last?
* Answer (yli110-stat660): Like LIBNAME, FILENAME statements are global, and they remain in effect unitl changed, cancelled or untill the SAS session ends.



[Course Textbook Chapter 6, Problem 6]
- Question (mphan12-stat660): What are the two statements used to read in raw data?
- Answer (mphan12-stat660): The INFILE and INPUT statements are used in the DATA step for read in raw data.
- Question (whu8-stat660): How to use the input statement?
- Answer(whu8-stat660):Input statment is used to read specific fields. You must specify the variable name, identify character variables with a $, and specify the correct starting and ending column for each field. 
- Question (jduan10-stat660): How to limit the number of observations that SAS reads?
- Answer (jduan10-stat660): Adding OBS=n to the INFILE statement enables you to process records only 1 through n.
- Question (anguyen152-stat660): What does "infile" statement do ? What does "input" statement do ? 
- Answer(anguyen152-stat660):  The INFILE statement opens an external file for input or, if the file is already open, makes it the current input file. Meanwhile, the INPUT statement creates a variable using the name that you assign to each field. 
* Question (yli110-stat660): How does SAS decide the order of variables in the output data set after reading from raw data set?
* Answer (yli110-stat660): The INPUT statement specifies the variables in the order that you want it to be in the output SAS data set.



[Course Textbook Chapter 6, Problem 7]
- Question (mphan12-stat660): What is the syntax for reading in character variable?
- Answer (mphan12-stat660): INPUT <VARIABLE> $ X-Y (where X is the starting position and Y is the ending position).
- Question (whu8-stat660): Does order matter in the Input statement?
- Answer(whu8-stat660): Yes.
- Question (jduan10-stat660): If there exists invalid data, does DATA step fail?
- Answer (jduan10-stat660): No, the DATA step does not fail because of the invalid data but continues to execute.
- Question (anguyen152-stat660):  What's the dollar signs ($) used for in "input" statement ? 
- Answer(anguyen152-stat660): The dollar sign ($) identifies the variable type as character (if the variable is numeric, then nothing appears here).
* Question (yli110-stat660): What is the purpose of INPUT statement when you read raw data set into a SAS data set?



[Course Textbook Chapter 6, Problem 8]
- Question (mphan12-stat660): What happens to the variable, if the variable appears on both side of the equal sign?
- Answer (mphan12-stat660): The original value on the right is used to evaluate the expression. The result is assigned to the variable on the left side of the equal sign.
- Question (whu8-stat660): How to redefine the values of variables?
- Answer(whu8-stat660): In an assignment statement, the variable name is specified on the left side of the equal sign and an appropriate expression including the variable name on the right side of the equal sign.
- Question (jduan10-stat660): What will the assignment statement do if the arithmetic operator is missing?
- Question (anguyen152-stat660): Do we need any SAS statement to redefine the values like that ? 
* Question (yli110-stat660): How do you redefine a variable in DATA step?



[Week 5 SAS Recipe: basic_recipe_for_creating_analytic_datasets]
- Question (mphan12-stat660): What does the RETAIN statement do?
- Answer (mphan12-stat660): It causes a variable that is created by an INPUT or assignment statement to retain its value from one iteration of the DATA step to the next. In addition, the RETAIN statement can set variable order.
- Question (whu8-stat660): What’s the difference between keep and retain steps？
- Answer(whu8-stat660): Keep and retain steps modify by different aspects of the program data vector aka the PDB that SAS uses to compile and execute a data stuff.
- Question (jduan10-stat660): Does the column list order in keep statement matters?
- Question (anguyen152-stat660): How to distinguish "keep" and "retain" ? 
- Answer(anguyen152-stat660): "retain" is used to set variable order, and "keep" is used to explicitly list the columns to keep in output.
* Question (yli110-stat660): What is PDF and what is its way to read datasets from disk? In other words, how come SAS can be used for big data?



[Week 5 SAS Recipe: adv_recipe_for_creating_analytic_datasets]
- Question (mphan12-stat660): Why is PROC SQL preferred over DATA step?
- Question (whu8-stat660): What’s the limitation of proc sql in SAS?
- Answer(whu8-stat660): Instead of loading records one-by-one, the proc sql loads all the data into memory at one time. This means only dataset that fits the memory can be processed with proc sql.
- Question (jduan10-stat660): What's the maximum dataset that can fit into memory with PROC SQL?
- Question (anguyen152-stat660): Why do I see some SQL statements here ? Is it better to use PROC SQL ? 
- Answer(anguyen152-stat660): SQL is one of the many languages built into the SAS System. PROC SQL is a powerful Base SAS Procedure that combines the functionality of DATA and PROC steps into a single step. That's why we can use SQL statements under "PROC SQL". 
* Question (yli110-stat660): How to end a PROC SQL procedure? and why?


