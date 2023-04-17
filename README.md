## Description: 
Used to manage employee details in a company. The system makes use of single centralized database to maintain records of all the employees. Authentication process is implemented to allow only the authorized members to register and view employee data. All the details like, department, division, city, state, number of employees, employee report etc. are all stored in the database. The technologies used are HTML, CSS, Javascript and PHP. Laravel framework is used to create an MVC based project. 

## Available functionalities:

+ Login and logout, forget password  (Lock account in 5 minutes after 3 failed attempts).

+ Manage employees (Add, edit and delete).

+ Manage countries, cities, states (Add, edit and delete).

+ Manage users (Add, edit and delete).

+ Manage division (Add, edit and delete).

+ Manage departments (Add, edit and delete).

+ Make reports (export to PDF).

+ Search (with multiple combine fields).

+ Pagination

+ Validation

+ Responsive

### Employee Management System is a centralized application to manage employee information. 
### This application is built by 
+ K S Sai Nanda Kishore Rao(1KG17CS031)(nandakishore03@gmail.com)
+ Aditya S Karnam(1KG17CS004)(adityaskarnam@gmail.com)


## Hardware Requirements:
+ Windows XP or Linux equivalent OS
+ Intel Celeron or AMD equivalent processor
+ 256MB of RAM

## Software Requirements:
+ XAMPP  
+ Composer
+ Git Bash(If you want to clone the application)

## Instructions to run the application:
+ Go to the path where Xampp Is installed, navigate to the htdocs folder. 
+ You can either:	
+ Extract the file provided in the CD, paste the entire folder in htdocs, OR
+ Open command prompt(terminal), navigate to the aforementioned folder and execute the clone link provided above(RECOMMENDED)
+ Open command prompt(terminal) in the pasted/cloned project folder, run “composer update”
+ Rename .env.example with .env(If not already renamed)
+ Configure database on .env file 
+ Go to the Xampp GUI, Enable/Start MySQL
+ Now in your browser, type “localhost/phpMyAdmin”
+ Create a new empty database with the name employees_db
+ You can either import the tables directly from the project folder to the database, OR
+ Execute “php artisan migrate”
+ Create default user for system with “php artisan db:seed”
+ To generate database keys, type “php artisan key:generate”
+ Now execute “Execute: php artisan config:clear”
+ Finally, start a local server by executing “php artisan serve”, copy the URL generated, paste it in your browser. 
+ The default credentials are: 
+ Username: admin@gmail.com
+ Pass: admin



## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
# employee-management-system

