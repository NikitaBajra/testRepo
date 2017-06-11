<html>
<head>
	<title>Form</title>
		<script type = "text/javascript" src = "myScript.js" ></script>
</head>
<body >
	<h1 align = "center" > Admission Form </h1>
	<table>	
		<form onsubmit = "return validate()" method = "post" name = "myform" action = "/nextPage.html">
			<div>	
				<div>
					<img src="image/image1.jpeg" onclick = "myImage()" id = "img" alt = "image">
					<p id="myImage()"></p>
				</div>
				<div>
					<table>
						<tr>
							<th>First Name : </th>
							<td><input type = "text" name = "fname" placeholder = "Enter your first name" id = "fname"></td>
						</tr>

						<tr>
							<th>Last Name : </th>
							<td><input type = "text" name = "lname" placeholder = "Enter your last name" id = "lname"></td>
						</tr>

						<tr>
							<th align = "left">Age : </th>
							<td><input type = "text" name = "age" placeholder = "Enter your age above 18" id = "age"></td>
						</tr>

						<tr>
							<th align = "left" >Hobby : </th>
							<td>
								<input type = "checkbox" name = "dance">Dance<br>
								<input type = "checkbox" name = "sing">Sing<br>
								<input type = "checkbox" name = "music">Music<br>
								<input type = "checkbox" name = "adventure">Adventure<br>
								<input type = "checkbox" name = "story">Read stories and noble<br>
								<input type = "checkbox" name = "othesr">Others<br>
							</td>
						</tr>

						<tr>
							<th align = "left" id= "code">Code : </th>
							<td><input type="text" name = "code" placeholder = "Enter any 5 numeber separated by comma"></td>
						</tr>

						<tr>
							<td>
								<input type = "submit" name = "submit" value = "Submit">
							</td>
						</tr>
					</table>
				</div>
			</div>
		</form>
	</table>

	
</body>
</html>