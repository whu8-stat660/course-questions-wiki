
## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- Question (mphan12-stat660): How do you calculate the average in SQL?
- Question (anguyen152-stat660) :Can we write mean(Var1, Var2, Var3, Var4) instead of mean(of var1-var4)? 
- Answer (anguyen152-stat660) :Yes. We can. Look at the MEAN syntax : MEAN(argument-1<,...argument-n>)
- Question (llopez37-stat660) What if the variables are not sequential such as this example?
- Answer (llopez37-stat660) It seems that you would list out the variables while seperating them with commas
* Question (yli110-stat660): How do you calculate the mean of a list of variables in MEAN() statement in SAS?
* Answer (yli110-stat660): don't forget to include of to indicate the list. This is very different from MEAN() in R, which only takes one vector and compute the mean for that factor.



[Course Textbook Chapter 14, Problem 2]
- Question (mphan12-stat660): Can calculations be done on character variables?
- Answer (mphan12-stat660): Yes, by default, SAS tries to convert the variable values to numeric. Whenever data is automatically converted, a message is written to the SAS log stating that the conversion has occurred.
- Question (anguyen152-stat660) :When will SAS automatically convert characters to numeric values ? 
- Question (llopez37-stat660) How does this work with multiple character variables, even with ones that have no numeric value within it?
* Question (yli110-stat660): What happens when SAS automatically converts a character variable into numeric?



[Course Textbook Chapter 14, Problem 3]
- Question (mphan12-stat660): How do you convert character values to numeric values?
- Answer (mphan12-stat660): Use the INPUT function to convert character data values to numeric values. 
- Question (anguyen152-stat660) :What does "comma7." in this statement "TargetNo=input(target,comma7.)"  mean ?
- Question (llopez37-stat660) Is the number after comma based on the character length of your variable? 
* Question (yli110-stat660): Which statement is used to convert character values to numeric values?
* Answer (yli110-stat660): INPUT



[Course Textbook Chapter 14, Problem 4]
- Question (mphan12-stat660): What does a double pipe || do?
- Answer (mphan12-stat660): This is the concatenation operator (||).  The concatenation operator concatenates character values. The operator can be expressed as || (two vertical bars), ¦¦ (two broken vertical bars), or !!( two exclamation points).
- Question (anguyen152-stat660) :What does the value 4.1 in this statement "Location=dept||'/'||put(sitenum,4.1)" mean?
- Question (llopez37-stat660) Is there another way to change numeric to character variable outside of using input and put syntax?
* Question (yli110-stat660): Which statement is used to convert numeric values to character values?
* Answer (yli110-stat660): PUT



[Course Textbook Chapter 14, Problem 5]
- Question (mphan12-stat660): What does the MDY function do?
- Answer (mphan12-stat660): The MDY function returns a SAS date value from month, day, and year values. The MDY function accepts two-digit values for the year, but SAS interprets two-digit values according to the 100-year span that is set by the YEARCUTOFF= system option. The default value of YEARCUTOFF= is 1926.
- Question (anguyen152-stat660) :What does the YEARCUTOFF function do ? 
- Question (llopez37-stat660) Do we use 2020 only because of the confusion within the 100 year gap or do we always list out the entire year?
- Answer (llopez37-stat660) This appears to be due to the 100 year case
* Question (yli110-stat660): How does YEARCUTOFF = defines the two-digit year?



[Course Textbook Chapter 14, Problem 6]
- Question (mphan12-stat660): The variable Address2 contains values such as Piscataway, NJ. What is another way to assign the two-letter state abbreviations to a new variable named State?
- Question (anguyen152-stat660) :What's the difference btw scan and substr function?
- Answer (anguyen152-stat660) : SCAN extracts words within a value that is marked by delimiters. SUBSTR extracts a portion of a value by starting at a specified location. The SUBSTR function is best used when you know the exact position of the string that you want to extract from the character value. It is unnecessary to mark the string by delimiters.  The SUBSTR function is the best choice to extract class level information from ID. By contrast, the SCAN function is best used during the following actions: You know the order of the words in the character value. The starting position of the words varies. The words are marked by some delimiter.
- Question (llopez37-stat660) How does this know that the 2 is dictating the state part versus the city part and abberviating it? 
* Question (yli110-stat660): Which statement do you use to extract word from a character value?
* Answer (yli110-stat660): SCAN(), please note that in SCAN, you first define the character string, then the position of the extraction starting point, and delimiter if it's not one the defaults.



[Course Textbook Chapter 14, Problem 7]
- Question (mphan12-stat660): What is the difference between TRANWRD and SUBSTR?
- Question (anguyen152-stat660) :Can scan and subst function be interchangable in this case ?
- Question (llopez37-stat660) Similar to the previous question, what happens to the last letter and how would we go about seperating both letters? 
* Question (yli110-stat660): Which statement do you use to extract a subset string from a character value?
* Answer (yli110-stat660): SUBSTR()



[Course Textbook Chapter 14, Problem 10]
- Question (mphan12-stat660): What is the difference between INDEX and SCAN?
- Question (anguyen152-stat660) :Can we use FIND function here instead of using INDEX ? 
- Question (llopez37-stat660) What would be the syntax to make it case-sensitive? 
* Question (yli110-stat660): When searching a subset string from a character value, how do you make the search case-sensitive, and how do you make the search case-insensitive?



[Week 10 SAS Recipe: basic_recipe_for_combining_data_vertically]
- Question (mphan12-stat660): When combining the data vertically, will using a MERGE statement create different results than SET statement?
- Question (anguyen152-stat660) :How will missing values be treated as a result in this recipe ? 
- Question (llopez37-stat660) When combining two sets that do not have similar variables would we get an error?
- Answer (llopez37-stat660) It seems that we would extend the amount of columns and then gain missing variables for each observation given that the variable does not exist
* Question (yli110-stat660): How do you create an indicator variable in the SET statement when combining datasets vertically?



[Week 10 SAS Recipe: adv_recipe_for_combining_data_vertically]
- Question (mphan12-stat660): What does the SELECT * do?
- Answer (mphan12-stat660): Selects ALL the columns in the table.
- Question (anguyen152-stat660) : What does the  "union all corr" statement mean ? 
- Answer (anguyen152-stat660) :If the keywords ALL and CORR are used together, the UNION operator will display all rows in the two tables, both unique and duplicate, based on the columns that have the same name.
- Question (llopez37-stat660) When would the limitations of RAM and proc sql realistically take place given the power of many modern machines? 
* Question (yli110-stat660): What is the tradeoff for using PROC SQL to combine datasets vertically?


