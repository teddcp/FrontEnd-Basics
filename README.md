# FrontEnd-Basics
<body>
<div>
<p> 1. Headers : <br>
   h1, h2, h3, h4, h5, h6 are the headers in which h1 is the largest header(in font) and h6 is the smallest </p>
<br>
examples:
<h1>Biggest</h1>
<h6>smallest</h6>
<div>

<div>
<p> 2. Paragraph: <br> 
   p tag is used for paragraphs and broswers erases the extra spaces and lines while displaying . 
   To keep the extra space and line we can use the <a href='https://www.w3schools.com/html/tryit.asp?filename=tryhtml_pre'>pre tag</a>
</p>
</div>


	<h2>Forms Basics</h2><br>
	<form action="default.py" method="post" >
		<fieldset>
			<legend>Personal Information</legend>
			First name : <br>
			<input type="text" name="First name" value="" placeholder="Enter the first name" autofocus><br>
			Last name : <br>
			<input type="password" name="Password" value=""><br>
			Gender:<br>
			<input type="radio" name="gender" value="Male" checked>Male<br>
			<input type="radio" name="gender" value="FeMale">FeMale<br>
			<input type="radio" name="gender" value="Others">Others<br>
			<br>

			choose one option<br>
			<input type="checkbox" name="passed" value="passed" checked>passed in semester<br>
			<input type="checkbox" name="failed" value="failed">failed in semester<br><br>
			<br>
			<input type="image" src="img_submit.gif" alt="Submit" width="48" height="48">
			<br><br>
			(Using select tag)<br>
			Choose the exam you have<br>
			<select name="exam">
				<option value="Internal">Internal</option>
				<option value="External">External</option>
				<option value="semester" selected mutiple>Semester</option>
			</select><br>
			<!-- selected for to choose a default value and mutiple for selecting multiple values-->
			<br><br>
			(using datalist) select the paper you have<br>
			<input list="dropdown2">
				<datalist id="dropdown2">
					<option value="Math">Math</option>
					<option value="Physics">Physics</option>
					<option value="Chemistry">Chemistry</option>
				</datalist>

			<br><br>
			Enter additional comments if any:<br>
			<textarea name="message" style="width:200px; height:100px;" maxlength="3">
			<!--enter the text that you wan to display in textare-->
			</textarea>
			<br>
			<br>
			<button type="button" onclick="alert('Hello World!')" disabled>Click Me!</button>
			&nbsp;
			<input type="submit" name="submit" value="submit">
			&nsp;
			<input type="reset" name="reset" >
			<br><br>
			<b>HTML5 added attributes (including datalist and output) :</b><br>
			1. Choose your favourite Color :<br>
			<input type="color" name="fav" value="red"><br><br>
			2.Choose your bday :<br>
			<input type="date" name="bday" min="1979-02-01" max="5000-02-20"><br><br>
			3. choose your bday with timestamp :<br>
			<input type="datetime-local" name="bdayTime"><br>
			4.Enter your Email address:<br>
			<input type="Email" name="EmailAddress" required><br><br>
			5.Upload your photo<br>
			<input type="file" name="UploadFile"><br>
			6.Enter your passed month and year:<br>
			<input type="month" name="Passed year and month"><br>
			7.Enter your age: <br>
			<input type="number" name="age" min="18" max="35" step="1"><br>
			8.Choose a random Point :<br>
			<input type="range" name="ChooseOne" min="0" max="10"><br><br>
			9.Enter to search  in search bar:<br>
			<input type="search" name="google"><br>
			10.Enter your telephone number: <br>
			<input type="tel" name="telephonenum" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}"><br>
			11.Enter the cuurent time:<br>
			<input type="time" name="UserTime"><br><br>
			12.enter the github address :<br>
			<input type="url" name="github address"><br><br>
			13.Enter your bday week: <br>
			<input type="week" name="week_year"><br><br>

</body>

