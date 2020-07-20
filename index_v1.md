<html>
	<head>
	
		<title>PHP Form Design </title>
		<link rel="stylesheet" href="css/style.css">
	
	</head>
	
	<body>
		
		<div id = "main">
			
			<h1>Contact</h1>
			
			<nav>
				<ul>
					<li><a href="index.php"> Home</a></li>
					<li><a href="page1.php"> Page1</a></li>
					<li><a href="page2.php"> Page2</a></li>
					<li><a href="contact.php"> Contact</a></li>
				</ul>
			</nav>

			<br><br><hr><br>
			
			<!-- FORM -->
			
			<div class="contact_container">
				<form action="mail-text.php" method="post">
				
				<!-- FULL NAME -->
				
				<div class="row">
					<div class="column">
						<label for="fname"> Full Name</label>
					</div>
					<div class="column2">
						<input type="text" id="name" name="name" placeholder="Full name">
					</div>
				</div>
				
				<!-- EMAIL -->
			
				<div class="row">
					<div class="column">
						<label for="email"> Email Address</label>
					</div>
					<div class="column2">
					<input type="text" id="email" name="email" placeholder="your@emailaddress.com">
					</div>
				</div>
			
				<!--- CONTACT NUMBER -->
				
				<div class="row">
					<div class="column">
						<label for="contactnumber"> Contact Number</label>
					</div>
					<div class="column2">
					<input type="text" id="contactnumber" name="contactnumber" placeholder="Phone #">
					</div>
				</div>
				
				<!--- SUBJECT -->
				
				<div class="row">
					<div class="column">
						<label for="subject"> Subject</label>
					</div>
					<div class="column2">
					<textarea id="text" name="body" placeholder="Write in here..." style="height: 200px;"></textarea>
					</div>
				</div>
				
				<!--- SUBMIT BUTTON-->
				
				<div class="row">
					<input type="submit" value="Submit">
				</div>
				
				</form>
			</div>
	
	</body>
	
	
</html>

