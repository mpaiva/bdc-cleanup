bdc-cleanup
===========

Just an old site  - sadly made with frontpage - that needs to be brought back to life. Please check the [Issues](https://github.com/mpaiva/bdc-cleanup/issues) tab for the messy list we need to wipe out.


---

##Cleanup Notes
---
The following are the steps already taken so far.

###BDC-0.0.3
---
* Remove `<link>` to styles
* Remove `<script>` 


###BDC-0.0.2
---
* Run HTML5 Tidy to close all opened `<li>` and convert the latin characters



###BDC-0.0.1
---
#### Remove
* Remove `<body> background` attribute
* Remove `<body> lang` attribute
* Remove `<meta>`
* Remove `<!-- comments -->`
* Remove `<img>`
* Remove `<font>`
* Remove `<form>`
* Remove `<div class="form">`
* Remove `empty tags`
* Remove `<td> bgcolor` attribute
* Remove `<table> border`
* Remove `inline style` attribute
* Remove `class="MsoNormal"`
* Remove `align` attribute
* Remove

	```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
	```



#### Replace

* HTML5 Doctype - Replace / By
	
	```
	<html>
	```
	```
	<!DOCTYPE html>
	<html>
	```

* Adding `section` tag - Replace tag / By
	
	```
	<div class="Section1">
	```
	```
	<section id="content">
	```
* Replace
	
	```
	<i> by <em>
	```	

* Replace
	
	```
	<b> by <strong>
	```		

###BDC-Original
---
Folder structure as it was originally given.	
