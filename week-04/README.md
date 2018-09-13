
## Week 4 Quiz Questions and Answers

In order to prepare your Week 4 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-4" in your fork of this repo. Then, after all edits have been made/committed, your Week 4 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-4 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 8, Problem 3]
- Question (anguyen152-stat660): What is an example of SAS valid new format's name ? 
- Answer (anguyen152-stat660): see $GENDERLABEL in this example 
PROC FORMAT;
    VALUE $GENDERLABEL
	  "M"   = "Male"
	  "F"   = "Female";
RUN;



[Course Textbook Chapter 8, Problem 4]
- Question (anguyen152-stat660): Do we always have to declare the library name when using the "PROC FORMAT" statement ? 



[Course Textbook Chapter 8, Problem 5]
- Question (anguyen152-stat660):Where the semicolons should be placed in the "PROC FORMAT" statement ? 
- Answer (anguyen152-stat660): They are placed after these statement : The first statement calls PROC FORMAT. The second statement is a value clause that defines the name and contents of the user-defined format. The final statement is the run statement



[Course Textbook Chapter 8, Problem 6]
- Question (anguyen152-stat660): What is a "label" in SAS ?



[Course Textbook Chapter 8, Problem 7]
- Question (anguyen152-stat660):What are the "keywords" should be noted in SAS for formatting?



[Course Textbook Chapter 8, Problem 8]
- Question (anguyen152-stat660): Why would you place a FORMAT statement in a DATA step ? 



[Course Textbook Chapter 9, Problem 1]
- Question (anguyen152-stat660): How many functions in total of the MEANS procedure ? 



[Course Textbook Chapter 9, Problem 2]
- Question (anguyen152-stat660): What is the word "BY" used for ?



[Course Textbook Chapter 9, Problem 4]
- Question (anguyen152-stat660): What is the pre-condition when using "By-group process" ? 



[Course Textbook Chapter 9, Problem 7]
- Question (anguyen152-stat660):How to create list output for cross-tabulations in proc freq?



[Course Textbook Chapter 9, Problem 8]
- Question (anguyen152-stat660): Can Frequency distributions work with variables of all types of values?



[Course Textbook Chapter 9, Problem 10]
- Question (anguyen152-stat660): What are the meanings of the words after the slash ?  



[Week 4 SAS Recipe: recipe_for_summarizing_quantitative_values]
- Question (anguyen152-stat660):What if I want the mean and standard deviation only in the output statistics ?



[Week 4 SAS Recipe: recipe_for_summarizing_qualitative_values]
- Question (anguyen152-stat660): What is the slash (/) used for in the PROC FREQ?
- Answer (anguyen152-stat660): It indicates that what comes after are options(not variables).



[Week 4 SAS Recipe: recipe_for_temporarily_binning_values]
- Question (anguyen152-stat660):How to make a new table storing the binned values ? 


