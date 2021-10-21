# The fun part of my life
-Watching sports </br>
-Going snowboarding</br>
-Going out downtown</br>
-street racing</br>
-bumping music</br>

[Return to home](README.md)

## A hard part of my life
Trying to code the _Fizzbuzz_ challenge was a **nightmare** but we managed to make it work. Here is the code used for it!
```
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

function fizzbuzz() {
	var display = document.getElementById('display');
	var displayHTML = "";
	for (i = 1; i < 101; i++) {
		if (i%3==0&&i%5==0) {result="FizzBuzz"}
		else if (i%5==0) {result="Buzz"}
		else if (i%3==0) {result="Fizz"}
		else {result=i;}
		displayHTML += "<p>" + result + "</p>";
	}
	display.innerHTML = displayHTML
}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```
