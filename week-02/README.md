
## Week 2 Quiz Questions and Answers

In order to prepare your Week 2 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-2" in your fork of this repo. Then, after all edits have been made/committed, your Week 2 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-2 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 2, Problem 1]
- Question (mphan12-stat660): What are the SAS names for column, row, and table?
- Answer (mphan12-stat660): Column = Variable, Row = Observation/Record, and Table = Dataset.
- Question (jduan10-stat660): What's the different between observations and variables?
- Answer (jduan10-stat660): Observations are also called rows and variables are called columns.
* Question (yli110-stat660): What are the two parts of a SAS data set?
* Answer (yli110-stat660): a descriptor portion and a data portion. 
- Question (anguyen152-stat660):What are "observations" and "variables?"
- Answer (anguyen152-stat660):"Observations" can be counted as "rows" and "variables" can be counted as "columns" 



[Course Textbook Chapter 2, Problem 2]
- Question (mphan12-stat660): There are only two program steps, what are they and what color is it highlighted in SAS? And what do they do?
- Answer (mphan12-stat660): The two steps are DATA and PROC.  They are both highlighted in dark blue font.  PROC step analyzes data, produces output, or manages SAS files.  The DATA step creates or modifies data.
- Question (jduan10-stat660): Is the run statement required between steps in SAS?
- Answer (jduan10-stat660): No, it’s not required.
* Question (yli110-stat660): How does SAS recognize the ending of a program step?
* Answer (yli110-stat660): A DATA or PROC step indicates the previous step ends. Besides, RUN and QUIT statement means the step to stop.
- Question (anguyen152-stat660): What is the purpose of the 2nd line "infile jobs;" ? 
- Answer (anguyen152-stat660): INFILE statement identifies the file to read. In this case, "table" is the input dataset and "jobs" is the file to read. 



[Course Textbook Chapter 2, Problem 3]
- Question (mphan12-stat660): When is a variable considered numeric?
- Answer (mphan12-stat660): Numeric value contain only numeric values (the numerals 0 through 9, +, -, ., and E for scientific notation).  Else the variable is character.  You can also tell if the variable is numeric when the values in the column are left aligned.
- Question (jduan10-stat660): Can a variable be both the character type and numeric type?
* Question (yli110-stat660): How does SAS treat a string of numbers if they are put into a quotation mark?
* Answer (yli110-stat660): As character
- Question (anguyen152-stat660):What are the differences between numeric and character variables? 



[Course Textbook Chapter 2, Problem 5]
- Question (mphan12-stat660): What does the option VALIDVARNAME=ANY do?
- Answer (mphan12-stat660): The VALIDVARNAME specifies the rules for valid SAS variable names that can be created and processed during a SAS session. Setting it to ANY will allow SAS to overwrite the system default settings.
- Question (jduan10-stat660): With the system option VALIDVARNAME=ANY, can variable names contain null bytes?
- Answer (jduan10-stat660): No, the names cannot contain any null bytes.
*  Question (yli110-stat660): What is a valid variable name in SAS?
- Question (anguyen152-stat660): What makes a valid variable name in SAS ?



[Course Textbook Chapter 2, Problem 8]
- Question (mphan12-stat660): What is the default length for the numeric variable?
- Answer (mphan12-stat660): Numeric variable default length is 8 bytes. But you can have a number with 16 or 17 in length.
- Question (jduan10-stat660): How long can character variable be up to?
- Answer (jduan10-stat660): 32767 bytes long.
* Question (yli110-stat660): How long can a character variable be?
- Question (anguyen152-stat660): Can we define the length for numeric variables ? and how ? 



[Course Textbook Chapter 3, Problem 5]
- Question (mphan12-stat660): How do you identify permanent dataset?
- Answer (mphan12-stat660):  If you see two-level name joined by a period, and the first word is not locwork or work, then the permanent dataset name is the second latter word of the two-level, i.e. mylib.mydata where mydata is the permanent dataset.
- Question (jduan10-stat660): How long can the SAS library name be?
- Answer (jduan10-stat660): 1 to 8 characters long.
* Question (yli110-stat660): What is the default library if you do not specify the libref in a SAS program?
* Answer (yli110-stat660): WORK
- Question (anguyen152-stat660):What is the "set" command used for ? for example:
```data mysales.totals; 
    set sales_99.salesanalysis; 
    if totalsales>50000; 
run;
```



[Course Textbook Chapter 3, Problem 6]
- Question (mphan12-stat660): What is the default value for year cutoff and the time span?
- Answer (mphan12-stat660):  The default cutoff year is 1926, and only 100-year span is read. However, you can override the default and change the value of YEARCUTOFF= to the first year of another 100-year span. For example, if you specify YEARCUTOFF=1950, then the 100-year span is from 1950 to 2049.
- Question (jduan10-stat660): Does the value of the YEARCUTOFF= system option affect only two-digit year values?
* Question (yli110-stat660): Why do you have to specify YEARCUTOFF sometimes when interpreting two-digit year values?
- Question (anguyen152-stat660):What is the YEARCUTOFF option used for ?



