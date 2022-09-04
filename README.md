# Installation

1. Download the repository or clone using this command in the terminal.
 ```
 git clone https://github.com/msdelver/ShopManagementSystem.git

```

2. Go into the project folder. or use this command in the terminal 
```
cd Shop-Management-System
```

3. rename the file name `.env.example` to `.env` or copy it and rename paste it at the project root and name it `.env`.You can simply use this command.
```
cp .env.example .env
```

4. Generate app key using this command.
```php artisan key:generate ```

5. setup your database and your app name in the .env file 

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=

```

6. Install dependencies using the following command
```
composer install

```

7. Run the following command in the terminal to run migrations and seeds

 ```
 php artisan migrate:fresh --seed
 ```
 You can also import the tms.sql file in the database folder. 

8. Install npm packages
```
npm install; npm run dev
```
9. Start the development server in the terminal using 

```
php artisan serve
```

10. Open your browser and go to the address in the terminal.Usually like this 

```
http://127.0.0.1:8000/

```

11. Login to the default user :

```
username: admin
password: admin

```

12. Star the repository,request features,report bugs, fork and send your pull request i will be happy to merge them :).