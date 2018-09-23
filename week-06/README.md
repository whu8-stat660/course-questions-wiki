
## Week 6 Quiz Questions and Answers

In order to prepare your Week 6 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-6" in your fork of this repo. Then, after all edits have been made/committed, your Week 6 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-6 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 7, Problem 1]
- Question (mphan12-stat660): What items are created during the compilation phase?
- Answer (mphan12-stat660): The input buffer, program data vector (PDV) and descriptor information are created during the compilation phase.



[Course Textbook Chapter 7, Problem 2]
- Question (mphan12-stat660): What errors are detected during the compilation phase?
- Answer (mphan12-stat660): Misspelled keywords and data set names, unbalanced quotation marks, and invalid options are detected during the compilation phase.



[Course Textbook Chapter 7, Problem 3]
- Question (mphan12-stat660): What are the two phases that occurs in the DATA step process?
- Answer (mphan12-stat660): The compilation and executuion phases.  The compilation phase checks for syntax and compiles them.  During the execution phase, each raw data record is processed and is then written to the data set as an observation.



[Course Textbook Chapter 7, Problem 4]
- Question (mphan12-stat660): What does _N_ represents?
- Answer (mphan12-stat660): _N_ is an automatic variable that represents the number of times the DATA step has iterated. Typically aligns to number of observations read/created.



[Course Textbook Chapter 7, Problem 5]
- Question (mphan12-stat660): What are the possible values for _ERROR_?
- Answer (mphan12-stat660): The value of _ERROR_ is either 0 (no error exists) or 1 (one or more errors occured).



[Course Textbook Chapter 7, Problem 6]
- Question (mphan12-stat660): What is the program data vector (PDV)?
- Answer (mphan12-stat660): The PDV is a logical area in the memory where SAS builds a data set, one observation at a time.  It contains the set variables and computed variables, and the _N_ and _ERROR_ automated variables.  



[Week 6 SAS Recipe: obtain-column-information]
- Question (mphan12-stat660): What is the best approach in obtaining a full list of columns in a table?


