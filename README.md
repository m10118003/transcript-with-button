# transcript-with-button
 Use javascript and html to make the interface and button

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
	<input type="number" id="score">
	<button onclick="grades('score')">Calculate!</button> 

    <script>
		function grades() {
			let grades = document.getElementById("score").value
			if (grades >= 100) {
				alert('Perfect')				
			} else if (grades >= 90 && grades < 100) {
				alert('A+')
				// console.log("A+");
			} else if (grades >= 80 && grades < 90) {
				alert('A')
				// console.log("A");
			} else if (grades >= 70 && grades < 80) {
				alert('B')
				// console.log("B");
			} else if (grades >= 60 && grades < 70) {
				alert('C')
				// console.log("C");
			} else if (grades >= 59) {
				alert('D')
				// console.log("D");
			}        
		}
    </script>
</body>

</html>
