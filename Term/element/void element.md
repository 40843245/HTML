# void element
## Intro 
A void element is an element that can NOT have any child nodes (i.e. nested nodes or text nodes).

A void element only have a start tag, it can NOT have an end tag.

Such as 

    <div>
        <input type='text'> 
    </div>
    
is a valid syntax.

While 

    <div>
        <input type='text'>TEXT</input>
    </div>

is NOT a valid syntax since the input tag is a kind of a void element and the end tag is specificied.


## Ref
https://developer.mozilla.org/en-US/docs/Glossary/Void_element


