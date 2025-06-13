# CSCI-4000-Assignment-6-solution

Download Here: [CSCI 4000 Assignment 6 solution](https://jarviscodinghub.com/assignment/csci-4000-assignment-6-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Question 1 – Database: PHP Chapter 4, eg008 and knowledge of SQL (15 points) Estimated time: 1 hour
• You created part the requested sql file in Assignment 3, Q1. You can copy create_db.sql from Assignment
3 and update the sql file, instead of creating a new file.
• Save question 1 files in folder “lastname_firstname_assignment6”: (1 point)
o create_db.sql
• Create a text file create_db.sql, write sql statements in the file to
o Create a MySQL database richard_ricardo_assignment_db. (1 point)
2 CSCI 4000
o In the database, create 1 table.
 student (1 point)
o Create the following fields (columns) for the table (refer to examples below for details).
 student table: studentID, name, email, GPA (5 points)
 studentID is the primary key of the student table (1 point)
o Insert test records to the student table. (5 points)
o Create a MySQL database username richardweb with password richardchocolate, with data
privileges (select, insert, update, delete) for the richard_ricardo_assignment_db database. (1
point)
o All above must be done by SQL statements in the text file create_db.sql. (0 points if not)
• Load create_db.sql in XAMPP > phpMyAdmin to create the above mentioned database.
• Note: In the real world, do NOT put sql files in a website folder. Keep it offline and safe.

Question 2 – Connect: PHP Chapter 4, eg008/9 and knowledge of SQL (5 points) Estimated time: 0 hours
• You can copy your files from Assignment 3. Technically you do not need to do anything for this question
if you finished Assignment 3.
• Save question 2 files in “lastname_firstname_assignment6”: (5 points, -5 points if there is any error)
o main.css
o richard_ricardo_database.php
o richard_ricardo_database_error.php
4 CSCI 4000
• Create web page(s) that displays the default information (example shown).
• The initial page and related outputs should look like the examples shown below.
• Create your page(s) using “richard ricardo’s kung fu school” as the page title(s).
• Create file richard_ricardo_database.php (php code only, no html code) to connect to database
o Use PDO (PHP Data Object) to interface with your MySQL database.
o Connect to the richard_ricardo_assignment_db MySQL database (created in Q1), using
username richardweb with password richardchocolate.
o Use try {} catch () {} exception handling to detect if the connection is successful.
o If the connection is not successful, show an error page richard_ricardo_database_error.php.
• Create a css file named main.css to format all pages by creating your own layout (no two students should
have the same layout). You should use the same css file to format all questions.

Question 3 – AJAX Search: PHP Chapter 4, eg008/9, SQL & AJAX (40 points) Estimated time: 2 hours • Save question 3 files in folder “lastname_firstname• The initial page and related outputs should look like the examples shown below. • Create your page(s) using “richard ricardo’s kung fu school” as the page title(s) (_assignment6”. (2 points) o index.htm o richardricardo_search.php • The initial page and related outputs should look like the examples shown below. • Create your page(s) using “richard ricardo’s kung fu school” as the page title(s) (

Question 4 – AJAX Search Split: PHP Ch 4, eg008/9, SQL, AJAX (45 points) Estimated time: 3 hours • Save question 4 files in folder “lastname_firstname_assignment6”. (2 points) o richard_ricardo_ajaxsearch_single.htm o richardricardo_search_single.php • The initial page and related outputs should look like the examples shown below. • Create your page(s) using “richard ricardo’s kung fu school” as the page title(s) (

Important: 1. If you do not put / in the above mentioned fields (as shown in the examples), you will get 0 points for the question(s). 2. No two students should submit webpages with exactly the same code, content, layout, or color combination. If found, both students will get 0 points. 3. Before adding PHP code, all html files must pass html validation at https://validator.w3.org/ without any error (and with only 1 warning). Use the validator’s “File Upload” tab to check each file. a. If you want to validate a PHP file after adding PHP code, you can temporarily rename the *.php file to *.htm file. b. When you view page source in a web browser, must be at the top of every page. In other words, all pages must be written in HTML5. (-20 points if not) c. If any html error is found, 2 points will be deducted for each error. Please validate the files before adding PHP code. 4. All css files must pass css validation at https://jigsaw.w3.org/css-validator/ without any error. 5. If your files do not pass the html and css validations, 2 points will be deducted for each html or css error found (no deduction for php error at html validation). 6. Document (comment) your HTML files (), CSS files (/* */), and PHP files (/* */ OR //). Points will be taken off for insufficient comments (, /* */, //). Submission instructions: • You need to test all document(s). • Do screen capture(s) of the input and the related output(s). Use any graphic editing software (e.g. Microsoft Paint, Adobe Fireworks, GIMP, or Microsoft Expression Design etc) to cut out the browser output (from the screen capture), paste them into a word document. • Provide 2 different test cases for each question. In other words, for each question, you may need to have 2 input screen captures and 2 related output screen captures. • Do NOT need to do screen capture(s) of html validation results and css validation results for this assignment. • Save the word document as a pdf file. You need to submit the following: 1. A pdf file containing the screen capture(s) of the web browser input and output pages, name the file lastname_firstname_assignment6.pdf. 2. All html file(s), php file(s), css file(s), and other related files (e.g. image files). Zip your file folder (lastname_firstname_assignment6) into a single zip file (or rar file) lastname_firstname_assignment6.zip. In the above example, the zip file should contain the following files and subfolders. If there is any image, there should be a \images\ subfolder. • lastname_firstname_assignment6\create_db.sql • lastname_firstname_assignment6\index.htm • lastname_firstname_assignment6\main.css • lastname_firstname_assignment6\richard_ricardo_ajaxsearch_single.htm • lastname_firstname_assignment6\richard_ricardo_database.php • lastname_firstname_assignment6\richard_ricardo_database_error.php • lastname_firstname_assignment6\richardricardo_search.php • lastname_firstname_assignment6\richardricardo_search_single.php Please submit the above mentioned two files (.pdf and .zip) to D2L digital dropbox. 9 CSCI 4000 Grading guidelines (programming questions): Your programs will be judged on several criteria, which are shown below. • Correctness (50%): Does the program compile (run) correctly? Does the program do what it’s supposed to do? • Design (20%): Are operations broken down in a reasonable way (e.g. classes and methods)? • Style (10%): Is the program indented properly? Do variables have meaningful names? • Robustness (10%): Does the program handle erroneous or unexpected input gracefully? • Documentation (10%): Do all program files begin with a comment that identifies the author, the course code, and the program date? Are all the classes, methods and data fields clearly documented (commented)? Are unclear parts of code documented (commented)? (Some items mentioned may not apply to some languages) A program that does not compile (run) will get at most 50% of the possible points

