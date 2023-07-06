# TSS-Reminder

> Remind Users for Tenure Submission System

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Setup](#setup)
* [Usage](#usage)
* [Project Status](#project-status)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
* [License](#license)
<!-- * [License](#license) -->


## General Information
- This Script Remind Users that not filled and/or submitted personal form and files.
- Or not canceled registration in submission system.
- Time Lapse from last unsubmitted process is 5 days.
- Script uses XML ini files situated in 
- \\ekeksql00\SP_Resources$\WP_Config\SendToRakefet\CRS_asher\ directory
- Names of XML files are: TSS-ARS10.xml and TSS-ARS11.xml
- Script uses Template ini file situated in 
- \\ekeksql00\SP_Resources$\WP_Config\SendToRakefet\CRS_asher\ directory
- Name of Template file is: TSSMailTemplate.txt


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- PoweShell - Version 5.1


## Features
In Template Ini  file there are list of internal fields that replacing during running
- "CustName" - Customer name
- "OpenfilesUpload" - Link to Upload Page
- "openCancelPage"  - Link to Cancel Page




## Setup
Copy files to directory on server and ask Sergey Rubin to create cmd and Task for this script

## Usage
- Log files suitable in "\\ekekfls00\data$\scriptFolders\LOGS\TSSReminder" directory

`.\Do-TSSRemider.ps1`


## Project Status
Project is: _in progress_ / _complete_ / _no longer being worked on_. If you are no longer working on it, provide reasons why.




## Acknowledgements
Developer: Asher Sandler. 

- This project was inspired by Evgenia Tchachkin
- Many thanks to [Evgenia Tchachkin](mailto:evgeniat@savion.huji.ac.il)


## Contact
Created by [ashersan](mailto:ashersan@savion.huji.ac.il) - feel free to contact me!


<!-- Optional -->
## License 
© 2023 Copyright: The Hebrew University in Jerusalem
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
