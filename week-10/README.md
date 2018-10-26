
## Week 10 Quiz Questions and Answers

In order to prepare your Week 10 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-10" in your fork of this repo. Then, after all edits have been made/committed, your Week 10 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-10 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Textbook Chapter 14, Problem 1]
- Question (anguyen152-stat660) :Can we write mean(Var1, Var2, Var3, Var4) instead of mean(of var1-var4)? 
- Answer (anguyen152-stat660) :Yes. We can. Look at the MEAN syntax : MEAN(argument-1<,...argument-n>)



[Course Textbook Chapter 14, Problem 2]
- Question (anguyen152-stat660) :When will SAS automatically convert characters to numeric values ? 



[Course Textbook Chapter 14, Problem 3]
- Question (anguyen152-stat660) :What does "comma7." in this statement "TargetNo=input(target,comma7.)"  mean ?



[Course Textbook Chapter 14, Problem 4]
- Question (anguyen152-stat660) :What does the value 4.1 in this statement "Location=dept||'/'||put(sitenum,4.1)" mean?



[Course Textbook Chapter 14, Problem 5]
- Question (anguyen152-stat660) :What does the YEARCUTOFF function do ? 



[Course Textbook Chapter 14, Problem 6]
- Question (anguyen152-stat660) :What's the difference btw scan and substr function?
- Answer (anguyen152-stat660) : SCAN extracts words within a value that is marked by delimiters. SUBSTR extracts a portion of a value by starting at a specified location. The SUBSTR function is best used when you know the exact position of the string that you want to extract from the character value. It is unnecessary to mark the string by delimiters.  The SUBSTR function is the best choice to extract class level information from ID. By contrast, the SCAN function is best used during the following actions: You know the order of the words in the character value. The starting position of the words varies. The words are marked by some delimiter.



[Course Textbook Chapter 14, Problem 7]
- Question (anguyen152-stat660) :Can scan and subst function be interchangable in this case ?



[Course Textbook Chapter 14, Problem 10]
- Question (anguyen152-stat660) :Can we use FIND function here instead of using INDEX ? 



[Week 10 SAS Recipe: basic_recipe_for_combining_data_vertically]
- Question (anguyen152-stat660) :How will missing values be treated as a result in this recipe ? 



[Week 10 SAS Recipe: adv_recipe_for_combining_data_vertically]
- Question (anguyen152-stat660) : What does the  "union all corr" statement mean ? 
- Answer (anguyen152-stat660) :If the keywords ALL and CORR are used together, the UNION operator will display all rows in the two tables, both unique and duplicate, based on the columns that have the same name.


