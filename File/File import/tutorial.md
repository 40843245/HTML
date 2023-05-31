# File import in html

## import js file
To import a js file, the tag you should use in .html file. Such as 

    <script src="timesheet.min.js"></script>
## import css file
To import a css file, the tag you should use in .html file. Such as 

    <link href="timesheet.min.css" rel="stylesheet">
    
instead of

    <script src="timesheet.min.js"></script>

https://github.com/40843245/JS/blob/main/useful%20tools/timesheet/tutorial/screenshot/import_screenshot_1.png

## Notice 
Notice that in the script tag, the file consider to be a JS file. Or exactly to say, it is parsed with JS syntax. Such as

  <script src="timesheet.min.js"></script>
  
That's the reason why it is NOT valid to import a css file with such above tag.

![image](https://github.com/40843245/HTML/assets/75050655/0b974bd5-0908-41db-acb5-19cdb73697e5)


For more details, see the reply in the following section.
## Ref
Reply on StackOverflow.

https://stackoverflow.com/questions/65158024/uncaught-syntaxerror-unexpected-token-css
