# url
## intro 
Url determines to redirect what webpages.
## Consist
It consist of
  
    1. scheme
    2. authority
    3. path 
    4. fragment
    
### Scheme 
It determines what kind of protocol will be used.

Such as https 

#### Common type of scheme
    1. http
    2. https
    3. mailto
    4. news
    5. tel
    6. javascript

##### Intro to common type of schemes
1. http : 
    
        Redirect to a webpage.

2. https :


        Secure type of http.
        
3. mailto :

        Send a mail.

4. news :
        
         About the news.
5. tel :

          About the telephone.

6. javascript :
    
          About the javascript code. It can be used for execute the javascript code or etc.
    
### Authority
The authority contains the information about the scheme.

It can consist of these respectively.
          
          1. userinfo (optional) (if the scheme is either http, https, or javascript, it should NOT exist)
          2. host
          3. port 
         
#### Intro to common type of Authority
1. userinfo : 

        It's optional.
        
        If the scheme is either http, https, or javascript, it should NOT exist.

2. host :

        It's required.
        
        Determine the host name, including the domain name.

3. port :
        
        Determine what port to be used. 
        
        If it is NOT specified, then the port 80 will be used.  
        
### Path

It determines what the file will be executed (,or what the webpage will be redirected).

It is optional.

However, we usually specify it.

It is a special case to NOT specify it.

If it is NOT specified, it will redirect the mainpage of the current running server (if there are running server at present). 

For more details, see my notes about Docker in GitHub which available at.

https://github.com/40843245/Docker/blob/main/basic%20knowledge/phpmyadmin/phpmyadmin.md

### Fragment

It determines which part of the webpage will be redirected to.

The syntax should be

      #fragment

## More details and examples

For more details and examples, visit the Example Url section in wiki which is available at the following website.

## Ref
https://en.wikipedia.org/wiki/Uniform_Resource_Identifier#Syntax
