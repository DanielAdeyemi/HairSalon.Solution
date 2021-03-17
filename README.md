## <div align="center">Eau Claire's Salon</div>
#### <div align="center">📚 *Epicodus Independent Project # 9  (Week 3 of C#)  3/12/2021* </div> 
***<p align="right">By Daniel Adeyemi***</p>   
<p align="center">

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="csharp" width="30" />
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="30"/>
<img alt="MySQL" width="30px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png" /> 
</p>

<div style="text-align:center"><img src="https://www.yourelitewriter.com/wp-content/uploads/2019/10/ceiling-chairs-indoors-705255.jpg" alt="Bakery image" width="300"/></div>

___
## <div align="center"> Table of Contents: 
| [Description](#description) | [Setup and Installation instructions](#setup) |  [SQL setup instructions](#sql) |
| :-------------: |  :------------: | :-------------: |
| [User story](#story) | [Technology used](#technology) | [Known bugs](#bugs) |
| [Improvement opportunities](#improvement) | [Contact information](#contact)| [View Website](#view) |
| [License and copiright](#license) | |  |
</div>

<a name="description"></a>
## <div align="center"> 🚩 *Description*:</div>    
### *Looking to ease your workflow in salon? Check our app!*
##### *An MVC app to manage employees and their clients. User will be able to add a list of stylists working at the salon, and for each stylist, add clients who see that stylist. Each client can only belong to single stylist.*

<a name="setup"></a>
## <div align="center"> 🔧 *Setup/Installation instructions:*
#### 🌐 From the web:
* Go to my GitHub repository, using following [URL](https://github.com/DanielAdeyemi/HairSalon.Solution.git).
* * At the top of the repository, click <img src="https://i.imgur.com/Ej9Dphm.png" alt="Code Button" height="20" align="center" /> then select "Download ZIP".

<img src="https://i.imgur.com/tZKvGne.gif" alt="download zip gif" height="200"/>

* Unzip the file, navigate to the `HairSalon` directory to check code
#### ⚙️ From the terminal: 
* Clone my repository from GitHub using `git clone https://github.com/DanielAdeyemi/HairSalon.Solution.git` in your terminal or GitBash
* Navigate to the downloaded folder using ***cd*** command
* Execute **code .** command in your terminal and it will open all source code in your code editor.    
⚠️ *Note: To run this project locally you will need to have .NET Core. You can check if you have .NET Core by running `dotnet --version` in the command line. If you do not have .NET Core please find more information and download [here](https://dotnet.microsoft.com/download/dotnet).*

<a name="sql"></a>
## <div align="center"> 🗃️ SQL setup and connection to the application
* In your terminal start using mysql by running command: `mysql -u[YOUR-USERNAME] -p[YOUR-PASSWORD]` 
* run command `SOURCE [PATH-TO-THE-PROJECT]/daniel_adeyemi.sql` to recreate database and tables.
* inside `HairSalon` folder create **appsettings.json** file and input following information:    
```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=daniel_adeyemi;uid=[YOUR-ACCOUNT-NAME];pwd=[YOUR-PASSWORD];"
  }
}
```
⚠️ *Note: Don't include **[ ]** around your username or password in any of the examples above.*    
If you need to set up SQL database from scratch - click on details below:
<details>
<summury>Details to set up DB </summary>

- You need to have MySqlWorkbench installed on your machine. You can download it [here](https://www.mysql.com/products/workbench/)   
- In the navigator > Administration window, select Data Import/Restore   
- In Import Options select Import from Self-Contained File.   
- Navigate to daniel_adeyemi.sql in the HairSalon.Solutions directory   
- Under Default Schema to be Imported To, select the New button.   
- Enter the name of your database   
- Click ok   
- Click Start Import   
- Reopen the Navigator > Schemas tab and refresh the schemas(using `Refresh All`). 
</details>


<a name="story"></a>
<h3 align="center"> 😴 📖Story:</h3> 
<details>
<summary>🔽</summary>

| # | Story |  Complete |
| :------------- |  :------------: | :-------------: |
| 01 | Salon owner needs to be able to see a list of all stylist | ✅ |
| 02 | Salon owner needs to be able to select stylist and see their details as well as list of clients that belong to this stylist | ✅ |
| 03 | Salon owner needs to be able to add new stylist to the system when they re hired | ✅ |
| 04 | Salon owner needs to be able to add new client to a specific stylist | ✅ |
| 05 | Salon owner should not be able to add client if no stylists have been added| ✅ |

</details>

<a name="view"></a>

### <div align="center">  🖥️ View website:
*GitHub page is not available for this project. To view functionality you need to run `dotnet run` from **HairSalon** folder. After that you will see `http://localhost:5000`, click on that link and it will open web appliction in your default browser. In order to exit from local host use **Ctrl+C** command.*

<a name="technology"></a>

## <div align="center"> 🛠️ *Technologies used:*
* C# 9
* .NET 5.0
* ASP.NET Core MVC
* Razor View Egine
* RESTful Routing, CRUD & HTTP
* CSHTML and CSS
* Bootstrap v.4.6.x
* MSTest
* REPL
* Git and GitHub
* MySQL and MySQL Workbench
* Entity Framework Core

<a name="bugs"></a>

## <div align="center"> 🐛 *Known bugs:*
This project was used to practice building web applications with SQL database, Entity Framework. Application has basic style.

<a name="improvement"></a>

## <div align="center"> 🌟 *Improvement opportunities:*
* add more style to the pages

<a name="contact"></a>

##  <div align="center"> 📬 Contact Information
#### For any questions *[email author](mailto:adeyemidany+github@gmail.com?subject=[GitHub])*

<a name="license"></a>

## <div align="center"> 📘 *License and copyright:*

> ***© Daniel Adeyemi, 2021***  
> ⚖️ *[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)*