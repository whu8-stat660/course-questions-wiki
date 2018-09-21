
## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 6, Problem 1]
* Question (yli110-stat660): What are the similarities between FILENAME and LIBNAME, and what are their differences?
* Answer (yli110-stat660): FILENAME is used to associate a fileref with a raw data file, whereas LIBNAME associate a libref with a SAS library. Other than that, you use FILENAME in the same way that you assign a libref.



[Course Textbook Chapter 6, Problem 2]
* Question (yli110-stat660): Is FILENAME global? How long does it last?
* Answer (yli110-stat660): Like LIBNAME, FILENAME statements are global, and they remain in effect unitl changed, cancelled or untill the SAS session ends.



[Course Textbook Chapter 6, Problem 6]
* Question (yli110-stat660): How does SAS decide the order of variables in the output data set after reading from raw data set?
* Answer (yli110-stat660): The INPUT statement specifies the variables in the order that you want it to be in the output SAS data set.



[Course Textbook Chapter 6, Problem 7]
* Question (yli110-stat660): What is the purpose of INPUT statement when you read raw data set into a SAS data set?



[Course Textbook Chapter 6, Problem 8]
* Question (yli110-stat660): How do you redefine a variable in DATA step?



[Week 5 SAS Recipe: basic_recipe_for_creating_analytic_datasets]
* Question (yli110-stat660): What is PDF and what is its way to read datasets from disk? In other words, how come SAS can be used for big data?



[Week 5 SAS Recipe: adv_recipe_for_creating_analytic_datasets]
* Question (yli110-stat660): How to end a PROC SQL procedure? and why?


