# Web Development
1. Login Page: 
   - Login page that uses jQuery to validate.
   
2. Drop Down List: 
   - Drop-down selection which options are generated from a SQL query.
   - The configuration of config.php is: 
   
          $servername = "yourdatabaseaddress";
          $username = "yourusername";
          $password = "yourpassword";
          $dbname = "yourdatabasename";

          The syntax below is to establish a connection to the database
          $mysql = mysqli_connect($servername, $username, $password, $dbname);
