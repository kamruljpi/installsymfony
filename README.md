# How To Install Symfony

To downloads symfony, you need to download symfony.phar (a small file PHP) from this [link](http://symfony.com/installer).

Then, you have to move in your usual Web directory **C:\wamp\www** or **C:\xamp\htdocs** on windows and **/var/www** on Linux ;
Execute the below command : 

**php symfony.phar new your_project_name** 

for example : **php symfony.phar new firstproject** to download Symfony Latest Version

Then, you can :
Change your current directory to **/var/www/html/firstproject** on Linux or  **C:\wamp\www\firstproject** or **C:\xampp\htdocs\firstproject** on windows;
Then execute this command to run your application

**php bin/console server:run**

Then browse to the url **http://localhost::8000** url

Configure your application in the below file: 

**app/config/parameters.yml** file

And (always) read the documentation at http://symfony.com/doc.
