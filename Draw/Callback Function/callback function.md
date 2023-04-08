# callback function (Will Update at future)
In this article, I will discuss some event callback functiond about drawing in html and JS.

I will update it in the future once I learn and fully understand it.

Thus, as an audience, if you enjoy this article, welcome to leave comments, follow me (including my YT channel and Twitter etc)

and share it to your friends.

Let's dig in.

### Window.requestAnimationFrame()

#### Syntax
Window.requestAnimationFrame(function func);

#### Description
An event callback function func every time before repainting.

Before repainting, the func will be automatically invoked.

#### NOTE

    1) The method Window.requestAnimationFrame() is 1 shot.
    
    You can consider it as disposables. It can be only used once.
    
    Thus, to use it many times, don't forget to write the statement Window.requestAnimationFrame() inside the callback function. 
    
    More details on the following figure and example given in the following website.
    
![image](https://user-images.githubusercontent.com/75050655/230726016-a78ee95b-b0f0-451f-b369-11649c4945fd.png)


#### Warning
![image](https://user-images.githubusercontent.com/75050655/230726066-4d297930-999a-49a3-ab65-b29c15c72683.png)


#### Ref

MDN Docs:
https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame




