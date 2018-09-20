
## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 6, Problem 1]
- Question (jduan10-stat660): When referring a file in an aggregate storage location, can the file extension be omitted?
- Answer (jduan10-stat660): If the file extension is omitted, SAS looks for a .dat file.



[Course Textbook Chapter 6, Problem 2]
- Question (jduan10-stat660): What’s the maximum characters can the fileref name has?
- Answer (jduan10-stat660): The name must be 1 to 8 characters long.



[Course Textbook Chapter 6, Problem 6]
- Question (jduan10-stat660): How to limit the number of observations that SAS reads?
- Answer (jduan10-stat660): Adding OBS=n to the INFILE statement enables you to process records only 1 through n.



[Course Textbook Chapter 6, Problem 7]
- Question (jduan10-stat660): If there exists invalid data, does DATA step fail?
- Answer (jduan10-stat660): No, the DATA step does not fail because of the invalid data but continues to execute.



[Course Textbook Chapter 6, Problem 8]
- Question (jduan10-stat660): What will the assignment statement do if the arithmetic operator is missing?



[Week 5 SAS Recipe: basic_recipe_for_creating_analytic_datasets]
- Question (jduan10-stat660): Does the column list order in keep statement matters?



[Week 5 SAS Recipe: adv_recipe_for_creating_analytic_datasets]
- Question (jduan10-stat660): What's the maximum dataset that can fit into memory with PROC SQL?


