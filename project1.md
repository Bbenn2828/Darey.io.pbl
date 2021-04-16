
##WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS
A technology stack is a set of frameworks and tools used to develop a software product. This set of frameworks and tools are very specifically chosen to work together in creating a well-functioning software. They are acronymns for individual technologies used together for a specific technology product.

Installing apache2
$ sudo apt update
$ sudo apt install apache2
$ sudo systemctl staus apache2
![Capture](https://user-images.githubusercontent.com/82408358/114868432-c2046080-9daa-11eb-9747-e0d89c8e1ca8.PNG)


To test if the Apache HTTP server can respond to request from the internet, open a web browser and input
http://<Public-IP-Address>:80  for the following image
  
  ![apache2](https://user-images.githubusercontent.com/82408358/114871519-35f43800-9dae-11eb-8a19-a6b804fd311d.PNG)

Installing MySQL
$ sudo apt install mysql-server
When prompted, confirm installation by typing Y, and then ENTER.
$ sudo mysql_secure_installation
Answer Y for yes, or anything else to continue without enabling.

VALIDATE PASSWORD PLUGIN can be used to test passwords
and improve security. It checks the strength of password
and allows the users to set only those passwords which are
secure enough. Would you like to setup VALIDATE PASSWORD plugin?
Press y|Y for Yes, any other key for No:

To confirm MySQL has been successfully installed: Input $ sudo mysql

![mysql](https://user-images.githubusercontent.com/82408358/114874148-e4997800-9db0-11eb-86ae-475e3714d243.PNG)

Enable PHP on the website. Create a new file named index.php inside your custom web root folder:

$ vim /var/www/projectlamp/index.php
This will open a blank file. Add the following text, which is valid PHP code, inside the file:

<?php
phpinfo();
When you are finished, save and close the file, refresh the page and you will see a page similar to this:

![php debug](https://user-images.githubusercontent.com/82408358/114984785-ef065100-9e46-11eb-95cc-06d33a272ec4.PNG)


