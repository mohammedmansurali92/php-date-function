# php-date-function
PHP Date Function
<!DOCTYPE HTML>
<html lang="en-US">
<head>
	<meta charset="UTF-8">
	<title>New</title>
	<style>
	.error{
		color:#ff0000;
	}
	</style>
</head>
<body>
 <?php
 echo "To day is:".Date("y/m/d")."<br>";
 echo "To day is:".Date("y-m-d")."<br>";
 echo "To day is:".Date("y.m.d")."<br>";
 echo "To day is:".Date("l");
 
 ?>
	<?php
echo "The Time is:".Date("h.i.sa");
?>
	<?php
$d= mktime(11,14,54,12,8,2014);
echo "The create time is:".date("d-m-y h:i:sa",$d)
?>
</body>
</html>
