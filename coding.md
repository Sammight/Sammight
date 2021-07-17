# Documentation

`github > mediafire > codeproject > wikidot > google sites | godaddy`

Use           | Service
--------------|-------------
source code   | Github
documentation | Github Pages
file hosting  | MediaFire
tutorials     | CodeProject
forum         | CodeProject
wiki          | Wikidot
website       | Google Sites
webhost       | Godaddy

# Software

`stackshare > codecanyon > filehippo`

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
backup      | Heroku

## Storage

`OneDrive > Convertio > NetApp - Couchdrop > Github > MongoDB (NoSQL) / ClearDB (SQL) > Stripe`

Use         | Service
------------|-----------
file        | OneDrive
cloud share | NetApp
file share  | Couchdrop
source code | GitHub
programming | MongoDB
information | ClearDB
conversion  | Convertio
payment     | Stripe

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
bootstrap  | framework | webpages
angular    | framework | webserver
xna        | framework | video
ionic      | framework | web applications
jquery     | library   | webbrowser
vx         | sdk       | virus writings

# Task

`stackshare > asana > codetree > github issues > stockpile`

Use        | Service
-----------|--------------
change log | Framapad 
software   | Stackshare
function   | Asana
project    | Codetree
task       | Github Issues
items      | Stockpile

## No Abbreviations and Object (if possible)

```
projectDN
projectDomainName
ProjectDomainName
ProjectDomain
Project
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
project.domain.name.code
```

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

# Source
## Only Use Comments for Development

Right

```
// ... code ...
... code ...
```

Wrong

```
// STEP 1: Load server

//... code ...

// STEP 2: Build file

... code ...
```

## Steps Are Checks and Written to Log File

```
console.log('STEP 1: Load server')

//... code ...

console.log('STEP 2: Build file')

... code ...
```

## Development Comment

IMPROVE Approach to observe to remove confusion
TODO    Task waiting to be completed
REDO    Code temporarily in place to keep running
REVIEW  Advanced code to reduce for current standard
BUG     Conditions execution breaks unintendenly breaks on
MEMORY  Mark of an occurrance of memory leaks
LEGACY  Code that would break on upgrade

### Cut code to another file, not block comment

program.c
//TODO: Build array to load file

program.c.log
array=""
while getopt option
do
 echo "hello"
done


### Common File Extensions

.config
.log
.backup
.<language>



## Always Use A Change Log

* One text file for the month
* mmddyyyy (status)description=commit message 
