# Styling HTML with CSS

CSS stands for Cascading Style Sheets.  
CSS describes how HTML elements are to be displayed on screen, paper, or in other media.  
CSS saves a lot of work. It can control the layout of multiple web pages all at once.  
  
CSS can be added to HTML elements in 3 ways:

    Inline - by using the style attribute in HTML elements
    Internal - by using a <style> element in the <head> section
    External - by using an external CSS file  

The most common way to add CSS, is to keep the styles in separate CSS files. However, here we will use inline and internal styling, because this is easier to demonstrate, and easier for you to try it yourself.  
  
## Inline CSS
  
An inline CSS is used to apply a unique style to a single HTML element.  
An inline CSS uses the style attribute of an HTML element. 

Eg. ``` <h1 style="color:blue;">This is a Blue Heading</h1> ```
  
## Internal CSS

An internal CSS is used to define a style for a single HTML page.  
Eg. 
``` <!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
  
Reference [W3Schools](https://www.w3schools.com/html/html_css.asp)

## External CSS

       gnfru5gfdibfr5tvfofr6otgoy7uhnjupy
