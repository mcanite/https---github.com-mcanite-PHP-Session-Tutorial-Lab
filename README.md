# Introduction
Asdfsdfsfs

## What Are PHP Sessions?
PHP sessions are one method for storing and accessing user data across the pages of a website, storing data on a server rather than browser. 

## Why Should I Use PHP Sessions?
As stated above, PHP sessions are one method for storing user data on a server, as opposed to storing data on the browser like cookies do. 

# Tutorial
## Starting a PHP Session
In order to start your PHP session, you’ll have to open your session with the following line of code:

```
<?php
session_start();
?>
```

`session_start();` will need to be at the top of the PHP files associated with your webpage. If your PHP file reroutes to other PHP files, you will need to include `session_start();` to continue the session. 

## Setting Session Variables
One way to set session variables is by setting the variables statically in your code.
```
asdfs
```
### What’s Happening?
While running this code snippet, we can see the session variables using web inspect tools. 

[screenshot of session variables on inspe ct]

Alternatively, we can utilize text boxes to allow users to input their own answers to customize the site. As opposed to statically setting the session variables, users will be able to customize the site. In the previous approach, we were able to see the values we wanted, but this value would have been shown for all users, which might not have been applicable for everyone. 

[screenshot of page with text boxes, then screenshot of page with session variables being listed]

# Additional Resources
* [W3Schools](https://www.w3schools.com/php/php_sessions.asp)
    * W3Schools is a well-known source that provides tutorials and code examples for various coding languages, including PHP. Linked above is a page dedicated to PHP sessions, showing how to start a session, set variables, change variables, and destroy a session. This resource is especially value for those learning PHP because it includes mini quizzes relating to the language and little explanations of what's occurring in the provided code snippets. 

* [GeeksForGeeks](https://www.geeksforgeeks.org/php-sessions/)
    * GeeksForGeeks is another well-known reource containing overviews and tutorials for various coding languages, including PHP. In this PHP session tutorial, GeeksForGeeks concisely overviews the different parts about utilizing sessions in PHP, showing how to start a session, set session data, access session data, and destroying session data/whole sessions. I find this source to be especially useful for explaining the significance of PHP sessions in securely storing user data in comparison as opposed to cookies.

* [W3Docs](https://www.w3docs.com/learn-php/php-sessions.html)
    * W3Docs provides a comprehensive overview about PHP sessions with a unique emphasis on security. This resource provides short code snippets showing how to set up PHP sessions and set up variables, as well as how to secure these sessions. Here, W3Docs describes the process of securing PHP sessions to protect user data in multiple ways. 

* [Medium](https://medium.com/@patelharsh7458/php-sessions-explained-practical-usage-and-best-practices-b15df9cc7568)
    * Medium blogs range across diverse topics and this one, authored by Patel Harsh, describes best practices for implementing PHP sessions and examples of when to use PHP sessions. Additionally, this source is unique because it includes code for an elaborate registration/login system using PHP sessions. For those wanting to experiment with PHP sessions in their own code, I would highly recommend looking at this resource to see how the PHP code regarding sessions work, as well as best implementation practices.

* []()
    * 