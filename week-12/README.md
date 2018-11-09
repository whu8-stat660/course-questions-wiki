
## Week 12 Quiz Questions and Answers

In order to prepare your Week 12 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-12" in your fork of this repo. Then, after all edits have been made/committed, your Week 12 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-12 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 16, Problem 1]
- Question (llopez37-stat660)Do we include the other variables in the keep syntax in order to allow for the if statement to go into affect? 
* Question (yli110-stat660): What types of elements can be put into an array?
* Answer (yli110-stat660): Either numeric or characteristic, as long as all the variables in the same array have same type.
- Question (anguyen152-stat660) : What is an "executable statement" ?
- Answer (anguyen152-stat660) :  DATA step statements are executable or declarative statements that can appear in the DATA step. Executable statements result in some action during individual iterations of the DATA step; declarative statements supply information to SAS and take effect when the system compiles program statements. ARRAY statement is a declarative statement.
- Question (mphan12-stat660): What is an "declarative statement"?
- Answer (mphan12-stat660):  DATA step statements are executable or declarative statements that can appear in the DATA step. Declarative statements supply information to SAS and take effect when the system compiles program statements. ARRAY statement is a declarative statement.
- Question (whu8-stat660):What's the use of an ARRAY statement?
- Answer (whu8-stat660):An ARRAY statement is used to define an array which could be referenced later.



[Course Textbook Chapter 16, Problem 2]
- Question (llopez37-stat660) Is this due to the set syntax which is setting that data set into the new data set that we wanted to create? 
- Answer (llopez37-stat660) It seems this is the case, the data step is setting the data set. 
* Question (yli110-stat660): How do you define the dimentions of arrays in SAS?
- Question (anguyen152-stat660) : It the cases we can not define how many elements in the array, what should we put in the braces ? 
- Answer (anguyen152-stat660) : We can put a '*'
- Question (mphan12-stat660): How do you define the dimentions of arrays in SAS?
- Question (whu8-stat660):What's the meaning of the parameter in the braces of an ARRAY statement?
- Answer (whu8-stat660):It indicates the number of elements in the array.



[Course Textbook Chapter 16, Problem 3]
- Question (llopez37-stat660)How would we go about getting this to print out on the output? 
* Question (yli110-stat660): How do you reference elements in an array?
- Question (anguyen152-stat660) : Why "do until" statement doesnt work in this case ? Are "do i=1 to 4;"
"do until i=4;" not the same meaning ? 
- Question (mphan12-stat660): How do you reference elements in an array?
- Question (whu8-stat660):Can the WHILE or UNTIL clause be used in the DO statment which included in an ARRAY statement?
- Answer (whu8-stat660):I don't think so.



[Course Textbook Chapter 16, Problem 4]
- Question (llopez37-stat660)Is this just an example or what would be the purpose of a code such as this? 
* Question (yli110-stat660): What's the purpose of DIM function? And how do you use it in the DO loop?
- Question (anguyen152-stat660) : Is index=0 not applied in SAS ?  
- Question (mphan12-stat660): What is the purpose of DIM function? 
- Question (whu8-stat660):How the index value is determined?
- Answer (whu8-stat660):The index value is determined by the position of the array element.



[Course Textbook Chapter 16, Problem 5]
- Question (llopez37-stat660)How would we go about printing the first 5 observations starting from the 4th observation?
- Answer (llopez37-stat6660) From what I could find this is where the start syntax might work out.
* Question (yli110-stat660): How to assign initial values for elements in an array?
- Question (anguyen152-stat660) : What's the correct syntax for DIM function ? 
- Answer (anguyen152-stat660) : DIM(array-name)
- Question (mphan12-stat660): What is the correct syntax for DIM function?
- Answer (mphan12-stat660): DIM(array-name)
- Question (whu8-stat660):What's the use of DIM funcion with array name?
- Answer (whu8-stat660):The DIM functions with the array name as the argument to process all the elements in an array.



