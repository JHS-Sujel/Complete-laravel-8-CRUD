# Complete-laravel-8-CRUD


This is a simple laravel 8 CRUD app.
If you are new in Laravel 8 and looking for a step by step project for Laravel 8 CRUD projectapp 
then this project will help you to learn how to make a complete CRUD application using Laravel 8. 
Before starting we have to check our system requirement is okay to use Laravel 8. 
The Laravel 8 minimum requirements are listed below so that you can confirm 
either your system is okay or not to install Laravel 8 project for making a Laravel 8 CRUD application.

CRUD stands for Create, Read, Update and Delete which are operations needed in most data-driven apps that access and work with data from a database. 
In this example, we'll see how to impelement the CRUD operations in Laravel 8/7 against a MySQL database.


---


# Steps for making Laravel 8 CRUD

- Step 01: Install Laravel 8
- Step 02: Database Configuration
- Step 03: Make model & migration
- Step 04: Make controller
- Step 05: Define routes
- Step 06: Make views
- Step 07: php artisan serve


---


# How to install and run on your local system

- Clone the repository with git clone. https://github.com/JHS-Sujel/Complete-laravel-8-CRUD
- cd laravel-8-CRUD
- Run composer install or update
- Add your database config in the .env file
- Run php artisan migrate 
- Run php artisan db:seed  --seed__ (it has some seeded data for your testing)
- Run php artisan key:generate
- Run php artisan config:clear
- php artisan serve (if the server opens up, http://127.0.0.1:8000,  then we are good to go)

--- DONE

- Navigate to http://127.0.0.1:8000/blogs


![Screenshot (198)](https://user-images.githubusercontent.com/73945266/105083079-a3017580-5abe-11eb-8a7c-5d608623dde5.png)


---


# CRUD Operations


- Create a project

create() - This method has been used for load create.blade.php file. In this file user can find form for insert new records and 
filling data insert data request will be send to store() method of ProjectController.php controller class.

![Screenshot (197)](https://user-images.githubusercontent.com/73945266/105083093-a72d9300-5abe-11eb-8100-b4e8ff606b28.png)


![Screenshot (199)](https://user-images.githubusercontent.com/73945266/105083085-a4cb3900-5abe-11eb-8444-f181d464e5c5.png)


---


- View a project

show() - This method in Crud controller has been used for fetch single data details based on on value of $id argument. 
For this it has been used findOrFail() method. After fetch details it will send to view.blade.php file.

![Screenshot (200)](https://user-images.githubusercontent.com/73945266/105083088-a563cf80-5abe-11eb-84a5-df11018c749c.png)


---


- Edit a project

edit() - This method main function is fetch single data from Mysql database and load into edit or update form for make required changes.


![Screenshot (201)](https://user-images.githubusercontent.com/73945266/105083090-a5fc6600-5abe-11eb-8f01-3678f0e5bee3.png)


---


- Delete a project

delete() - Delete() method mainly used for remove single or multiple data from Mysql Database. This is last operation Crud Operation in Laravel 8 Crud tutorial series.


![Screenshot (202)](https://user-images.githubusercontent.com/73945266/105083092-a694fc80-5abe-11eb-8829-777e86aa92a9.png)


---


# License

Basically, feel free to use and re-use any way you want
