
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
