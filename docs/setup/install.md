---
sidebar_position: 1
---

# Installations

There are several steps to install this application, namely:

1. Download the source code file [Dropbox](https://www.dropbox.com/sh/su7xfzsxlz8n5bk/AABADj1qZhCfRuKlQ0H1oYIpa?dl=0) (Make sure your email has confirmed the invitation)
2. Extract the ZIP file to the `htdocs/folder`
3. Open the file in the `application/config/database.php` in the section below adjust to the your envirovment
   ```php
   'username' => 'root', // in default is root
   'password' => '', // in default is empty
   'database' => 'sistemkeputusan', // the name of the database that you will create in point number 4
   ```
4. Create a new database in xampp. If you don't know how to create a new database, you can visit the following link: [Create new database](https://www.dewaweb.com/blog/cara-membuat-database-di-xampp/).
5. After the database creation is complete in xampp, you can open the folder `database/local` then you will find the database name `sistemkeputusan.sql` Next, you need to import the database in localhost/xampp/database that you created in point number 4. If you don't know how to import it, you can read the tutorial [In here](https://www.niagahoster.co.id/blog/cara-import-database-mysql/)
6. The installation process is complete. You can access your application by: `localhost/namefolder`. For example if I name my application folder in htdocs with name `spk`, then I access it in browser is: `localhost/spk`.
