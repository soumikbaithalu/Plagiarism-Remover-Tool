<h1 align="center">🤖 Plagiarism Remover Tool 🤖</h1>

<div align= "center">
  <h4>Plagiarism Remover Tool is written in PHP (CakePHP framework) and MySQL using synonyms database to rephrase the sentences.</h4>
</div>


## :star: Star us on GitHub — it helps!

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img alt="PHP" src="https://img.shields.io/badge/php-%23777BB4.svg?&style=for-the-badge&logo=php&logoColor=white"/>
<img alt="MySQL" src="https://img.shields.io/badge/mysql-%2300f.svg?&style=for-the-badge&logo=mysql&logoColor=white"/>
<img alt="HTML5" src="https://img.shields.io/badge/html5-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/>
<img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/>
<img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/chandrikadeb7/Plagiarism-Remover-Tool/issues)
[![Forks](https://img.shields.io/github/forks/chandrikadeb7/Plagiarism-Remover-Tool.svg?logo=github)](https://github.com/chandrikadeb7/Plagiarism-Remover-Tool//network/members)
[![Stargazers](https://img.shields.io/github/stars/chandrikadeb7/Plagiarism-Remover-Tool.svg?logo=github)](https://github.com/chandrikadeb7/Plagiarism-Remover-Tool//stargazers)
[![Issues](https://img.shields.io/github/issues/chandrikadeb7/Plagiarism-Remover-Tool.svg?logo=github)](https://github.com/chandrikadeb7/Plagiarism-Remover-Tool//issues)
[![MIT License](https://img.shields.io/github/license/chandrikadeb7/Plagiarism-Remover-Tool.svg?style=flat-square)](https://github.com/chandrikadeb7/Plagiarism-Remover-Tool//blob/master/LICENSE)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555)](https://www.linkedin.com/in/chandrika-deb/)

<p align="center"><img src="https://github.com/chandrikadeb7/Plagiarism-Remover-Tool/blob/main/Screenshot%202021-05-15%20at%2011.00.17%20PM.png"></p>

## :point_down: Support me here!
<a href="https://www.buymeacoffee.com/chandrikadeb7" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
 
## :hourglass: Project Demo

https://user-images.githubusercontent.com/29686102/118373361-0a928200-b5d4-11eb-86f5-37bce1c46ab6.mov


## :warning: TechStack/framework used

- PHP
- CakePHP
- MySQL
- HTML
- CSS
- Javascript

## :star: Features
Our plagiarism remover tool rephrases and rewrites the sentences given in input box via three levels which are Soft, Normal and High and gives an output with a time limit of a few seconds.

## :file_folder: Database Configuration
The dataset used can be found here - [Click Here](https://github.com/chandrikadeb7/Plagiarism-Remover-Tool/blob/main/rephrase.sql)

## :key: Prerequisites

- Download XAMPP from [here](https://www.apachefriends.org/download.html)
- Launch XAMPP server and start the respective services, network, and mount the htdocs folder. See screenshots [here](https://github.com/chandrikadeb7/Plagiarism-Remover-Tool/tree/main/Readme_Images)
- Go to [phpMyAdmin](http://localhost:8080/phpmyadmin/) and create a new database as **'rephrase'**

## 🚀&nbsp; Installation

#### Clone the repo inside /htdocs folder
```
$ git clone https://github.com/chandrikadeb7/Plagiarism-Remover-Tool.git
```

#### Import the database file

Import the database [file](https://github.com/chandrikadeb7/Plagiarism-Remover-Tool/blob/main/rephrase.sql) into the created database **'rephrase'**.

## :bulb: Working

#### Enter your database details in file [database.php](https://github.com/chandrikadeb7/Plagiarism-Remover-Tool/blob/main/app/Config/database.php)

```
class DATABASE_CONFIG {

	public $default = array(
		'datasource' => 'Database/Mysql',
		'persistent' => false,
		'host' => 'localhost',
		'login' => 'root',
		'password' => '',
		'database' => 'rephrase',
		'prefix' => '',
		//'encoding' => 'utf8',
	);
```

## :key: Run

#### Run the web app locally

Go to [https://localhost:8080/Plagiarism-Remover-Tool](https://localhost:8080/Plagiarism-Remover-Tool) on your browser (Chrome/Safari/Firefox)

## :clap: And it's done!
Feel free to **file a new issue** with a respective title and description on the the [Plagiarism-Remover-Tool](https://github.com/chandrikadeb7/Plagiarism-Remover-Tool/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**! 

## 📘&nbsp; License
The Plagiarism-Remover-Tool is released under the under terms of the [MIT License](LICENSE).

## :heart: Contributor
Made by [Chandrika Deb](https://github.com/chandrikadeb7)

