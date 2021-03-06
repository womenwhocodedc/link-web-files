# Linking up Web Files
This is meant to be the simplest of examples for how you move on from something like [Codecademy](http://www.codecademy.com/)'s Javascript lesson to working with files on your computer. This doc covers some basics with a few examples but you should download the zip to see how they all work in tandem. At the [bottom there are exercises]() which you'll need the source files for anyway.

## Hooking up CSS
To link to a CSS file you use a ```link rel```. An example is below:

```html
<link rel="stylesheet" href="css/main.css">
```

The important thing to notice here is that the link is _relative:_ this means that the files are within the current project folder. This is diferent from an [absolute link](#hooking-up-javascript), which you've probably also written. One thing you should never write is this:

```html
<link rel="stylesheet" href="C://username/Documents/code/my-project/css/main.css">
```

This is linking to a file on your computer, which other people can't see when you upload your files to a web server. (Not to mention that the short link is a lot easier to read.)

## Hooking up Javascript
```html
<script src="js/main.js"></script>
```

Like our CSS above, the link is relative. It's a pretty common thing to use absolute links too with javascript, such as linking to jQuery:

```html
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
```

Again, with your javascript files, you should never write something like this:

```html
<script src="C://username/Documents/code/my-project/js/main.js"></script>
```

Absolute links are bad. Still don't get it? You can read more about [relative and absolute links here](http://www.coffeecup.com/help/articles/absolute-vs-relative-pathslinks/).

## Exercises
With your new-found knowledge, complete the follwing:

1. Change all of the ```EDIT ME```s in ```index.html```

2. Leave your middle name in a comment

3. Add an image from the ```img```s folder

4. Check the console, solve the error <br>
	<em>Where's my console? [Find it here!](https://developer.chrome.com/devtools/index)</em>

5. Create a paragraph tag, write a little bit about yourself

6. Write about yourself in the paragraph tag

7. Change the ```background-color``` of your paragraph to ```tomato```

8. Write a javascript function that adds two numbers together and logs the number to the console

### Colophon
The ```index.html``` is a modified version of [HTML5 Boilerplate](http://html5boilerplate.com/), which is a pretty great way to start any project.

The relative vs. absolute link article is from [Coffeecup.com](http://www.coffeecup.com/help/articles/absolute-vs-relative-pathslinks/).

The images are from [@helenvholmes' Instagram](http://instagram.com/helenvholmes).