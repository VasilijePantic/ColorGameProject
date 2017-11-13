# ColorGameProject

ColorGameProject is an app created mainly using JavaScript with alot of object manipulation. Alongside JavaScript, CSS and HTML
files are somewhat long and have a certain level of complexity for a beginer.

It's a simple, one player game and it is repetative. The point is to match the RGB color from the top to it's real visual color 
from the squares in the bottom. Depending on which mode you chose,you are able to switch between eazy mode with 3 colors
to pick from and bewtween hard mode. Hard mode has 6 color options and the game will always start on hard mode.

When you pick the matching color,all the squares will gain that color. But when you choice is poor, the square you picked
will dissappear. That will happen to evey square until your choice is right.

You are also able to reset all the color options clicking on the "New Colors" button,so automatically,the game will reset.

This app was logic was mostly based around 'eventListeners' to manipulate the objects,functions and 'if' statements to chose between the objects.

Code example:
	

	function randomColor() {
		//pick a "red" from 0 - 255
		var r = Math.floor(Math.random() * 256);
		//pick a "green" from 0 - 255
		var g = Math.floor(Math.random() * 256);
		//pick a "blue" from 0 - 255
		var b = Math.floor(Math.random() * 256);
		return "rgb(" + r + ", " + g + ", " + b + ")";
	};

The app works perfectly and is full responsive.

This project is a direct result JavaScript and DOM learning process from Udemy's "The Web Developer Bootcamp" as a codealong project to summ
up all the major things learned until this point.
