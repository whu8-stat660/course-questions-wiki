
## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 8, Problem 3]
- Question (mphan12-stat660): When creating PROC FORMAT, where does the semi-colon go?
- Answer (mphan12-stat660): For every value statement there is a semi-colon.
- Question (anguyen152-stat660): What is an example of SAS valid new format's name ? 
- Answer (anguyen152-stat660): see $GENDERLABEL in this example 
PROC FORMAT;
    VALUE $GENDERLABEL
	  "M"   = "Male"
	  "F"   = "Female";
RUN;
- Question (llopez37-stat660) If we did not put the dollar sign, would an error occur or would the name be considered numeric by sas?



[Course Textbook Chapter 8, Problem 4]
- Question (mphan12-stat660): What happens when the library option is omitted from PROC FORMAT?
- Answer (mphan12-stat660): If you omit the library option, then formats and informats are stored in the Work Formats catalog.
- Question (anguyen152-stat660): Do we always have to declare the library name when using the "PROC FORMAT" statement ? 
- Question (llopez37-stat660) Would this be the same if the format was within a data step in terms of amount of semi colons used?
- Answer (llopez37-stat660) Yes, it holds true whether its just a format statement or within a data or proc step.



[Course Textbook Chapter 8, Problem 5]
- Question (mphan12-stat660): What are the keywords to specify the lower and upper limits of a variable's value range.
- Answer (mphan12-stat660): Keywords are Low and High.  Note that Low does not include missing numeric values.
- Question (anguyen152-stat660):Where the semicolons should be placed in the "PROC FORMAT" statement ? 
- Answer (anguyen152-stat660): They are placed after these statement : The first statement calls PROC FORMAT. The second statement is a value clause that defines the name and contents of the user-defined format. The final statement is the run statement
- Question (llopez37-stat660) Why does the range only go from A to M? 



[Course Textbook Chapter 8, Problem 6]
- Question (mphan12-stat660): How many characters can be used in a LABEL?
- Answer (mphan12-stat660): 32,767
- Question (anguyen152-stat660): What is a "label" in SAS ?
- Question (llopez37-stat660) Is there ever a situation in which 256 characters would be required if so then why?



[Course Textbook Chapter 8, Problem 7]
- Question (mphan12-stat660): When would you use OTHER in PROC FORMAT?
- Answer (mphan12-stat660): To label missing numeric values as well as any values that are not specified in a range.
- Question (anguyen152-stat660):What are the "keywords" should be noted in SAS for formatting?
- Question (llopez37-stat660) Is there a statement we can add that deletes the observation that is within the Other group or would that lean towards the sort statements?



[Course Textbook Chapter 8, Problem 8]
- Question (mphan12-stat660): What does the FORMAT procedure do?
- Answer (mphan12-stat660): PROC FORMAT stores user-defined informats and formats as entries in SAS catalogs. Formats determine how variable values are printed.
- Question (anguyen152-stat660): Why would you place a FORMAT statement in a DATA step ? 
- Question (llopez37-stat660) I see that some code can have multiple steps within it, is it possible to have multiple format statements within steps making our data more granular as it goes?



[Course Textbook Chapter 9, Problem 1]
- Question (mphan12-stat660): What are the default statistics produced by the MEANS procedure?
- Question (anguyen152-stat660): How many functions in total of the MEANS procedure ? 
- Question (llopez37-stat660) Are these the defaullt statistics produced for all descriptive statistics functions?
- Answer (llopez37-stat660) A proc means table tends to print with most descriptive analysis with these default statistics



[Course Textbook Chapter 9, Problem 2]
- Question (mphan12-stat660): What is the difference between by and class statements in PROC MEANS?
- Answer (mphan12-stat660): BY-group processing requires that your data already be sorted or indexed in the order of the BY variables. Also, the layout of BY-group results differs from the layout of CLASS group results.
- Question (anguyen152-stat660): What is the word "BY" used for ?
- Question (llopez37-stat660) Are there conflictions with that can arise with using Var, by and class statements?



[Course Textbook Chapter 9, Problem 4]
- Question (mphan12-stat660): Why would one chose BY over CLASS statement in PROC FREQ and PROC MEANS procedures?
- Answer (mphan12-stat660): Although the CLASS statement is easier to use than the BY statement because it does not require a sorting step, the BY-group processing can be more efficient when your categories might contain many levels.
- Question (anguyen152-stat660): What is the pre-condition when using "By-group process" ? 
- Question (llopez37-stat660) Does the order effect how the table comes out?



[Course Textbook Chapter 9, Problem 7]
- Question (mphan12-stat660): What does the asterisk do in PROC FREQ?
- Answer (mphan12-stat660): The asterisk in PROC FREQ creates n-way crosstabulations.  
- Question (anguyen152-stat660):How to create list output for cross-tabulations in proc freq?
- Question (llopez37-stat660) What are the limitations for proc freq on both character and numeric variables if any?
- Answer (llopez37-stat660) It seems that the frequencies could be broken down for intervals on continous variables.



[Course Textbook Chapter 9, Problem 8]
- Question (mphan12-stat660): Does order matter when listing it in PROC FREQ? Why?
- Answer (mphan12-stat660): Yes, order of the variable is important.  In n-way tables, the last two variables of the TABLES statement become the two-way rows and columns. Variables that precede the last two variables in the TABLES statement stratify the crosstabulation tables.
- Question (anguyen152-stat660): Can Frequency distributions work with variables of all types of values?
- Question (llopez37-stat660) What approach could we take with non categorical variables?



[Course Textbook Chapter 9, Problem 10]
- Question (mphan12-stat660): What does the list option do in PROC FREQ?
- Answer (mphan12-stat660): Adding the LIST option puts the frequencies in a simple, short table.
- Question (anguyen152-stat660): What are the meanings of the words after the slash ?  
- Question (llopez37-stat660) How could we change the ranges of the weights to our choosing? 



[Week 4 SAS Recipe: recipe_for_summarizing_quantitative_values]
- Question (mphan12-stat660): What are the differences bewteen PROC MEANS and PROC SUMMARY?
- Question (anguyen152-stat660):What if I want the mean and standard deviation only in the output statistics ?
- Question (llopez37-stat660) Could we simply create a seperate window of the output and put into PDF?



[Week 4 SAS Recipe: recipe_for_summarizing_qualitative_values]
- Question (mphan12-stat660): What are the differences between PROC FREQ and PROC TABULATE?
- Question (anguyen152-stat660): What is the slash (/) used for in the PROC FREQ?
- Answer (anguyen152-stat660): It indicates that what comes after are options(not variables).
- Question (llopez37-stat660) What is best practice for the order to put into tabular form?



[Week 4 SAS Recipe: recipe_for_temporarily_binning_values]
- Question (mphan12-stat660): What are the differences between VALUE and INVALUE in PROC FORMAT?
- Question (anguyen152-stat660):How to make a new table storing the binned values ? 
- Question (llopez37-stat660) Do all the criteria for binning values have to be range values and not specific values?


