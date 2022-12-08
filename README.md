# Website-Authentication
## Control access

Once someone is logged in a session variable can be used to store the user credentials, so they are not required to log in on every page.
Use  password_hash function in PHP to store hash code of password in the database for more security.
“Authentication.php” class is handle all the functionality needed to check if auser has access to a web page, logout, creart new user and update password functionality.

## Protecting pages from unauthorised access

To ensure pages cannot be accessed by users that are not authorised a check needs to be made for each file that cannot be accessed.

