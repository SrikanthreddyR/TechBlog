## Welcome to Srikanth's Tech Blog 


## Covid 19 Data Analysis

#### Project Overview
1. Loading Covid 19 data into SQL Server Database
2. Data Exloration
3. Data Cleaning
4. Visualization
5. Creating Dashboard
<br/>

#### Prerequisites:
- Should have SQL Server and SSMS installed on your machine. 
     
     - If not, please follow the isntallation process with the video [SQL Server 2019 Developer Edition - Download and Installation Steps
](https://www.youtube.com/watch?v=1UdmrVIBzN4) on youtube.
     - Otherwise you can navigate through the installation on [www.c-sharpcorner.com](https://www.c-sharpcorner.com/article/how-to-install-sql-server-2019/) web page to install the same. This link  guides through the basic installation of SQL server which avoids going through multiple cofiguration steps maually.
     - If your system is not running with Windows 10 / Windows Server 2016 or greater, SQL Server 2019 Developer Edition isn't compatible for your machine.
     - In that case you can [Download SQL Server 2017 Developer edition](https://download.microsoft.com/download/5/A/7/5A7065A2-C81C-4A31-9972-8A31AC9388C1/SQLServer2017-SSEI-Dev.exe) using the link and follow the same steps as mentioned in [www.c-sharpcorner.com](https://www.c-sharpcorner.com/article/how-to-install-sql-server-2019/) or [SQL Server 2019 Developer Edition - Download and Installation Steps](https://www.youtube.com/watch?v=1UdmrVIBzN4).
     - After installing both SQL Server and SSMS(Tool to connect to the SQL Server), we are good to proceed further.

- Basic SQL commands. [W3Schools](https://www.w3schools.com/sql/sql_syntax.asp) should be a good starting point if you don't have prior SQL hands on.

<br/>


### 1. Loading Covid 19 data into SQL Server Database 

<p> First we will download the data from [https://ourworldindata.org/](https://ourworldindata.org/covid-deaths). Navigate to link 
     
<p/>  
 
 []
 
 
 Loading latest Covid 19 Data from [https://ourworldindata.org/](https://ourworldindata.org/covid-deaths) onto SQL Server DB
    - 



1. Creating blank database with the name 'Covid19Data' (You can use a different name as per your convinience). 
2. Downloading Latest Covid 19 Data from [https://ourworldindata.org/](https://ourworldindata.org/covid-deaths)
3. Dividing the data into Covid19Deaths and Covid19Vaccinations.
4. Uploading the data as tables onto the previoiusly created DB 'Covid19Data'.




Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/SrikanthreddyR/TechBlog/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
