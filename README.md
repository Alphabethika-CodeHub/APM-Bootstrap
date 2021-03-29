# APM-Bootstrap
### Hey there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">
<span>
    <img src="https://img.shields.io/badge/-Visual%20Studio%20Code-23A9F2?style=flat-square&logo=Visual%20Studio%20Code&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Github-181717?style=flat-square&logo=GitHub&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Git-F44D27?style=flat-square&logo=Git&logoColor=white"/>
    <img src="https://img.shields.io/badge/-NPM-CB3837?style=flat-square&logo=NPM&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Apache-D22128?style=flat-square&logo=Apache&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Trello-0079BF?style=flat-square&logo=Trello&logoColor=white"/>
    <img src="https://img.shields.io/badge/-MySQL-F29111?style=flat-square&logo=MySQL&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Notion-000000?style=flat-square&logo=Notion&logoColor=white"/><br/>
    <img src="https://img.shields.io/badge/-Laravel-F55247?style=flat-square&logo=Laravel&logoColor=white"/>
    <img src="https://img.shields.io/badge/-WebPack-1C78C0?style=flat-square&logo=WebPack&logoColor=white"/>
    <img src="https://img.shields.io/badge/-ESLint-4B32C3?style=flat-square&logo=ESLint&logoColor=white"/>
    <img src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white"/>
    <img src="https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white"/>
    <img src="https://img.shields.io/badge/-Google%20Cloud-4285F4?style=flat-square&logo=Google%20Cloud&logoColor=white"/>
</span>

[![Linkedin Badge](https://img.shields.io/badge/-daffanabilh-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/daffa-nabil-hartono-800271178/)](https://www.linkedin.com/in/daffa-nabil-hartono-800271178/)

<a href="https://trakteer.id/daffanh_eui77">
  <img alt="donate coffee" src="https://i.ibb.co/R02Pnc3/trakteer-button.png" />    
</a>

## Getting Started
<p>Aplikasi Pengaduan Masyarakat Untuk Ujikom 2021</p>

### Prerequisites | Setting up the project

Things you need to prepare before launch the project.
1. Install Composer [here](https://getcomposer.org/download/)
2. Install NPM [here](https://www.npmjs.com/get-npm)
3. Install Xampp [here](https://www.apachefriends.org/download.html)

### Installing

A step by step how to get a development env runnig

1. Go to the project and run the command below in CMD/Gitbash/Terminal.
    ```
    composer update
    ```
   Wait untill it's finished.
   
2. Create Database MySQL.
   In CMD/Gitbash/Terminal run
    ```
    mysql -u root -p
    ```
   then
    ```
     create database apm_bootstrap;
    ```
   if database has been created
    ```
     exit
    ```

3. In the project run the command below in CMD/Gitbash/Terminal.
   To wipe, migrating and seeding the database.
    ```
    php artisan apm:db
    ```
    Run cleaner command.
    ```
    php artisan apm:cc
    ```
    

### User And Admin
username: user
password: 12345678

username: daffa
password: 12345678

### Built With
* [Laravel 8](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Bootstrap 5]() - The CSS framework used
* [MySQL / MariaDB]() - The Database used
