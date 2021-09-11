# Documentation

`github > mediafire > codeproject > wikidot > microsoft developer network > google sites | godaddy`

Use           | Service
--------------|-------------
source code   | Github
documentation | Github Pages
filehost      | MediaFire
tutorials     | CodeProject
forum         | Microsoft Developer Network
wiki          | Wikidot
website       | Google Sites
webhost       | GoDaddy

# Software

`github pages > stackshare > codecanyon > filehippo`

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

## Storage

`OneDrive > Convertio > NetApp > Couchdrop > Github > NoSQL / SQL > Stripe`

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
bootstrap  | framework | webpages
angular    | framework | webserver
xna        | framework | video
ionic      | framework | web applications
jquery     | library   | webbrowser
vx         | sdk       | virus writings

# Task

`framapad > stackshare > asana > codetree > github issues > stockpile`

Use        | Service
-----------|--------------
change log | Framapad 
software   | Stackshare
function   | Asana
project    | Codetree
task       | Github Issues
items      | Stockpile

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

Wrong
```
// STEP 1: Load server

//... code ...

// STEP 2: Build file

... code ...
```

Right
```
console.log('STEP 1: Load server')

//... code ...

console.log('STEP 2: Build file')

... code ...
```

## Optional Markdowns

Name      | Use
----------|----------------------------------------------
README    | How to use
INSTALL   | How to install
COPYING   | How to copy
LICENSE   | What rights
STANDARDS | Specific coding rules
NEWS      | Release history and top five features

## Development Comment

Type    | Purpose
--------|---------------------------------------------------
IMPROVE | Approach to observe to remove confusion
TODO    | Task waiting to be completed
REDO    | Code temporarily in place to keep running
REVIEW  | Advanced code to reduce for current standard
BUG     | Conditions execution breaks unintendenly breaks on
MEMORY  | Mark of an occurrance of memory leaks
LEGACY  | Code that would break on upgrade
README  |
NEWS    |
INSTALL |
STEP    | Output to terminal or log file to track execution

![IMG_20210911_122152](https://user-images.githubusercontent.com/58202540/132956049-d29700e3-2ee4-40a4-8e33-1b788d4b6428.jpg)

## Cut Code To Backup File, Avoid Block Comment

Wrong

program.sh
```
# TODO: Build array to load file

# Create server and start connection
#array=""
#while getopt option // Fixes bug from 0.4.2
#do
# echo "hello"
#done

echo "done"
```

Right

program.sh
```
# TODO: Build array to load file

echo "done"
```

program.sh.backup
```
array=""
while getopt option
do
 echo "hello"
done
```

* folder/README.md
* folder/folder/program.sh
* folder/folder/program.sh.backup
* folder/folder/README.md
```
get option fixes 0.4.2 on line 7
```

## Always Use A Change Log
* TOOLS, new tools to be added to stockpile and stackshare
* STATUS, task to be added to GitHub Issues
* Task is also the git commit message

```
05182021
=Copy Tools To New Change Log
=Dealing With Repeating Task or Events
=Site With Projects
=Recording Applications to Ensure Use
=Not Woking Enough
```

```
mmddyyyy
status(commit message)
status(commit message)
status(commit message)
status(commit message)
status(commit message)
```
