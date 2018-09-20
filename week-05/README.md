
## Week 5 Quiz Questions and Answers

In order to prepare your Week 5 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-5" in your fork of this repo. Then, after all edits have been made/committed, your Week 5 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-5 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 6, Problem 1]
- Question (whu8-stat660): What’ the function of filename statement?
- Answer(whu8-stat660): Filename statement is used to point to the location of the external file that contains the data. Its syntax is “FILENAME fileref 'filename';”.



[Course Textbook Chapter 6, Problem 2]
- Question (whu8-stat660): What is fileref?
- Answer(whu8-stat660): Filerefs perform the same function as librefs: they temporarily point to a storage location for data. However, librefs reference SAS libraries, whereas filerefs reference external files.



[Course Textbook Chapter 6, Problem 6]
- Question (whu8-stat660): How to use the input statement?
- Answer(whu8-stat660):Input statment is used to read specific fields. You must specify the variable name, identify character variables with a $, and specify the correct starting and ending column for each field. 



[Course Textbook Chapter 6, Problem 7]
- Question (whu8-stat660): Does order matter in the Input statement?
- Answer(whu8-stat660): Yes.



[Course Textbook Chapter 6, Problem 8]
- Question (whu8-stat660): How to redefine the values of variables?
- Answer(whu8-stat660): In an assignment statement, the variable name is specified on the left side of the equal sign and an appropriate expression including the variable name on the right side of the equal sign.



[Week 5 SAS Recipe: basic_recipe_for_creating_analytic_datasets]
- Question (whu8-stat660): What’s the difference between keep and retain steps？
- Answer(whu8-stat660): Keep and retain steps modify by different aspects of the program data vector aka the PDB that SAS uses to compile and execute a data stuff.



[Week 5 SAS Recipe: adv_recipe_for_creating_analytic_datasets]
- Question (whu8-stat660): What’s the limitation of proc sql in SAS?
- Answer(whu8-stat660): Instead of loading records one-by-one, the proc sql loads all the data into memory at one time. This means only dataset that fits the memory can be processed with proc sql.


