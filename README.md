#Flakes.js

##Running

simply include these two lines at the bottom of your page:

```HTML
<canvas id="flakes"></canvas>
<script src="flakes.js"></script>
```

If you want this to be responsive to resizing windows, add a window.resize listener:

```javascript
window.onresize = function(){
	document.getElementById("flakes").width 	= window.innerWidth;
	document.getElementById("flakes").height	= winodw.innerHeight;
}
```
