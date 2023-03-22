<!DOCTYPE html>
<html>
<head>
	<title>Counting from 1 to 69</title>
	<style>
		#counter {
			font-size: 100px;
			text-align: center;
			margin-top: 50px;
		}
	</style>
</head>
<body>

<div id="counter">1</div>

<script>
	var count = 1;
	var interval = setInterval(function() {
		if (count < 69) {
			count++;
			document.getElementById("counter").innerHTML = count;
		} else {
			clearInterval(interval);
		}
	}, 1000);
</script>

</body>
</html>
