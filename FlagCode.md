<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>Denmark Flag</title>
</head>

<body>
	<canvas id="myCanvas" width="350" height="200" style="border; 10px solid #d3d3d3; background: red"></canvas>
	
<script>
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.beginPath("2d");
ctx.strokeStyle = "white";
ctx.lineWidth = 30;
ctx.moveTo(100, 0);
ctx.lineTo(100, 250);
ctx.stroke();
var c = document.getElementById("myCanvas");
var ctx = c.getContext("2d");
ctx.beginPath();
ctx.moveTo(0, 95);
ctx.lineTo(400, 95);
ctx.stroke();
</script>
</body>
</html>
