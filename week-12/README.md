
## Week 12 Quiz Questions and Answers

In order to prepare your Week 12 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-12" in your fork of this repo. Then, after all edits have been made/committed, your Week 12 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-12 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- Question (mphan12-stat660): What is an "declarative statement"?
- Answer (mphan12-stat660):  DATA step statements are executable or declarative statements that can appear in the DATA step. Declarative statements supply information to SAS and take effect when the system compiles program statements. ARRAY statement is a declarative statement.



[Course Textbook Chapter 16, Problem 2]
- Question (mphan12-stat660): How do you define the dimentions of arrays in SAS?



[Course Textbook Chapter 16, Problem 3]
- Question (mphan12-stat660): How do you reference elements in an array?



[Course Textbook Chapter 16, Problem 4]
- Question (mphan12-stat660): What is the purpose of DIM function? 



[Course Textbook Chapter 16, Problem 5]
- Question (mphan12-stat660): What is the correct syntax for DIM function?
- Answer (mphan12-stat660): DIM(array-name)



[Course Textbook Chapter 16, Problem 6]
- Question (mphan12-stat660): Can you have combination of numeric and character variables in an array?
- Answer (mphan12-stat660): No. All variables that are associated with an array must be of the same type.



[Course Textbook Chapter 16, Problem 7]
- Question (mphan12-stat660): How are temperary arrays for calcuation created?



[Course Textbook Chapter 16, Problem 8]
- Question (mphan12-stat660): When do you use temporary arrays?
- Answer (mphan12-stat660): Temporary arrays are often used to perform calculation.



[Week 12 SAS Recipe: recipe_to_disaggregate_counts_data]
- Question (mphan12-stat660): What is the purposes to diaggregate datasets?
- Answer (mphan12-stat660): With diaggregation, you can get individual observations in an aggregated group. Even though that the name and other personal info is not available, the id alone is sufficient enough to indicate one person.



[Week 12 SAS Recipe: recipe_to_create_unique_record_id]
- Question (mphan12-stat660): How do you use the automatic variable _N_ to create unique ID for each observation?
- Answer (mphan12-stat660):  _N_ is created and added automatically into the pdv. Create a variable and set it equal to _N_.


