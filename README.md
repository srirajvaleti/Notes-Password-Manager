


Overview
--------
my application helps to take notes at any time and helps to generate a very strong password for the security of your account and makes them
available whenever you need. It's going to have two major functionalities at the same time

Features:

* my application incorporates Strong encryption by the use of AES-256-CBC algorithm 
* can be loaded into a USB stick
* capable of generating strong passwords
* The user interface is very friendly and helps you to organize all your user name, password, URL and notes information in one file


Usage
-----
Java 8 or later is recommended to run  Notes-password-Manager. Most platforms have a mechanism to execute `.jar` files (e.g. double click the `jpass-0.1.24-RELEASE.jar`).
You can also run the application from the command line by typing (the password file is optional):

    java -jar jpass-0.1.24-RELEASE.jar [password_file]

How to compile
--------------
* Maven: `mvn clean package`
* Gradle: `gradle clean build`
* sbt: `sbt clean package`
