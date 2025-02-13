<!DOCTYPE html>
<html>
<head>
<title>
Registration Form</title>
</head>
<body style="background-color : beige;">
<div style="border:4px green solid; border-radius: 20px;">
<center>
<h1> Registration Form</h1>
<marquee style="color : red; font-size:25px;">Registrations are Open </marquee>
<form action="">
First Name:
<input type="text" name="firstname" readonly>
Last Name:
<input type="text" name="lastname">
<br>
Email:<br>
<input type="text" name="emailid">
<br>
Mobile No:<br>
<input type="text" name="mobileno">
<br>
Date of Birth:<br>
<input type="date" name="dob">
<br>
<label for="pAddress">Permanent Address</label>
<br>
<textarea id="pAddress" name="address" rows="4" cols="50"></textarea>
<br>
<br>
<label for="pAddress">Local Address:</label>
<textarea id="pAddress" name="address" rows="1" cols="50">1.8K Hostel,Nit Warangal</textarea>
<br><br>
<label for="pincode">Pincode : </label>
<input type="text" id="pincode">
<br>
<br>
<label for="cg">CGPA:</label>
<input type="float" id="cg">
<p>Favourite Subjects</p>
<label for="maths">Maths</label>
<input type="checkbox" id="maths">
<label for="physics">Physics</label>
<input type="checkbox" id="physics">
<label for="chemistry">Chemistry</label>
<input type="checkbox" id="chemistry">
<br>
<p>Languages Known</p>
<label for="CPP">C++</label>
<input type="checkbox" id="CPP">
<label for="python">Python</label>
<input type="checkbox" id="python">
<label for="java">Java</label>
<input type="checkbox" id="java">
<p>Intrested Area</p>

<select name="dropdown">
<br>
<option value="Machine Learning">Machine Learning</option>
<option value="Maths">Maths</option>
<option value="Physics">Physics</option>
</select>
<br>
<p>select your age</p>
<input type="radio" id="age1" name="age" value="15">
<label for="age1">0 to 15</label>
<br>
<input type="radio" id="age2" name="age" value="30">
<label for="age2">25 to 30</label>
<br>
<p>select your Gender</p>
<input type="radio" id="male" name="gender">
<label for="male">male</label>
<br>
<input type="radio" id="female" name="gender">
<label for="female">female</label>
<br>
<input type="radio" id="other" name="gender">
<label for="other">others</label>
<br>
<br>
<a href="https://erp.nitw.ac.in/erp/login">Check My Resume</a>
<br>
<br>
<button type="button">Reset</button>
<button type="button">submit</button>
</form>
</center>
</div>
</body>
</html>
