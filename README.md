# Dummycodes.github.io
<html>
<head><title>Sign UP</title>
</head>
<body>

	<fieldset style="background:lightblue;width:500px;height:550px;margin:0vh 27vw; border-width:30px; font-size:20px;"><legend style="background-color:pink;color:black;">Sign Up Here</legend>
<center>
 <img src="C:\Users\krishna\Desktop\wow.png" alt="image" height="100px" width="100px">
<table><tr><td>
Name:</tr><tr><td><input type="text" placeholder="Enter Name" required></td></tr><tr><td>
Middle Name:</tr></td><tr><td><input type="text" placeholder="Enter Mname" required></td></tr><tr><td>
Last Name:</tr></td><tr><td><input type="text" placeholder="Enter LName" required></td></tr><tr><td>
Phone No.:</tr></td><tr><td> <input type="text" maxlenght="10" placeholder="Enter Name" required></td></tr><tr><td>
Create password:</tr></td><tr><td><input type="password" placeholder="Enter Name" required></td></tr><tr><td>
Match password:</tr></td><tr><td><input type="password" placeholder="Enter Name" required></td></tr><tr><td>
Address:-</td></tr><tr><td><input type="text" placeholder="Enter Adress" required>
</table>
<button value="submit" onclick="kyascene()" style="color:red;" >submit</button>
</center>
</fieldset>

</body>
<script>
 function kyascene()
{
	alert('successfully login the page now you sumbit your cppl experiment')
    
}
</script>
</html>
 
<head><title>login</title>
</head>
<body>
<form action="login.php" method="post">
	<fieldset style="background:lightgoldenrodyellow;width:40px;margin:25vh 40vw; border-width:40px; font-size:20px;"><legend style="background-color:yellow;color:red;">Login Here</legend>

			Name:<input type="text" name="name" placeholder="kya scene" title="Enter:-cppl" id="lid" required><br><br>
			Password:<input type="password" name="pass" placeholder="kyascene" title="Enter password" id="pass" required><br><br>
		
	<button type="submit" onclick="getme()" id="btn">Login</button>&emsp;<button type="button"><a href="signup.html">Sign Up</a></button>
<div id="show"></div>
	</fieldset>
</form>
</body>
<script>
function getme(){
if(document.getElementById('lid').value=="krishna"&&document.getElementById('pass').value=="krishna"){
document.write("Login successfull")
}else{
	document.getElementById("show").innerHTML="Invalid login";
}

}

</script>

</html>
