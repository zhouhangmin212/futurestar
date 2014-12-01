#css

-------------
# CSS reset
- *{margin:0;padding:0}
- [eric reset](http://meyerweb.com/eric/tools/css/reset/)
- [normalize reset](https://github.com/necolas/normalize.css)

----------------
# CSS Specificity

- id .class p span 
- !important
- inline style: style="font-size:20px"
- [权重](http://www.w3cplus.com/css/css-specificity-things-you-should-know.html)

----------------
# Pseudo-class
- :hover
- :after
- :nth(n+1)
- :first-child
- [selectors](http://quirksmode.org/css/selectors/)

-----------------
# CSS Element type
- inline
- block
- inline-block
- visibility:hidden
- table
- [display](http://segmentfault.com/blog/trigkit4/1190000000654770)

----------------
# float element

- clear both
- clearfix 
- over hidden
- IE haslayout
- [float test](http://www.cnblogs.com/polk6/p/3142187.html)
- [haslayout](http://www.qianduan.net/comprehensive-haslayout.html)

----------------
# position 

- absolute
- relative
- fixed
- z-index
- [position](http://www.html-js.com/article/1744)

----------------
# box model

- margin
- padding
- border
- box-sizing:border-box
- [box model](http://www.w3school.com.cn/css/css_boxmodel.asp)

	
---------
# rgba color and opacity

- rgba(0,0,0.0.7)
- opacity:0.7;

----------
# safe font and web font

- [safe font](http://www.cssfontstack.com/)
- 中文的字体
- 开源Google Webfonts, Typekit
- webkit

--------
# retina image
- @2x.png
- background-size

------
# css spirit
![icon](http://www.w3schools.com/css/img_navsprites_hover.gif)
	
	.item0 a:hover {
    	background: url('img_navsprites_hover.gif') 0 		-45px;
	}

	.item1 a:hover {
    	background: url('img_navsprites_hover.gif') -47px 		-45px;
	}

	.item2 a:hover {
    	background: url('img_navsprites_hover.gif') -91px 		-45px;
	}
	
--------
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

	@media (max-width: 300px) {
    	body {
        	background-color: lightblue;
    	}
	}
	
	@media print {
    	p {
        	font-size: 20px;
        	color: red;
    	}
	}

[link](http://mediaqueri.es/)








