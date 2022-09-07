# JasonPowerDB
### Description
JsonPowerDB is a Database Server with Developer friendly REST API services. It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database. Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.

## Benefits of using JsonPowerDB
- Simplest way to retrieve data in a JSON format.
- Schema-free, Simple to use, Nimble and In-Memory database.
- It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
- It is low level (raw) form of data and is also human readable.
- It helps developers in faster coding, in-turn reduces development cost.

### Release History
#### v0.0.0  
##### Initialization:
- [1] Added basic designs of all planned HTML pages
---
#### v0.1.0  
##### Enhancements:
- [2] Designed all HTML pages
- [3] Added JS and connected pages to JsonPowerDB
- [4] Tested all pages
---
#### v0.1.1  
##### Enhancements:
- [5] Added a README.md file
- [6] Few CSS changes
---


### Table of Content
1. [Introduction](#introduction)
2. [Illustrations](#Illustrations)
3.  Scope Of Functionality
4. Example Of Use 
   1. [Requirements](#requirements)
   2. [Execution](#execution)
   3. [Website](#website)
   
5.Project Steps  
6.Sources 

   7.Other Information

## 1.Introduction
In this project, you can do the following:
1. Fill the Employee Details.
2. Submit the Employee Details.
3. View all Employee Data.
4. Upadte mobile number.
5. Delete a specific Employee record.


   ## 2.Illustrations
![Index](https://github.com/Devan5622/Web/blob/main/Screenshot/Screenshot%20(94).png)

![Submit](https://github.com/Devan5622/Web/blob/main/Screenshot/Screenshot%20(95).png)
## In this we can se token number, command name and database name.

![Update](https://github.com/Devan5622/Web/blob/main/Screenshot/Screenshot%20(96).png)
## In this Above Dialogue Box Showing that Data updated in Record Number 6.

![Database](https://github.com/Devan5622/Web/blob/main/Screenshot/Screenshot%20(97).png) 
## After Updation all data is showing on Json Database. So many operation we can do on Json Like Delete,Update and GET etc.
   
   ## 3.Example Of Use
#### Requirements
  * Web Browser
  * Database Connection Token
#### Execution
* open `index.html` to open the Indec page
#### Website
* To go on any page
  * click on the link
* To come back on index page
  * click <- arrow on Browser

   ### 4.Scope of functionalities
* It is a very basic project for demonstration of JsonPowerDb with help of a web application. 
* Can be further improved by addidng additional fields and can be made into a working DB manager.


   ## 5.Project Steps
* Firstly added some scripts in this like: Jquery,Bootstrap and Javascript Library using script Elements. `<script>`
* After this create web form using html tags and input types are: EmployeeID, Employee Name and Email. `<form>,<label> and <input> etc.`
* Through the JavaScript validating the form data on client PC after this send the data to the web server. So for this we use the `ValidateGetFormData()` function.
* Using `JSON.Stringify()` method converts a JavaScript Value to a JSON string.
* For Put Request we use `createPUTRequest()` with the help of this creating the data and update an existing data.
* And For Executeing the data we use `executeCommand()`.
* But Replace both `createPUTRequest()` and `executeCommand()` function using single function`executeCommandAtGivenBaseUrl()`. Because `executeCommandAtGivenBaseUrl()`
this fuction directly available of JavaScript Library, So for this we directly add the URL link and then all work is done.
### Code Link: https://github.com/Devan5622/Web/blob/main/index.html
   # 6.Sources
[https://login2explore.com/jpdb/docs.html]

[https://login2explore.com/jpdb/resources/js/0.0.3/jpdb-commons.js]

[chrome-extension://aejoelaoggembcahagimdiliamlcdmfm/index.html#requests]

   # 7.Other Information

#### Name: Devanshu Siwach
#### Email: devanshusiwach15@gmail.com




 