[Course Textbook Chapter 4, Problem 1]
- Question (mphan12-stat660): What are the two steps that should not be indented?
- Answer (mphan12-stat660):  PROC and DATA steps and the corresponding RUN/QUIT should always start in the first space of a line, i.e. never indented. Note that proc statements don't require run, but it is good practice to add it.
- Question (jduan10-stat660): Does the new steps in SAS programming always begin with DATA or PROC statements?
* Question (yli110-stat660): Despite the fact that SAS is free-format language, what is the best way to write a complete step?
- Question (anguyen152-stat660):Why indentation should be paid intention to while SAS programming?



[Course Textbook Chapter 4, Problem 3]
- Question (mphan12-stat660): What color are quote strings?
- Answer (mphan12-stat660):  Quotes are highlighted purple in SAS.
- Question (jduan10-stat660): Is the PROC PRINT statement only followed by “data=xxxxx;”?
* Question (yli110-stat660): How does SAS treat missing quotation marks?
- Question (anguyen152-stat660): Can I find the answer to this problem without understanding every code line ?



[Course Textbook Chapter 4, Problem 4]
- Question (mphan12-stat660): How and where are syntax error reported?
- Answer (mphan12-stat660):  Syntax errors are reported in the Log window displays the word “ERROR”, the line number that it occurred, and an explanation of the error.
- Question (jduan10-stat660): When does syntax errors occur?
- Answer (jduan10-stat660): Syntax errors occur when program statements do not conform to the rules of the SAS language.
* Question (yli110-stat660): What is the difference between syntax error and logic error?
- Question (anguyen152-stat660):How are syntax errors reported in SAS programs ?



[Course Textbook Chapter 4, Problem 5]
- Question (mphan12-stat660): What are example syntax errors?
- Answer (mphan12-stat660):  They are missing RUN statement, missing semicolon, or unbalance quotation mark.
- Question (jduan10-stat660): How can I know where the PROC steps receive incorrect instructions?
* Question (yli110-stat660): What will the SAS log show if you put an invalid option in a SAS statement?
- Question (anguyen152-stat660): What are common types of syntax errors in SAS ? 
- Answer (anguyen152-stat660): These are common syntax errors in SAS: misspelled SAS keyword, unmatched quotation marks, missing a semicolon, invalid statement option, invalid data set option.



[Course Textbook Chapter 4, Problem 7]
- Question (mphan12-stat660): What color are error messages in the Log window?
- Answer (mphan12-stat660):  Error and warning messages are highlighted in red in the Log window.
- Question (jduan10-stat660): Can I use PUTLOG statement to identify semantic errors?
* Question (yli110-stat660): What does the SAS log message show if you have a typo in a SAS keyword?
- Question (anguyen152-stat660):Are typos errors automatically detected in SAS ?
- Answer (anguyen152-stat660): No



[Course Textbook Chapter 4, Problem 9]
- Question (mphan12-stat660): What is the best practice to end program steps?
- Answer (mphan12-stat660):  For every DATA step, there is a RUN. For every PROC step, there should be a RUN or QUIT. But you can follow another proc step without ending the previous proc step.
- Question (jduan10-stat660): Can I just add another quotation mark in the steps to stop the DATA STEP RUNNING message?
* Question (yli110-stat660): What happened if you forgot to end a PROC step?
- Question (anguyen152-stat660):What to do if the active window displays the message DATA step running for a long time?



[Week 2 SAS Recipe: basic_recipe_for_loading_data_from_remote_Excel_file]
- Question (mphan12-stat660): The excel file extension is typically .xls, .xlsx, what does “?raw=true” do? 
- Answer (mphan12-stat660): Since I do not have access to the excel file, I'm assuming it means raw file format or pull from tab name “raw=FALSE”.  Here’s the documentation found on SAS site: [SAS Overview HTTP Procedure](https://documentation.sas.com/?cdcId=pgmsascdc&cdcVersion=9.4_3.4&docsetId=proc&docsetTarget=n0t7v16eitluu2n15ffpfeafqszs.htm&locale=en).
- Question (jduan10-stat660): Does the filename need to be 8 character under all conditions?
* Question (yli110-stat660): What does PROC HTTP do?
- Question (anguyen152-stat660):Can we edit the dataset after imported ?



[Week 2 SAS Recipe: bonus_advanced_recipe_for_loading_data_from_remote_Excel_file]
- Question (mphan12-stat660):When invoking the macro %loadDataIfNotAlreadyAvailable, the semicolon is not presented, why did SAS not error out?
- Answer (mphan12-stat660): This is because the semicolon is **NOT** required for calling macros.  When you call a self contained macro, i.e. not in data or proc steps, it is fine to include the semicolon. Here is an example where the semicolon should not be added after calling the macro:
  - proc sql;
  -  select %field_list()  
  -  from sashelp.class ;  
  - quit;
- Question (jduan10-stat660): What's the use of symbol "%" in SAS?
- Answer (jduan10-stat660): This symbol is used to revoke marco command.
* Question (yli110-stat660): What's the advantage of using Macro variables in SAS?
- Question (anguyen152-stat660):Are macros in SAS of the same use as functions in C++ ? How often is macro used in SAS ?


