<p align="center">
<a href="https://github.com/mauriciovater21/test-api-laravel/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/mauriciovater21/test-api-laravel"></a>
<a href="https://github.com/mauriciovater21/test-api-laravel/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/mauriciovater21/test-api-laravel"></a>
<a href="https://github.com/mauriciovater21/test-api-laravel/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/mauriciovater21/test-api-laravel"></a>
<a href="https://github.com/mauriciovater21/test-api-laravel/blob/master/LICENSE.md"><img alt="GitHub license" src="https://img.shields.io/github/license/mauriciovater21/test-api-laravel"></a>

</p>

## Laravel 8 API Crud (Passport)

Laravel 8 API Crud is a basic RESTful API crud app built with Laravel 8 and Passport. In this project a rest api created for managing product crud operations. 

Features (API) include:

- Laravel passport package
- Authentication using passport
- Logout to remove old tokens 
- Create product.
- List products.
- Update product.


## Install

Install commands:
``` 
- git clone https://github.com/mauriciovater21/test-api-laravel.git 
- composer update
- add .env and update database settings
- php artisan migrate:fresh --seed
- composer require laravel/passport
- php artisan passport:install
- php artisan key:generate
- php artisan serve

```

Use Postman to test the API.


## Note

- Login: 
    - URL: http://your-localhost/api/login 
    - Method: POST
    - Insert email and password: Body tab => x-www-form-urlencode
    - Press Enter to get Bearer token;
    - For future request add this token: 
      <br>Authorization tab: Type => Bearer Token; Insert token.
    
- Insert/Update:
    - Use Body tab => x-www-form-urlencode : Add title key and its value
    - Another way: Body tab => raw : select json type 
- Demo User (database/seeders/DatabaseSeeder.php): 
<br> ```admin@admin.com/password```


## License

The Laravel 8 Crud is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).


## Contact

Feel free to contact:  
<a href="https://www.linkedin.com/in/mauriciovater">Mauricio Vater</a> | <a href="mailto:mauriciovater21@gmail.com">Email</a>