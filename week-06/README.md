
## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 7, Problem 1]
- Question (llopez37-stat660) Is this the best way to determine whether to use proc logic statements to find errors?
- Question (whu8-stat660): What’s the two phases processed in a SAS DATA step?
- Answer(whu8-stat660): Compilation phase and execution phase. During the compilation phase, the program data vector is created. The descriptor portion of the new SAS data set is created at the end of the compilation phase. Observations are not written until the execution phase.
- Question (mphan12-stat660): What items are created during the compilation phase?
- Answer (mphan12-stat660): The input buffer, program data vector (PDV) and descriptor information are created during the compilation phase.
* Question (yli110-stat660): What are created in the DATA compilation phase?
* Answer (yli110-stat660): input buffer, program data vector, descriptor portion.
- Question (jduan10-stat660): Does SAS read automatic data to the output dataset?
- Answer (jduan10-stat660): No, SAS does not read these data to the output.
- Question (anguyen152-stat660): What does SAS create during compilation phase ?
- Answer (anguyen152-stat660) : At the bottom of the DATA step — in most cases, when a RUN statement is encountered — the compilation phase is complete, and the descriptor portion of the new SAS data set is created.



[Course Textbook Chapter 7, Problem 2]
- Question (llopez37-stat660) Does SAS also scan each step for logic errors or does that end the compilation phase? 
- Answer (llopez37-stat660) From what I could find it seems this is why proc logic exists.
- Question (whu8-stat660):  What are syntax errors?
- Answer(whu8-stat660): Syntax checking can detect common errors such as invalid options or missing punctuation, but not the values of variables and formats.
- Question (mphan12-stat660): What errors are detected during the compilation phase?
- Answer (mphan12-stat660): Misspelled keywords and data set names, unbalanced quotation marks, and invalid options are detected during the compilation phase.
* Question (yli110-stat660): What are common syntax errors?
- Question (jduan10-stat660): When will the input buffer be created?
- Answer (jduan10-stat660): The buffer is created only when the DATA step reads raw data. 
- Question (anguyen152-stat660): Will SAS point out the exact syntax errors (if exist) for me ?  
- Answer (anguyen152-stat660) : If SAS can interpret a syntax error, the DATA step compiles and executes; if SAS cannot interpret the error, the DATA step compiles but doesn't execute. 



[Course Textbook Chapter 7, Problem 3]
- Question (llopez37-stat660) Is each record per data point or per line? 
- Question (whu8-stat660): How does the DATA step execute?
- Answer(whu8-stat660): The DATA step executes once for each record in the input file, unless otherwise directed.
- Question (mphan12-stat660): What are the two phases that occurs in the DATA step process?
- Answer (mphan12-stat660): The compilation and executuion phases.  The compilation phase checks for syntax and compiles them.  During the execution phase, each raw data record is processed and is then written to the data set as an observation.
* Question (yli110-stat660): How do you compare DATA step and loop?
* Answer (yli110-stat660): They are quite similar to some extents, as both will keep going unless running into a stop mark.
- Question (jduan10-stat660): Does DATA step create observation one by one or all at a time?
- Question (anguyen152-stat660): How does SAS process records with missing values ? 
- Answer (anguyen152-stat660): SAS assigns missing values to prevent problems from arising. If you use a missing value in an arithmetic calculation, SAS sets the result of that calculation to missing. Then, if you use that result in another calculation, the next result is also missing. This action is called propagation of missing values. SAS prints notes in the log to notify you which arithmetic expressions have missing values and when they were created; however, processing continues.



[Course Textbook Chapter 7, Problem 4]
- Question (llopez37-stat660) Would fixing this error come down to the log or can we use a statement to identify why this error occurred?
- Question (whu8-stat660): What does the _N_ automatic variable represents?
- Answer(whu8-stat660): The _N_ automatic variable represents the number of times the DATA step has iterated.
- Question (mphan12-stat660): What does _N_ represents?
- Answer (mphan12-stat660): _N_ is an automatic variable that represents the number of times the DATA step has iterated. Typically aligns to number of observations read/created.
* Question (yli110-stat660): What are the possible values for the variable __ERROR__?
* Answer (yli110-stat660): 0 or 1.
- Question (jduan10-stat660): Is the way to represent missing numeric values the same as the way to represent missing characters?
- Answer (jduan10-stat660): No, missing numeric values are represented by periods, and missing character values are represented by blanks.
- Question (anguyen152-stat660): Why the values of the remaining variables are set "missing" ?



[Course Textbook Chapter 7, Problem 5]
- Question (llopez37-stat660) Is there a way to change it from a binary level to show an actual number of errors?
- Answer (llopez37-stat660) It seems like the errors will show up on logs so binary will suffice. 
- Question (whu8-stat660): What would the value of _ERROR_ would be?
- Answer(whu8-stat660): 0 or 1. Zero means there is no data error while 1 represents one or multiple errors.
- Question (mphan12-stat660): How does the DEBUG (i.e. DATA dsname / DEBUG) identify errors efficiently?
* Question (yli110-stat660): What does each value in the previous problem mean?
- Question (jduan10-stat660): Does ERROR_ remain 0 at the beginning of every iteration?
- Question (anguyen152-stat660): Will SAS still run after errors ?



[Course Textbook Chapter 7, Problem 6]
- Question (llopez37-stat660) How does the order operate with multiple iteration steps? 
- Question (whu8-stat660): How could we arrange the order of variables in a new SAS data set？
- Answer(whu8-stat660): We could arrange the order by defining it in the DATA step.
- Question (mphan12-stat660): What is the program data vector (PDV)?
- Answer (mphan12-stat660): The PDV is a logical area in the memory where SAS builds a data set, one observation at a time.  It contains the set variables and computed variables, and the _N_ and _ERROR_ automated variables.  
* Question (yli110-stat660): In the DATA step, what does SAS do when it initializes variables?
- Question (jduan10-stat660): Does the remaining values reset to missing at the beginning of each loop?
- Question (anguyen152-stat660): What occurs at the end of an iteration of the DATA step?



[Week 6 SAS Recipe: obtain-column-information]
- Question (llopez37-stat660) How accurate is proc sql with fishers data compared to R? 
- Answer (llopez37-stat660) Seems it depends on the discrimination analysis approach you take. 
- Question (whu8-stat660): What’s the use of dictionary library in approach 3?
- Question (mphan12-stat660): What is the best approach in obtaining a full list of columns in a table?
* Question (yli110-stat660): What are the three appoaches to obtain columns information in SAS?
- Question (jduan10-stat660): Can we paste the PROC SQL output information into a Excel file that is not empty?
- Question (anguyen152-stat660): Can we print out the dataset and then choose the names of the columns manually ? 


