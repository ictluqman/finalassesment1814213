# finalassesment1814213
## a. Name and Matric No.
NAME: WAN AHMAD LUQMAN AL-HAKIM WAN AZMI 

MATRIC NO:1814213
## b. Title of the web application.
Picturest
## c. Introduction of web application.
Picturest is a web application for an picture enthusiast to post their picture in a web application as their diaries.
## d. Objective of the enhancement.
-To implement the best practices of security in a web application
-To secure a web application from the attackers
-To enhance the existing security method applied in the web application
## e. Web Application Security Enhancement which includes:
######  i. Input Validation
- Client side
-In client side input validation, whitelisting technique being implemented into the login page as 
the user can only insert characters in name textfield not other special characters or numbers.For the password, users 
need to insert 8 characters of password.
- Server side
######  ii. Authentication 
– To authenticate the user, the database check if the users entered the registered email or not.If not, the message
"These credentials do not match our records." will display.Users can only register with one e-mail.
######  iii. Authorization 
– A registered users can only post,delete and edit the picture. Other than that, if the users try to access 
the post page without login, the 404 page will display.
######  iv. XSS and CSRF Prevention 
– CSRF token was used to  to verify that the authenticated user is the person actually making the requests to the application. Laravel blade function 
can prevent the XSS attack with the echo statement. Sanitizing the user input validation can also stop the  XSS attack. Any script inserted 
will be treated as plain text only.
######  v. Database Security Principles 
– Eloquent ORM was implemented on this web application so that the program  can only
reads and writes data to an SQL database without writing a single raw SQL query
######  vi. File Security Principles 
– Detailed error of a web application are vulnerabilities that can be exploited. APP_BUG must be turn off
to enhance your web server files?
##  f. References.
Sullivan, B., & Liu, V. (2011). Web application security: A beginner’s guide (1st
ed.). USA: McGraw Hill.
https://madewithlaravel.com/laravel-xss-protection
https://laracasts.com/discuss/channels/eloquent/laravel-and-sql-injections


