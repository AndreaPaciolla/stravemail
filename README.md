# STRAVEMAIL

## What?
A simple and lightweighted bootstrap file for emails' templates. Basically the css contains all the classes you need to create a perfect responsive email ( almost, at least ).

## How? 
Let's say the file **example.html** is the email template you wanna send and you have finished the coding phase of the **scss** file. Now you need to put between the **style** tags the **.css** formatted code. At this point I use this [inliner-tool](http://beaker.mailchimp.com/inline-css) by MailChimp to put the css code inline and strip the **style tag**. After that I use [PutsMail](http://putsmail.com/) to test if all works properly. 

## Quick start

### title_box
This class allows you to handle simple title ( with an image beside, if you wish )
```
<div class="title_box">
    <img class="title_logo" src="#">
	<h2 class="title">Le news da non perdere</h2>
	<div class="clean"></div>
</div>
```

### text_box
Just for text
```
<div class="text_box vbottomspace">
    <p>Some text here</p>
</div>
```

### text_image_box
If you wanna put an image beside the a box, to the right or to the left
```
<div class="text_image_box vspace">
    <div class="thumb to_left">
		<img src="#">
	</div>
	<p>some text written here</p>
	<div class="clean"></div>
</div>
```

### nested_boxes
If you wanna put more boxes on a single line. Each image has got a description at the bottom.
```
<div class="nested_boxes three vspace">

	<div class="box">
		<div class="thumb">
			<img src="#">
		</div>
		<p>some description text</p>
	</div>


	<div class="box">
		<div class="thumb">
			<img src="#">
		</div>
		<p>some description text</p>
	</div>


	<div class="box">
		<div class="thumb">
			<img src="#">
		</div>
		<p>some description text</p>
	</div>

	<div class="clean"></div>
</div>
```



### cta_title_button_box
A field which handle a box with a call to action ( title + button )
```
<div class="cta_title_button_box vspace">
	<h2 class="title">
		Have a look to our proposals
	</h2>
	<a href="#">
		<div class="button blue">
			Click here
		</div>	
	</a>
	<div class="clean"></div>
</div>
```

examples here: http://www.andreapaciolla.it/static/stravemail

optimized following http://emailclientmarketshare.com/
