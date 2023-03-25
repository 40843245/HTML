# Form Handling
## Objective
Quick guide to understand (NOT discussed in order)
  
    1) How html and php handles the form.
    
    2) The concept of the form of web development.
    
    3) Way to get data from html in php.
    
    4) The concept of url.
    
    5) GET v.s. POST
    
    6) Details and Notice of code.
   
It may save your time. 
    
I don't know the details of code, leaving a bug and debug it for a while.

I hope it can help you and save your time.
  
## Prequisite
Basic syntax of html and php.

For them, you can visit my other notes and tutorial provided in my notes (also in GitHub).


## Add a new form in html
To add a new form in html, add a form tag such as  

    <form action = "form_handler.php" method = "GET" />
    
    where 
    
    1) action refers the command and the php file will be executed after triggering the event of submitting the form.
    
    In the above example, when the form submits, the form_handler.php will be executed.
    
    2) method refers the method the form submits. 
    
    In the above example, it will adapt the GET method to submit the form.
    
NOTE that
    
    1) If the method will NOT specified, it will use the default value -- "GET".
    
    2) The value of action and GET attribute are case-sensitive (i.e. "GET" is NOT equivalent to "get").
    
## Access data from html in php.

Step1: Specify the name attribute.

Step2: According to the method of the form, in php, to access the input data from type $_GET or $_POST etc.

NOTE that

<b>The index of php in array must respond to the value of the name attribute in html tag.</b>

For example, suppose I use the GET method in html form.

    The value of a tag <input name="desired_text"> in php file will be stored in $_GET["desired_text"]
    
    $_GET["desired_texts"] will NOT access the value of a tag <input name="desired_text">.
    
  
### Code example

In website_decoder_1.html

    <!DOCTYPE html5>

    <html>
        <form action="website_decoder_1.php">
        <label>Desired Text:</label>
        <input name="desired_text">

     </html>

In website_decoder_1.php

    <?php
        echo "original text:";
        echo $_GET['desired_text'];
    ?>
        
        
When the user run the website_decoder_1.html (in my notebook, it can be done by typing "http://localhost/website_decoder/website_decoder_1.html" in url box.)

![image](https://user-images.githubusercontent.com/75050655/227746707-aec91e1f-0881-4ea1-a25f-fa5ea42f6fc1.png)

        
https://github.com/40843245/HTML/blob/main/Form/Form%20Handling/HTML_Form2.png

https://github.com/40843245/HTML/blob/main/Form/Form%20Handling/PHP_Form2.png

For more details, see the figure in GET v.s. POST section or visit the website in ref in the following section.

https://github.com/40843245/HTML/blob/main/Form/Form%20Handling/PHP_Form.png

## GET v.s. POST
To fully understand of the difference between GET and POST of form handling, let's dig in a figure.

![image](https://user-images.githubusercontent.com/75050655/227727831-7e4ecfb3-16ef-458b-bb2d-956537376e71.png)

### Ref

https://www.w3schools.com/tags/ref_httpmethods.asp
