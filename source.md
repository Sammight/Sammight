# Source

## Know what development comment your using while coding

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

### Start Issue with Label and Milestone

Type     | Purpose
---------|--------------------------------------------------
Request  | Thought about
Pending  | No milestone
Progress | Someone assigned
Testing  | Third party working on
Done     | Completed

## Development Comment

Type    | Purpose
--------|---------------------------------------------------
TODO    | Task to complete
IMPROVE | Wrong method impelemented
REDO    | Working but not to standard
BUG     | Errors
MEMORY  | Freezes
LEGACY  | Can be uncompatiable
REVIEW  | Document, always type every 50 lines

![IMG_20210911_122152](https://user-images.githubusercontent.com/58202540/132956049-d29700e3-2ee4-40a4-8e33-1b788d4b6428.jpg)

### Close Each Issue With Solution

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

[abakasam-052021-change.log](https://github.com/Sammight/Sammight/files/7148269/abakasam-052021-change.log)

[(simple)abakasam-102021-change.log](https://github.com/Sammight/Sammight/files/7360621/simple.abakasam-102021-change.log)


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

## No Abbreviations (if possible)

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
