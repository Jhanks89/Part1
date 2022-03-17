<head>
<meta charset="utf-8">
<title>CNIT 133 Homework4 - Part 1</title>
<link rel="stylesheet" type="text/css" href="hw4parts.css">
<link rel="shortcut icon" type="image/x-icon" href="favicon.ico">
<link rel="stylesheet" href="//code.jquery.com/ui/1.12.1/themes/base/jquery-ui.css">
<script src="https://code.jquery.com/jquery-1.12.4.js"></script>
<script src="https://code.jquery.com/ui/1.12.1/jquery-ui.js"></script>
<script type="text/javascript" src="hw4part1.js"></script>

<style>
#draggable { 
	width: 100px; 
	height: 30px; 
	padding: 1em; 
	border: 2px solid black;
}
</style>
<br>
</head>
<section class="container">
	<br>
	<h3>Calculate Product/Sum</h3>
	<br>
	<form name="myform">
	<br>
		<div id="sum" class="box"></div>
		<br>
		<div id="product" class="box"></div>
		<br>
		<div id="sum2" class="box"></div>
		<br>
		<div id="product2" class="box"></div>
		<br>
		<input type="button" onclick="calculate()" value="Calculate">
		<input type="reset" value="RESET" onclick="window.location.reload();">
		<br>
		<br>
		<h2 id="draggable" class="ui-widget-content ui-draggable ui-draggable-handle" style="position: relative;">(Draggable) Results:</h2>
		<br>
		<textarea rows="15" cols="50" name="result"></textarea>
		<br>
		<br>
	</form>
	<br>
</section>
