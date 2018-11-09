
## Week 12 Quiz Questions and Answers

In order to prepare your Week 12 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-12" in your fork of this repo. Then, after all edits have been made/committed, your Week 12 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-12 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- Question (anguyen152-stat660) : What is an "executable statement" ?
- Answer (anguyen152-stat660) :  DATA step statements are executable or declarative statements that can appear in the DATA step. Executable statements result in some action during individual iterations of the DATA step; declarative statements supply information to SAS and take effect when the system compiles program statements. ARRAY statement is a declarative statement.



[Course Textbook Chapter 16, Problem 2]
- Question (anguyen152-stat660) : It the cases we can not define how many elements in the array, what should we put in the braces ? 
- Answer (anguyen152-stat660) : We can put a '*'



[Course Textbook Chapter 16, Problem 3]
- Question (anguyen152-stat660) : Why "do until" statement doesnt work in this case ? Are "do i=1 to 4;"
"do until i=4;" not the same meaning ? 



[Course Textbook Chapter 16, Problem 4]
- Question (anguyen152-stat660) : Is index=0 not applied in SAS ?  



[Course Textbook Chapter 16, Problem 5]
- Question (anguyen152-stat660) : What's the correct syntax for DIM function ? 
- Answer (anguyen152-stat660) : DIM(array-name)



[Course Textbook Chapter 16, Problem 6]
- Question (anguyen152-stat660) : Can numeric and character variables both exist in an array ?
- Answer (anguyen152-stat660) :No. All variables that are associated with an array must be of the same type



[Course Textbook Chapter 16, Problem 7]
- Question (anguyen152-stat660) : Why the dimension of diff array is 9 in this case ? "diff{9}"



[Course Textbook Chapter 16, Problem 8]
- Question (anguyen152-stat660) : When should temporary arrays be used ? 
- Answer (anguyen152-stat660) : Temporary arrays are often used to perform calculation.



[Week 12 SAS Recipe: recipe_to_disaggregate_counts_data]
- Question (anguyen152-stat660) : What variable is disaggregated and what are the output variables in this example ?



[Week 12 SAS Recipe: recipe_to_create_unique_record_id]
- Question (anguyen152-stat660) : What does this statement means "school_record_id = "school_record-"||put(_N_,z6.)" ? 
- Answer (anguyen152-stat660) : This statement is used to created unique record id with unique name "school_record-_N_" for example with _N_=15, the id will be school_record-000015


