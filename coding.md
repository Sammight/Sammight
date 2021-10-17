# Documentation

`(markdowns) > mediafire > codeproject > wikidot > msdn`

Use           | Service
--------------|-------------
filehost      | MediaFire
tutorials     | CodeProject
forum         | Microsoft Developer Network
wiki          | Wikidot
webhost       | GoDaddy

# Software

`stackshare > github pages (docusaurus) > filehippo`

Use   | Service
------|-------------
stack | Stackshare
store | Codecanyon
site  | Github Pages
host  | Filehippo

## Environments 

Stage       | Server
------------|-------------
office      | Chromebook
development | Kamatera
test        | CodeAnywhere
production  | Heroku

# Storage

`onedrive > github > nosql / sql > stripe`

Use           | Service
--------------|-----------
cloud storage | OneDrive
cloud share   | NetApp
file share    | Couchdrop
source code   | GitHub
programming   | MongoDB Atlus (NoSQL)
information   | ClearDB (SQL)
conversion    | Convertio
payment       | Stripe

## Languages

Language   | Ends      | Purpose
-----------|-----------|----------
browser    | client    | explore - google
html       | front     | structure
xml        | front     | rule
latex      | front     | document
css        | front     | style
sql        | user      | query
perl       | user      | search
js         | user      | script
clisp      | back      | think (lisp) - nasa
ts         | back      | program (c#) - microsoft
c#         | back      | hack - microsoft
php        | server    | serve
node       | server    | run - google
powershell | shell     | configure - microsoft
platform   | system    | operate - microsoft
z80        | processor | assemble
binary     | computer  | act
physics    | universe  | interact

Name       | Type      | Use
-----------|-----------|-----------------
bootstrap  | framework | web pages
angular    | framework | web server
xna        | framework | video
ionic      | framework | web applications
jquery     | library   | web browser
vx         | sdk       | virus writings

# Task

`codetree > github issues > (spreadsheet)`

Use        | Service
-----------|--------------
change log | Framapad 
software   | Stackshare
function   | Asana
project    | Codetree
log        | Github Issues
items      | Stockpile

[Siban Inventory.xlsx](https://github.com/Sammight/Sammight/files/7348613/Siban.Inventory.xlsx)

![0210918_113814](https://user-images.githubusercontent.com/58202540/133896183-ef512fca-c334-4f8b-9903-2830f34c30af.jpg)

## Environment and Placeholder Variables

Syntax                   | Example         | Name
-------------------------|-----------------|---------------------- 
variable                 | first           | variable
object.word.word         | first.car.color | object
variable_word_word       | FIRST_CAR_COLOR | environment variable
variable(Letter, Number) | firstA          | placeholder variable

* Object names removed need for camel case
* Did not chagne environment variable naming
* Placeholder variable for a parameter to argument

## No Abbreviations and Object (if possible)

```
1 Variable
projectDN
projectDomainN
projectDomainName

3 Variables
Project
ProjectDomain
ProjectDomainName
```

or

```
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
project.domain.name.code = ''
```

## Files and Folders as Task

Data       | Title                  | Depth
-----------|------------------------|--------
executable | Function               | 0
folders    | Project                | 1
folder     | Assignment             | 2
file       | Task / Object          | 3
head       | Note                   | 3
block      | Step / Variable        | 3
line       | Instruction / Function | 3

### Example

Object            |  Type
------------------|----------------
card-match/       |  FUNCTION
html/             |  PROJECT
index.html        |  TASK   
css/              |  PROJECT
style.css         |  TASK
js/               |  PROJECT
app.js            |  TASK
flashcards/       |  ASSIGNMENT       
deal.js           |  TASK
cards.js          |  TASK
configuration.js  |  TASK
ts/               |  PROJECT
main.ts           |  TASK
convert/          |  ASSIGNMENT
split.ts          |  TASK
process.ts        |  TASK
card-slide/       |  PROJECT

* card-match/
  * html/              
    * index.html          
  * css/               
    * style.css        
  * js/                
    * app.js           
    * flashcards/        
      * deal.js        
      * cards.js       
    * configuration.js 
  * ts/                
    * main.ts          
      * convert/       
        * split.ts     
        * process.ts   
  * card-slide/        

### Common File Extensions

Type        | Purpose
------------|--------------------------------------
.config     | Configuration
.log        | Log
.backup     | Backup
.tmp        | Temporary
.(language) | Code
