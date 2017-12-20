# iTech Empires

## Laravel 5 Angular JS File Upload Tutorial Source Code

### Tutorial Features:

- File upload validations such as Required, File Type and File size
- Find the file type
- Calculating and store the size of the file
- Renaming file while uploading on to the server
- Listing existing files from the server
- Delete files from server

### Steps to follow

**1. Create a mysql database and its user.**

**2. Install composer dependencies:**
```
composer update
```

**3. Create .env file:**
```
cp .env.example .env
```

**4. Add to the .env file your database connection data:**
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=testfile
DB_USERNAME=testfile
DB_PASSWORD=testfile
```

**5. Run the migrations:**
```
php artisan migrate
```

**6. Generate the app's key:**
```
php artisan key:generate
```

**6. Execute the project:**
```
php artisan serve --host 0.0.0.0 --port 8000
```
