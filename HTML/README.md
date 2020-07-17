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

#### We can find all the tags in [TAGS](https://www.w3schools.com/tags/default.asp)

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

### HTML Attributes

#### We can find all the Attributes in [ATTRIBUTES](https://www.w3schools.com/tags/ref_attributes.asp)

We can also find something called Attributes which add functionallities to our tags.
	- All tags have attributes
	- Provide information about an element
	- Placed within the start tag
	- Key/value pairs: key="value"
It's syntax is:

```html
<tagname attribute="attributevalue">content</tagname>
```

### HTML Lists

Lists are something essential in HTML and so we have some types.

 - **Unordered lists**
 
```html
<ul>
	<li>Item List 1<li>
	<li>Item List 2<li>
</ul>
```

 - **Ordered lists**

```html
<ol>
	<li>Item List 1<li>
	<li>Item List 2<li>
</ol>
```

### HTML Tables

Tables are also very usefull things for sorting things well.

```html
<table>
	<thead>
		<tr>
			<th>Name</th>
			<th>Age</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Alexis</td>
			<td>20</td>
		</tr>
		<tr>
			<td>Mike</td>
			<td>20</td>
		</tr>
	</tbody>
	
</table>
```

### HTML Forms

Forms are needed when we want a log in, send emails...
Anyway we should know that just by usig HTML the forms won't work and we'll need CSS or PHP to apply methods.
Furthermore we have to know that the form tag is an inline element and we can use a div to avoid make a jump line

```html
<form action="process.php" method="POST">
	<div>
		<label>First Name</label>
		<input type="text" name="firstName" placeholder="Enter first name">
	</div>
	<div>
		<label>Second Name</label>
		<input type="text" name="secondName">
	</div>
	<div>
		<label>Email</label>
		<input type="email" name="email">
	</div>
	<div>
		<label>Message</label>
		<textarea name="message"></textarea>
	</div>
	<div>
		<label>Gender</label>
		<select name="gender">
			<option value="Male"></option>
			<option value="Female"></option>
			<option value="Other"></option>
		</select>
	</div>
	<div>
		<label>Age:</label>
		<input type="number" name="age" value="30">
	</div>
	<div>
		<label>Birthday:</label>
		<input type="date" name="birthday">
	</div>
</form>

```

### Usefull things

We can find some usefull things which will be replace with CSS coding but they have to be explained.

```html
It's like \n, endl.
<br>
Makes a line
<hr> 
```
