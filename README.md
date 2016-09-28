# jquery.simplegallery
jQuery plugin for creating image galleries with capability of rotation   
[Plugin home page: documentation, example, getting started guide](http://codengineering.ru/post/33).

##Usage
1) Simple image gallery has two dependencies: [jquery](http://jquery.com/) and [font-awesome](http://fontawesome.io/). 
You need to attacch it to your page before attaching Simple image gallery.
2) Download Simple image gallery from github or install via npm ```npm install jquery-simplegallery```; attach it to your page.
3) Generate markup of image gallery like:   
```html
<div class="simple_img_gallery">
	<a href="images/1.jpg"><img src="images/1.jpg" /></a>
	<a href="images/2.jpg"><img src="images/2.jpg" /></a>
	<a href="images/3.jpg"><img src="images/3.jpg" /></a>
	<a href="images/4.jpg"><img src="images/4.jpg" /></a>
	<a href="images/5.jpg"><img src="images/5.jpg" /></a>
</div>
```   
4) Initialize Simple image gallery using js:   
```js
$(function() {
	$('.simple_img_gallery').createSimpleImgGallery();
});
```

##Build
To compile Simple image gallery by yourself, first of make sure that you have [Node.js](Node.js) 
and [Grunt.js](https://github.com/cowboy/grunt).   
1) Copy repository   
```
https://github.com/Serganbus/jquery.simplegallery.git
```   
2) Now simply run ```grunt``` to generate JS and CSS in folder ```release```.

##Licencs
Script is MIT licensed and free and will always be kept this way.
