# replaced element
## Prequisite
Some basic knowledge of some tags in html.

## Intro
A replaced element is an element whose representation is outside of the scope of CSS.

## Recall
Recall about some tags
      
### <select>, <optgroup>, and <option>
      
            
            
            The <select> tag handles its internal HTML to a selection list. 
            User can select one option or more options among all options in the <select> tag.
            While a <option> tag create an option.
            The <optgroup> tag groups one <option> tag or more <option> tags.
      
Consider the following example.
      
For the html code, visit the website in GitHub.
      
https://github.com/40843245/HTML/blob/main/example/example%20code/example_code_1.html
     
The figure illustrates the output of the above HTML code.

![image](https://user-images.githubusercontent.com/75050655/236366333-99e3996a-7069-4637-94b1-43d51974162e.png)

 In the above example, I want to explain and highlight some knowledgements.
      
First, let's focus the piece of code.

      <label for="ext">File Ext:</label>
            <select name="ext" id="ext">
                <option value=".csv">Excel (.csv)</option>
                <option value=".xls">Excel (.xls)</option>
                <option value=".xlsx">Excel (.xlsx)</option>
                <option value=".txt">Text (.txt)</option>
                <option value=".html">HTML (.html)</option>
                <option value=".xml">XML (.xml)</option>
                <option value=".doc">Word (.doc)</option>
                <option value=".docx">Word (.docx)</option>
                <option value=".dot">Word (.dot)</option>
                <option value=".pdf">PDF (.pdf) (Only Output)</option>
                <option value=".accdb" class="DEPRECATED">Microsoft Access (.accdb) (Deprecated NOW)</option>
                <option value=".ppt" class="DEPRECATED">PowerPoint (.ppt) (Deprecated NOW , always Unavailable)</option>
                <option value=".pptx" class="DEPRECATED">PowerPoint (.pptx) (Deprecated NOW , always Unavailable)</option>
            </select>
            
In the above piece of code, there are 14 options. The first option which its value is ".csv" and will display the text "Excel (.csv)".

The <select> tag The 14 options are 


      
      
      
## Ref
