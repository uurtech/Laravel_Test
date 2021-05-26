## About Task

Testing User Login with these three conditions.
- User Credentials are correct
- User Credentials are not correct
- User can access to the login endpoint

You can simple use laravel auth or passport,

Just make sure your tests can by using this command,

docker exec CONTAINER_ID sh -c "php vendor/phpunit/phpunit/phpunit"