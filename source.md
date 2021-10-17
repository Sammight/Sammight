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
TODO    | Task to complete
IMPROVE | Wrong method impelemented
REDO    | Working but not to standard
BUG     | Errors
MEMORY  | Freezes
LEGACY  | Can be uncompatiable
REVIEW  | Document, always type every 50 lines

![IMG_20210911_122152](https://user-images.githubusercontent.com/58202540/132956049-d29700e3-2ee4-40a4-8e33-1b788d4b6428.jpg)

### Close Each Issue With Solution On Conversation

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
