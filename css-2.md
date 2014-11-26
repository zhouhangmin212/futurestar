# rgba color and opacity

- rgba(0,0,0.0.7)
- opacity:0.7;

--------------

# safe font and web font

[http://www.cssfontstack.com/](http://www.cssfontstack.com/)

- 中文的字体
- 开源Google Webfonts, Typekit


--------------

#  retina image

if a normal size image working on retina device, it looks ugly.

	.icons {
    	background-image: url(icon-sprite.png);
    	background-repeat: no-repeat;
	}

	@media only screen and (-Webkit-min-device-pixel-ratio: 1.5),
	only screen and (-moz-min-device-pixel-ratio: 1.5),
	only screen and (-o-min-device-pixel-ratio: 3/2),
	only screen and (min-device-pixel-ratio: 1.5) {
    	.icons {
        	background-image: url(icon-sprite-2x.png);
        	background-size: 200px 100px;
        	background-repeat: no-repeat;
    	}
	}
	
-----------------
# css spirit

![icon](http://www.w3schools.com/css/img_navsprites_hover.gif)

	#home a:hover {
    background: url('img_navsprites_hover.gif') 0 -45px;
	}

	#prev a:hover {
    background: url('img_navsprites_hover.gif') -47px -45px;
	}

	#next a:hover {
    background: url('img_navsprites_hover.gif') -91px -45px;
	}

-----------------
#grid layout

[bootstrap](http://getbootstrap.com/) ie9+ mobile first

[kiwi](https://github.com/tuxlinuxien) loweprofero ie8 project,our design is not mobile first, so this is not a good choice

---------------------

# icon-font

- [fontawesome](http://fortawesome.github.io/Font-Awesome/)
- [icon moon](https://icomoon.io/)

-------------------
#stylus

[stylus](http://learnboost.github.io/stylus/)

------------------
#resposive design

[link](http://mediaqueri.es/)

