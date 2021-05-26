## About Task

Please create a fork with this repo and share your repository via email. and make sure you commit on every time you implement or tests something ( follow micro-commit approach ) 

Testing User Login with these three conditions.
- User Credentials are correct
- User Credentials are not correct
- User can access to the login endpoint

You can simple use laravel auth or passport,

Just make sure your tests can be called by using this command,

``` docker exec CONTAINER_ID sh -c "php vendor/phpunit/phpunit/phpunit" ```