<!DOCTYPE html>
<html lang="en">
<head>
<title>Hello</title>
<link rel="stylesheet" href="C:\Users\Maftunabonu\Desktop\New folder\something.css">
</head>
<body>
	<nav>
		<ul class="topnav" id="dropDownClick">
		<li><a href="https://mover.uz/video/humor">Home</a></li>
		<li><a href="https://google.com">Films</a></li>
		<li><a href="https://google.com">TV</a></li>
		<li><a href="https://google.com">Games</a></li>
	<li><a href="https://google.com">Music</a></li>
	<li><a href="https://google.com">Auto</a></li>
	<li><a href="https://google.com">Sport</a></li>
	<li><a href="https://google.com">Anime</a></li>
	<li class="topnav-right"><a href="https://google.com">Sign In</a></li>
	<li class="topnav-right"><a href="https://google.com">Sign Up</a></li>
	<li class="dropdownIcon"><a href="javascript:void(0);" onclick="dropDownMenu()">&#9776;</a></li>
</ul>
	</nav>

	<div class="container" id="section1">
		<div class="row">
			<div class="col-6 leftSide-col">
				<div>
				<h1 class="large">Welcome to my page</h1>
				<h1 class="large">made from heart</h1>
			</div>
			<form>
				<div>
					<h2>Username</h2>
					<input class="inputbox" name="username" type="text" placeholder="Username">
					<h2>Password</h2>
					<input class="inputbox" type="text" name ="password"placeholder="Password">
				</div>
			</form>
		</div>
			<div class="col-6">
				<h1>Welcome to my page</h1>
				<h1 >made from heart</h1>
			</div>
		</div>


	</div>


	<script>
		function dropDownMenu(){
			var x = document.getElementById("dropDownClick");
			if(x.className === "topnav"){
				x.className += " reponsive";
			}else{
			x.className="topnav";}}
	</script>
</body>
</html>
