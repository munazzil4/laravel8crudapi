## Laravel CRUD API with Auth
Basic Laravel CRUD API application included with Authentication Module & Product Module. It's included with JWT authentication and Swagger API format.

----

### Language & Framework Used:
1. PHP
1. Laravel

```bash
git clone https://github.com/munazzil4/laravel8crudapi
```
2. Go to the project drectory by `cd laravel8crudapi` & Run the 
2. Create `.env` file & Copy `.env.example` file to `.env` file
3. Create a database called - `laravel_basic_crud`.
4. Now migrate and seed database to complete whole project setup by running this-
``` bash
php artisan migrate:refresh --seed
```
It will create `21` Users and `103` Dummy Products.
5. Run the server - 
``` bash
php artisan serve
```
6. Open Browser - 
http://127.0.0.1:8000 & go to API Documentation -
http://127.0.0.1:8000/api/documentation
7. You'll see a Swagger Panel.


### Procedure
1. First Login with the given credential or any other user credential
1. Set bearer token to Swagger Header or Post Header as Authentication
1. Hit Any API, You can also hit any API, before authorization header data set to see the effects.

