# Introduction
Asdf
## What Are PHP Sessions?
PHP Sessions areblahblahablahoablabalablaalahl.
## Why Should I Use PHP Sessions?
You’ll want to use PHP Sesssions to blah blah.
# Tutorial
## Starting a PHP Session
In order to start your PHP session, you’ll have to open your session with the following line of code:

```
<?php

session_start();

?>
```

### What’s Happening?
`session_start();` will need to be at the top of the PHP files associated with your webpage. If your PHP file reroutes to other PHP files, you need to include `session_start();` to continue the session [or something like that]. 

## Setting Session Variables
One way to set session variables is by setting the variables statically in your code.
```
<?php
// Start the session
session_start();
?>
<!DOCTYPE html>
<html>
<body>

<?php
// Set session variables
$_SESSION["favcolor"] = "green";
$_SESSION["favanimal"] = "cat";
echo "Session variables are set.";
?>

</body>
</html>
```
### What’s Happening?
While running this code snippet, we can see the session variables using web inspect tools. 

[screenshot of session variables on inspect]

Alternatively, we can utilize text boxes to allow users to input their own answers to customize the site. As opposed to statically setting the session variables, users will be able to customize the site. In the previous approach, we were able to see the values we wanted, but this value would have been shown for all users, which might not have been applicable for everyone. 

[screenshot of page with text boxes, then screenshot of page with session variables being listed]

# Additional Resources
* https://www.w3schools.com/php/php_sessions.asp 
    * asdf
* https://www.geeksforgeeks.org/php-sessions/
    * asdf
* source
    * asdf
* source
    * asdf
