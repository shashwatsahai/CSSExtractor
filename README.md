# CSSExtractor
This tool extracts CSS with source files for active styles and save the output to a JSON file

<h2>Please create a Pull Request in case you add/fix a feature so that others can benefit from it</h2>

Required - 
 The getC() function starts parsing from $0. Make sure your $0 points to body element. Open devtools and click on the element or pass an element in code<br/>
 Run getC function with the $0 or element as parameter<br/>
 It will output the data to the JSON file mentioned in line 2404<br/>
 Call getC after html has loaded otherwise $0 will not point to anything and there will be no data to parse<br/>
 <br/><br/>

Steps to use - </br>
->The $0 must point to your body element of your current page</br>
->Run <b>getC()</b> function with $0 as the parameter ie getC($0)</br>
->Change your JSON filename at line 2404 or where it is written  -//Give your filename here</br>
->You can add this file anywhere but function must be called after the html has loaded</br>


