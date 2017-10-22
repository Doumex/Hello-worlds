


<!DOCTYPE html>
<html>
	<head>
		<title></title>
		<link href="cssstyle.css" rel="stylesheet" type="text/css">
		<meta name="viewport" content="width=device-width, initial-scale=1">
	</head>
<body>
	<p> 
		<ul>
			<li><a href="Intertain.html">Sports</a>
				<ul>
					<li><a href="Mario SportsMix.html">Mario</a></li>
					<li><a href="Wii Sports.html">Wii</a></li>
					<li><a href="Sports Champions.html">Champion</a></li>
				</ul>
			</li>
		</ul>	
		<ul>	
			<li><a href="News.html">News</a>
				<ul>
					<li><a href="Shadow of Mordor.html">Shadow</a></li>
					<li><a href="Bioshock Infinite.html">Bioshock</a></li>
					<li><a href="Cosmos And Culture.html">Cosmos</a></li>
				</ul>
			</li>
		</ul>	
	</p>
</body>
</html>


Csstyle.css
body{
	background-image:url(ubuntu1.jpg);
}
ul{
	margin:0px; padding:0px;
}
ul li a{
  text-decoration:none;
  color:white;
  display:block;
  
}
ul li{
	float:left;
	width:90px;
	height:40px;
	background-color:black;
	font-size:20px;
	line-height:40px;
	text-align:center;
	opacity:.7;
	border:4px solid #285189;
}
ul li a:hover{
	background-color:orange
}
ul li ul li{
	display:none;
}
ul li:hover ul li {
	display:block;
}

News.html
<!DOCTYPE html>
<html>
	<head>
		<title></title>
		<link href="cssstyle.css" rel="stylesheet" type="text/css">
		<meta name="viewport" content="width=device-width, initial-scale=1">
	</head>
<body>
		<p><img src="News.png" border= "2px" width= "280px" height="280px />
			<a href="News.html"><h1>News</h1></a>		
				<p><b>November's Next Free Xbox One, Xbox 360 Games With Gold Titles Arrive
					Looking for something new to play?</b>
				</p>
		</p>
</body>
</html>
