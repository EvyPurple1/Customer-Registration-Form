# Customer-Registration-Form
Customer Registration Form
<!DOCTYPE html>
<html>
 
 <head>
 <title>Customer Registration Form</title>
 	<style>
 		body{
 			background:lightgrey;
 			font-family: arial;
 			line-height: 0.5em;
 		} 
 			#container{
 				overflow: hidden;
 			}
 			.emp{
 				color:black;
 				font-weight: bold;

 			}
 			.side-a{
 				float: left;
 				width: 50%;
 			}
 			}
 	</style>
 </head>
 <body>
 			<div id="container">
 				<div class="side-a">
 	<h1>Customer<span class="emp"> Registration Form</h1>
 	<form action="POST" action="index.php">
 	<fieldset>
 	<legend>Account</legend><br>
 	<br>
 	<label>Name</label><br>
 	<br>
 	<input type="text" name="name" required>	
 	<br><br>

 	<label>Firstname</label><br>
 	<br>
 	<input type="text" name="firstname">	
 	<br><br>

	 <label>Email</label><br>
	 <br>
 	<input type="email" name="email">	
 	<br><br>

 	<label>Password</label><br>
 	<br>
 	<input type="Password" name="Password">
  	<br><br>
  			</div>
  			</div>
  </fieldset>
  <fieldset>
  			<div class="side-b">
  	<legend>User Information</legend>
  	<br>
  	<br>
   <label>Location</label><br>
   <br>
   <select name="location">
   <br>
   		<option value="CA">CA</option>
   		<option value="NY">NY</option>
   </select>
   <br><br>
   	<label>Gender</label><br>
   	<br>
   	<input type="radio" name="gender" value="Male">Male
   	<input type="radio" name="gender" value="Female">
   	Female
    <br>
    <br>
    	<label>Interests</label><br>
    	<br>
   	<input type="checkbox" name="Interests" value="Movies">Movies
   	<input type="checkbox" name="Interests" value="Books">
   	Books
   	<input type="checkbox" name="Interests" value="Art">Art
   	<input type="checkbox" name="Interests" value="Sport">
   	Sport
   	<input type="checkbox" name="Interests" value="Music">Music
    <br><br>	
    </div>
</fieldset>
<br><br>
    <input type="submit" value="submit">
 	</form>


 </body>
 </html>
