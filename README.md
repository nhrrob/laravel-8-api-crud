<p align="center"><a href="https://nazmulrobin.com" target="_blank"><img src="http://laravel.nazmulrobin.com/images/nhrrob/nhrblog-logo-white.png" width="400"></a></p>

<p align="center">
<a href="https://github.com/nhrrob/laravel-8-api-crud/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/nhrrob/laravel-8-api-crud"></a>
<a href="https://github.com/nhrrob/laravel-8-api-crud/network"><img alt="GitHub forks" src="https://img.shields.io/github/forks/nhrrob/laravel-8-api-crud"></a>
<a href="https://github.com/nhrrob/laravel-8-api-crud/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/nhrrob/laravel-8-api-crud"></a>
<a href="https://github.com/nhrrob/laravel-8-api-crud/blob/master/LICENSE.md"><img alt="GitHub license" src="https://img.shields.io/github/license/nhrrob/laravel-8-api-crud"></a>

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
- Delete product
- Search By Title
- Pagination link with json data

This app created to help developers to get started with their api crud based apps.


## Install

Install commands:
``` 
- git clone https://github.com/nhrrob/laravel-8-api-crud.git 
- composer update
- add .env and update database settings
- php artisan migrate:fresh --seed
- php artisan serve

```

Use Postman to test the API.


## Note

- Login: 
    - URL: http://laravel-8-api-crud.rob/api/login 
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
<a href="https://www.nazmulrobin.com/">nazmulrobin.com</a> | <a href="https://twitter.com/nhr_rob">Twitter</a> | <a href="https://www.linkedin.com/in/nhrrob/">Linkedin</a> | <a href="mailto:robin.sust08@gmail.com">Email</a>