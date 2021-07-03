
# Documentation

github > framapad > mediafire > codeproject > wikidot > google sites | godaddy

source code   Github
documentation Github Pages
change log    Framapad
file hosting  MediaFire
tutorials     CodeProject
forum         CodeProject
wiki          Wikidot
website       Google Sites
webhost       Godaddy

# Software

stackshare > codecanyon > filehippo

stack Stackshare
store Codecanyon
site  Github Pages
host  Filehippo

## Environments 

development Kamatera
test        CodeAnywhere
office      Chromebook
production  Heroku
backup      Heroku

## Tools

cleardb
convertio
couchdrop
img2go
mongodb
netapp
stripe

# Task

asana > codetree > github issues

# Coding

## No Abbreviations and Object (if possible)

projectDN
projectDomainName
ProjectDomainName
ProjectDomain
Project

or

project = {
    'domain': 'name'
}
project = { 'domain': }
project.domain = {
    'name': '',
    'server': '',
    'ip': ''
}
project.domain.name = {
    'code': '',
    'location': '',
    'form': ''
}
project.domain.name.code

## Files and Folders as Task

Data       | Title       | Depth
-----------|-------------|--------
executable | Function    | 0
folders    | Project     | 1
folder     | Assignment  | 2
file       | Task        | 3
head       | Note        | 3
block      | Step        | 3
line       | Instruction | 3

### Example

* card-match/ (FUNCTION)
  * html/ (PROJECT)
    * index.html (TASK)     
  * css/               
    * style.css         
  * js/                
    * app.js            
    * flashcards/ (ASSIGNMENT)       
      * deal.js (TASK)
      * cards.js         
    * configuration.js 
  * ts/                
    * main.ts              
      * convert/          
        * split.ts         
        * process.ts

## Only Use Comments for Development

Right

// ... code ...
... code ...

Wrong

// STEP 1: Load server

//... code ...

// STEP 2: Build file

... code ...

## Steps Are Checks and Written to Log File

console.log('STEP 1: Load server')

//... code ...

console.log('STEP 2: Build file')

... code ...

## Always Use A Change Log

One text file for the month
mmddyyyy (status)description=commit message  
