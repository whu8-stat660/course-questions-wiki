
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



[Course Textbook Chapter 16, Problem 2]
- Question (llopez37-stat660) Is this due to the set syntax which is setting that data set into the new data set that we wanted to create? 
- Answer (llopez37-stat660) It seems this is the case, the data step is setting the data set. 
* Question (yli110-stat660): How do you define the dimentions of arrays in SAS?



[Course Textbook Chapter 16, Problem 3]
- Question (llopez37-stat660)How would we go about getting this to print out on the output? 
* Question (yli110-stat660): How do you reference elements in an array?



[Course Textbook Chapter 16, Problem 4]
- Question (llopez37-stat660)Is this just an example or what would be the purpose of a code such as this? 
* Question (yli110-stat660): What's the purpose of DIM function? And how do you use it in the DO loop?



[Course Textbook Chapter 16, Problem 5]
- Question (llopez37-stat660)How would we go about printing the first 5 observations starting from the 4th observation?
- Answer (llopez37-stat6660) From what I could find this is where the start syntax might work out.
* Question (yli110-stat660): How to assign initial values for elements in an array?



[Course Textbook Chapter 16, Problem 6]
- Question (llopez37-stat660)Why does it print out 1 observation and not the 5 that we set obsnum to equal? 
* Question (yli110-stat660): How do you use the array to create variables in SAS DATA step?



[Course Textbook Chapter 16, Problem 7]
- Question (llopez37-stat660)An error occurs because we do not finish the If then syntax on the last line? 
- Answer (llopez37-stat660) It appears to be the case when running that the syntax runs into an error.
* Question (yli110-stat660): How do you create a temperary array that will only be used to do calcuation, and not to be included in output data sets?



[Course Textbook Chapter 16, Problem 8]
- Question (llopez37-stat660)If there are no observations this is strictly the PDV and then the observations begin to populate?
* Question (yli110-stat660): What do you do differently when create an array with characteristic values?



[Week 12 SAS Recipe: recipe_to_disaggregate_counts_data]
- Question (llopez37-stat660)So for this case, would we have observations during PDV as opposed to the last problem? 
* Question (yli110-stat660): How do you diaggregate datasets? And what are the purposes to diaggregate datasets?
* Answer (yli110-stat660): Diaggregation is achieved by DO loop, which has one variable as index, and the second variable in the loop is set as a = a + 1 to indicate that the ids are increasing by 1. With diaggregation, you can get individual observations in an aggregated group. Even though that the name and other personal info is not available, the id alone is sufficient enough to indicate one person.



[Week 12 SAS Recipe: recipe_to_create_unique_record_id]
- Question (llopez37-stat660) How strong is the disaggregate capabilities as in can you disaggregate code that you did not manipulate yourself or do not have the raw data set? 
* Question (yli110-stat660): How do you use the automatic variable __N__ to create unique ID for each observation?
* Answer (yli110-stat660): __N__ is created and added automatically into the pdv, and it can be used in any calculations as a numeric variable. Thus by assigning the __N__ value to the ID variable, you are all set.


