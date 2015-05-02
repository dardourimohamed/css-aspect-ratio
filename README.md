# css-aspect-ratio
a css aspect ratio plugin to fix div aspect ratio

by Mohamed Dardouri

usage :
	container class : 
		aspectratio-container aspect-width-height [fit type]
	available aspects :
		square		      	: 1-1
		horisontal aspects	: 4-3, 3-2, 5-3, 16-9, 3-1
		vertical aspects	: 3-4, 2-3, 3-5, 9-16, 1-3

example :
[div class="aspectratio-container aspect-4-3 fit-width"]
	[div class="aspectratio-content"]
		[!--content--]
	[/div]
[/div]
