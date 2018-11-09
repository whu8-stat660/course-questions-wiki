
## Week 12 Quiz Questions and Answers

In order to prepare your Week 12 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-12" in your fork of this repo. Then, after all edits have been made/committed, your Week 12 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-12 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 16, Problem 1]
* Question (yli110-stat660): What types of elements can be put into an array?
* Answer (yli110-stat660): Either numeric or characteristic, as long as all the variables in the same array have same type.



[Course Textbook Chapter 16, Problem 2]
* Question (yli110-stat660): How do you define the dimentions of arrays in SAS?



[Course Textbook Chapter 16, Problem 3]
* Question (yli110-stat660): How do you reference elements in an array?



[Course Textbook Chapter 16, Problem 4]
* Question (yli110-stat660): What's the purpose of DIM function? And how do you use it in the DO loop?



[Course Textbook Chapter 16, Problem 5]
* Question (yli110-stat660): How to assign initial values for elements in an array?



[Course Textbook Chapter 16, Problem 6]
* Question (yli110-stat660): How do you use the array to create variables in SAS DATA step?



[Course Textbook Chapter 16, Problem 7]
* Question (yli110-stat660): How do you create a temperary array that will only be used to do calcuation, and not to be included in output data sets?



[Course Textbook Chapter 16, Problem 8]
* Question (yli110-stat660): What do you do differently when create an array with characteristic values?



[Week 12 SAS Recipe: recipe_to_disaggregate_counts_data]
* Question (yli110-stat660): How do you diaggregate datasets? And what are the purposes to diaggregate datasets?
* Answer (yli110-stat660): Diaggregation is achieved by DO loop, which has one variable as index, and the second variable in the loop is set as a = a + 1 to indicate that the ids are increasing by 1. With diaggregation, you can get individual observations in an aggregated group. Even though that the name and other personal info is not available, the id alone is sufficient enough to indicate one person.



[Week 12 SAS Recipe: recipe_to_create_unique_record_id]
* Question (yli110-stat660): How do you use the automatic variable __N__ to create unique ID for each observation?
* Answer (yli110-stat660): __N__ is created and added automatically into the pdv, and it can be used in any calculations as a numeric variable. Thus by assigning the __N__ value to the ID variable, you are all set.


