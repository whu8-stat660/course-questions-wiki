## Week 1 Quiz Questions and Answers

In order to prepare your Week 1 Quiz submission, please edit ***this*** document to provide substantive questions for each Quiz Problem and SAS Recipe listed below, as well as answers to at least three questions raised.

All edits should conform to GitHub Markdown specifications (https://guides.github.com/features/mastering-markdown/) and should be committed to a branch named "week-1" in your fork of this repo. Then, after all edits have been made/committed, your Week 1 Quiz should be submitted by initiating a pull request using

- the master branch of the stat660/course_questions_wiki repo as the base fork and

- the week-1 branch of your version of the repo as the head fork.

The instructor will then review the pull request and make comments should further revision be needed. Then, after the contents of the pull request have been finalized without any merge conflicts, the instructor will merge the pull request.



********************************************************************************



[Course Structure Quiz, Problem 1]
* Question (whu8-stat660): Can we create project-group-discussion channel to discuss the group project?



[Course Structure Quiz, Problem 2]
* Question (whu8-stat660): Will posts after 12 also count for extra credits?



[Course Structure Quiz, Problem 3]
* Question (whu8-stat660): Where can we see the answers of our quiz especially for the ones we don't know the answer?



[Course Structure Quiz, Problem 4]
* Question (whu8-stat660): Where can we find information about the projects?



[Course Structure Quiz, Problem 5]
* Question (whu8-stat660): If we pass the final exam does it mean we are ready for the SAS program certification exams?



[Course Structure Quiz, Problem 6]
* Question (whu8-stat660): Besides the five achievements, what else do think is also very important in real data analysis work?
* Answer (whu8-stat660):One thing I could think about is that to be successful in real analysis work, data analyst needs to be both detail-oriented and big-picture. We need to be very focused and detail-oriented during the analysis process, because even minor changes in data could cause huge difference in result, but when come to the model-design and interpreting results, big-picture mindset would be super helpful.



[Course Structure Quiz, Problem 7]
* Question (whu8-stat660): Could we submit assignments multiple times and get grades based on the latest submission?



[Course Structure Quiz, Problem 8]
* Question (whu8-stat660): How much extra credit we could get in total? 



[Course Structure Quiz, Problem 9]
* Question (whu8-stat660):  Do you have a real carrier pigeon? (Just curious:P) 



[Course Structure Quiz, Problem 10]
* Question (whu8-stat660): Do we need to check Blackboard daily? Does all instructions are posted only in Blackboard? 



[hello_world Week 1 SAS Recipe]
* Question (whu8-stat660): Compared with R or SQL, what’s the advantage of SAS in data analytics?
* Answer (whu8-stat660): R - R is the lingua franca of statistics. It is a free and open source programming language used to perform advanced data analysis tasks. Python –Python is a multi-purpose, free and open source programming language which has become very popular in data science due to its active community and data mining libraries. SAS – SAS has been the undisputed market leader in the enterprise analytics space. It offers a huge array of statistical functions, has a good GUI for people to learn quickly and provides brilliant technical support.
SAS is extremely efficient at sequential data access, and database access through SQL is well integrated. The drag-and-drop interface makes it easy for you to create better statistical models quickly.  It has decent functional graphical capabilities, but it’s difficult to create complex graphical plots in SAS.*Reference*:https://www.datasciencecentral.com/profiles/blogs/r-python-or-sas-which-one-should-you-learn-first



[fizz_buzz Week 1 SAS Recipe]
* Question (whu8-stat660):How would SAS process the if-then-else statement?
* Answer (whu8-stat660):First, SAS checks expression-1. What happens next depends on whether or not the condition in expression-1 is met. This is why IF-THEN-ELSE statements are sometimes referred to Conditional Processing.If expression-1 is true, SAS executes statement-1 and does NOT check the remaining ELSE IF statements. SAS will then continue to process any additional code following the block of IF-THEN-ELSE statements.
If expression-1 is false, SAS will move to the next ELSE IF line and check expression-2.If expression-2 is true, SAS executes statement-2 and does NOT check the remaining ELSE IF statements. SAS will then continue to process any additional code following the block of IF-THEN-ELSE statements.If expression-2 is false, SAS will check the next ELSE IF expression.
The same process will continue until SAS gets to the last ELSE statement. This last ELSE statement does not have an expression to check, so SAS will execute the THEN statement whenever this line is read. IF-THEN-ELSE statements are processed sequentially, so the only way SAS will execute the last THEN statement is if none of the previous IF and ELSE IF conditions have been met.*Reference*:https://analytics.ncsu.edu/sesug/2013/CC-18.pdf