[Course Textbook Chapter 16, Problem 6]
- Question (llopez37-stat660)Why does it print out 1 observation and not the 5 that we set obsnum to equal? 
* Question (yli110-stat660): How do you use the array to create variables in SAS DATA step?
- Question (anguyen152-stat660) : Can numeric and character variables both exist in an array ?
- Answer (anguyen152-stat660) :No. All variables that are associated with an array must be of the same type
- Question (mphan12-stat660): Can you have combination of numeric and character variables in an array?
- Answer (mphan12-stat660): No. All variables that are associated with an array must be of the same type.
- Question (whu8-stat660):What the default length of character variables created in an ARRAY statement?
- Answer (whu8-stat660):Eight.



[Course Textbook Chapter 16, Problem 7]
- Question (llopez37-stat660)An error occurs because we do not finish the If then syntax on the last line? 
- Answer (llopez37-stat660) It appears to be the case when running that the syntax runs into an error.
* Question (yli110-stat660): How do you create a temperary array that will only be used to do calcuation, and not to be included in output data sets?
- Question (anguyen152-stat660) : Why the dimension of diff array is 9 in this case ? "diff{9}"
- Question (mphan12-stat660): How are temperary arrays for calcuation created?
- Question (whu8-stat660):Can two array statements use the same index?
- Answer (whu8-stat660):Yes.



[Course Textbook Chapter 16, Problem 8]
- Question (llopez37-stat660)If there are no observations this is strictly the PDV and then the observations begin to populate?
* Question (yli110-stat660): What do you do differently when create an array with characteristic values?
- Question (anguyen152-stat660) : When should temporary arrays be used ? 
- Answer (anguyen152-stat660) : Temporary arrays are often used to perform calculation.
- Question (mphan12-stat660): When do you use temporary arrays?
- Answer (mphan12-stat660): Temporary arrays are often used to perform calculation.
- Question (whu8-stat660):What's temporary array elements?



[Week 12 SAS Recipe: recipe_to_disaggregate_counts_data]
- Question (llopez37-stat660)So for this case, would we have observations during PDV as opposed to the last problem? 
* Question (yli110-stat660): How do you diaggregate datasets? And what are the purposes to diaggregate datasets?
* Answer (yli110-stat660): Diaggregation is achieved by DO loop, which has one variable as index, and the second variable in the loop is set as a = a + 1 to indicate that the ids are increasing by 1. With diaggregation, you can get individual observations in an aggregated group. Even though that the name and other personal info is not available, the id alone is sufficient enough to indicate one person.
- Question (anguyen152-stat660) : What variable is disaggregated and what are the output variables in this example ?
- Question (mphan12-stat660): What is the purposes to diaggregate datasets?
- Answer (mphan12-stat660): With diaggregation, you can get individual observations in an aggregated group. Even though that the name and other personal info is not available, the id alone is sufficient enough to indicate one person.
- Question (whu8-stat660):Why "where not(missing(Enrollment_K12))' is needed in the recipe?



[Week 12 SAS Recipe: recipe_to_create_unique_record_id]
- Question (llopez37-stat660) How strong is the disaggregate capabilities as in can you disaggregate code that you did not manipulate yourself or do not have the raw data set? 
* Question (yli110-stat660): How do you use the automatic variable __N__ to create unique ID for each observation?
* Answer (yli110-stat660): __N__ is created and added automatically into the pdv, and it can be used in any calculations as a numeric variable. Thus by assigning the __N__ value to the ID variable, you are all set.
- Question (anguyen152-stat660) : What does this statement means "school_record_id = "school_record-"||put(_N_,z6.)" ? 
- Answer (anguyen152-stat660) : This statement is used to created unique record id with unique name "school_record-_N_" for example with _N_=15, the id will be school_record-000015
- Question (mphan12-stat660): How do you use the automatic variable _N_ to create unique ID for each observation?
- Answer (mphan12-stat660):  _N_ is created and added automatically into the pdv. Create a variable and set it equal to _N_.
- Question (whu8-stat660):How to create unique record id in SAS?


