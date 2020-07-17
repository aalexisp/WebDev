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

<p align="center">
	<img src="https://github.com/aalexisp/WebDev/blob/master/IMAGES/image0.png" width=60%>
</p>

### HTML Tags

The Tags are the essential coding of HTML.
We can classify some of them as:
 - **Inline Elements**
 	- They don't start in a new line and take the necessary width
```html
	<span>, <img>, <a>
```

 - **Block Elements**
 	- Start on a new line and takes full width avaliable
	
```html
	<div>, <h1>..<h6>, <p>, <form>
```

### We can find all the tags in [TAGS](https://www.w3schools.com/tags/default.asp)

### HTML Attributes

We can also find something called Attributes which add functionallities to our tags.
	- All tags have attributes
	- Provide information about an element
	- Placed within the start tag
	- Key/value pairs: key="value"
It's syntax is:

```html
<tagname attribute="attributevalue">content</tagname>
```
