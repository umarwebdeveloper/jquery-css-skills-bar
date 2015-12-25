jquery css skills bar
======

**jquery css skills bar** is free, simple and easy to use skills bar jquery and css plugin..

## [Demo](http://umarwebdeveloper.github.io/jquery-css-skills-bar/)

Required Files
```javascript
<script src="js/jquery-2.1.4.min.js"></script>
<script src="js/skill.bars.jquery.js"></script>
```

Call Jquery Function
```javascript
$('.skillbar').skillBars({
		from: 0,
		speed: 4000, 
		interval: 100,
	}); 
```

HTML markup
```html
<div class="skillbar" data-percent="98">
    <span class="skillbar-title" style="background: #d35400;">HTML5</span>
    <p class="skillbar-bar" style="background: #e67e22;"></p>
    <span class="skill-bar-percent"></span>
</div>
```

CSS for styling
```css
.skillbar {
	position:relative;
	display:inline-block;
	margin:15px 0;
	width:100%;
	background:#eee;
	height:35px;
	border-radius:3px;
	width:100%;
}

.skillbar-title {
	position:absolute;
	top:0;
	left:0;
	width:110px;
	font-weight:bold;
	font-size:13px;
	color:#ffffff;
	background:#6adcfa;
	border-top-left-radius:3px;
	border-bottom-left-radius:3px;
	background:rgba(0, 0, 0, 0.1);
	padding:0 20px;
	height:35px;
	line-height:35px;
}

.skillbar-bar {
	height:35px;
	width:0px;
	background:#6adcfa;
	border-radius:3px;
	display:inline-block;
}

.skill-bar-percent {
	position:absolute;
	right:10px;
	top:0;
	font-size:11px;
	height:35px;
	line-height:35px;
	color:#ffffff;
	color:rgba(0, 0, 0, 0.4);
}
```

## Contact
#### @umarwebdeveloper
* e-mail: [umarphpdev@gmail.com](mailto:umarphpdev@gmail.com)

