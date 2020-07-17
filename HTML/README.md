## HTML ESSENTIALS

### What do we need ? 

 - Text editor ([Notepad++](https://notepad-plus-plus.org/downloads/))
 - Browser ([Google Chrome](https://www.google.com/intl/es_es/chrome/))
 
### Need to know

 - In it's essence HTML doesn't need a server to run
 - Files must end in format **.html**
 - Runs in a browser
 - **index.html** is the root/home page of a website
   - What this means is:
     - http://foo.org loads **index.html**
     - http://foo.org/about.html loads **about.html**
 - We can start testing locally
 
### In order to make it public

 - Need to buy a domain
 - Hosting package

## SYNTAX

### HTML Page Structure

<p align="center">
	<img src="https://github.com/aalexisp/WebDev/blob/master/IMAGES/image0.png" width=60%>
</p>


```html
<!-- This is a declaration and tells the browser in what HTML this is written in. This one is for HTML5 -->
<!DOCTYPE html>
<html> 
	<!-- This tag works like metadata for the browser and gives information about the page. This is not displayed -->
	<head>
		<title> Page Title </title>
	</head>
	
	<!-- This is what we really display in our page -->
	<body>
		<!-- This tag is used for your headers -->
		<h1>My First Heading</h1> 
		<!-- This other tag is used for your paragraphs -->
		<p>My First Paragraph.</p>
	</body>
</html>
```
