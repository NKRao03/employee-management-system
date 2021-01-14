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


Employee Management System is a centralized application to manage employee information. 
This application is built by 
	•Aditya S Karnam(1KG17CS004)(adityaskarnam@gmail.com)
	•K S Sai Nanda Kishore Rao(1KG17CS031)(nandakishore03@gmail.com)

Git Clone Link: https://github.com/NKRao03/employee-management-system.git

Functionalities:
	•Login and logout, forget password (Lock account in 5 minutes after 3 failed attempts).
	•Manage employees (Add, edit and delete).
	•Manage countries, cities, states (Add, edit and delete).
	•Manage users (Add, edit and delete).
	•Manage division (Add, edit and delete).
	•Manage departments (Add, edit and delete).
	•Make reports (export to PDF).
	•Search (with multiple combine fields).
	•Pagination
	•Validation
	•	Responsive
Hardware Requirements:
	•Windows XP or Linux equivalent OS
	•Intel Celeron or AMD equivalent processor
	•256MB of RAM

Software Requirements:
	•XAMPP  
	•Composer
	•Git Bash(If you want to clone the application)

Instructions to run the application:
	1.Go to the path where Xampp Is installed, navigate to the htdocs folder. 
	2.You can either:	
		oExtract the file provided in the CD, paste the entire folder in htdocs, OR
		oOpen command prompt(terminal), navigate to the aforementioned folder and execute the clone link provided above(RECOMMENDED)
	3.Open command prompt(terminal) in the pasted/cloned project folder, run “composer update”
	4.Rename .env.example with .env(If not already renamed)
	5.Configure database on .env file 
		oGo to the Xampp GUI, Enable/Start MySQL
		oNow in your browser, type “localhost/phpMyAdmin”
		oCreate a new empty database with the name employees_db
		oYou can either import the tables directly from the project folder to the database, OR
		oExecute “php artisan migrate”
	6.Create default user for system with “php artisan db:seed”
	7.To generate database keys, type “php artisan key:generate”
	8.Now execute “Execute: php artisan config:clear”
	9.Finally, start a local server by executing “php artisan serve”, copy the URL generated, paste it in your browser. 
	10.The default credentials are: 
		oUsername: admin@gmail.com
		oPass: admin



## License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
# employee-management-system

