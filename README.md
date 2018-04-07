# Web Static Template
My web (HTML) static template.

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>My Template</title>

	<link rel="stylesheet" href="css/bootstrap.min.css">
	<link rel="stylesheet" href="css/style.css">
	<link rel="stylesheet" href="css/flex-box.css">
</head>
<body>
	
	<div class="container flex-box-col">
		<h1>HTML Static Template</h1>
		<p>just a personal template</p>
		<p><img class="img-responsive img-thumbnail" src="assets/iuiuiu.jpg" alt="The developer's inspiration" title="The developer's inspiration"></p>
		<p>the developer's inpsiration...</p>
		<p>2018</p>
	</div>

	<script src="js/jquery-3.3.1.min.js"></script>
	<script src="js/bootstrap.min.js"></script>
</body>
</html>
```

[//]: # ("material.io" vvv )

### Extras
Creating a cheatsheet to view the Material Icons ```css/fonts/MaterialIcons-list.txt``` using Regular Expressions.<br>
**Note**: Use a texteditor that can use a regular expression.

#### Steps
1. **Open** the *material icons* ```.txt``` file
2. **Copy** all the contents
3. **Paste** in a blank text file.
4. **Open** the **Find and Replace** window.
5. **Find** ```\w+```
6. Use snippet below to put in your **Replace**:
```
	<i class="material-icons">$&</i>

```
**Lesson**: ```$&``` is the backreference to the whole match (regular expression)