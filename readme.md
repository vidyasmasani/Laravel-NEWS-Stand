1. Steps to prepare the source code to build/run properly
	a. Copy the project src code to xampp/wamp/lamp projects folder
	b. Change the variable 'base_path'  value to your project base path in the file project/config/settings.php
	c. Go to the root folder of project source code.
	d. Run 'composer install'
	e. If encrypt error occurs run 'php artisan key:generate'
2. Steps to create and initialize the database
	a. Create database with name cross_over_project (then no need to change env db name) or add your db name
	b. Gave the credentials of databse in .env file
	c. Change the db credentials in project/config/database.php
	d. Run 'php artisan config:cache'
	e. Run 'php artisan cache:clear'
	f. Run 'php artisan migrate'
	g. Run 'php artisan db:seed'
3. Run Application
	a. Run 'php artisan serve'
