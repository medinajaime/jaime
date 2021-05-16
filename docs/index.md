<!DOCTYPE html>
<html>
<head>
	<title>Forms</title>
</head>
<body>
	<form action="http://example.com/subscribe.php" method="get">
		<p>Username:
			<input type="text" name="username" size="15" maxlength="30">
		</p>
		<p>Password:
			<input type="password" name="password" size="15" maxlength="30" placeholder="password">
		</p>
		<hr />
	</form>
	<form action="http://example.com/subscribe.php" method="get">
		<p>What do you think of the gig?</p>
		<textarea name="comments" cols="20" rows="4"> Enter your comments...</textarea>
	</form>
	<hr>
	<form action="http://www.example.com/profile.php">
		<p>
			Please select your favourite genre:
			<br />
			<input type="radio" name="genre" value="rock" checked="checked" /> Rock
			<input type="radio" name="genre" value="pop" /> Pop
			<input type="radio" name="genre" value="jazz" /> Jazz
		</p>
	</form>
	<hr />
	
	<form action="http://www.example.com/subscribe.php">
		<p>Please select your favourite music service:
			<br />
			<br />
			<input type="checkbox" name="service" value="itunes"> iTunes
			<input type="checkbox" name="service" value="lastfm" checked="checked">Last.fm
			<input type="checkbox" name="service" value="spotify"> Spotify
		</p>
	</form>
	<hr />
	<form action="http://www.example.com/profile.php">
		<p>
			What device do you listen to music on?
			<select name="devices">
				<option value="ipod">Ipod</option>
				<option value="radio">Radio</option>
				<option value="computer" selected="selected">Computer</option>
			</select>
		</p>
	</form>
	<hr />
	<form action="http://www.example.com/subscribe.php">
		<p>
			Do you play any of the following instruments?
			(You can select more than one option by holding down control on a PC or command key on Mac while selecting different options.)
		</p>
		<select name="instruments" size="3" multiple="multiple">
			<option value="guitar">Guitar</option>
			<option value="drums">Drums</option>
			<option value="keyboard">Keyboard</option>
			<option value="Bass">Bass</option>
		</select>
	</form>
	<hr />
	<form action="http://example.com/subscribe.php">
		<p>Upload your song in MP3 format:</p>
		<input type="file" name="user-song"><br />
		<input type="submit" name="Upload">
	</form>
	<hr />
	<form action="http://example.com/subscribe.php">
		<p>Subscribe to our email list:</p>
		<input type="text" name="email">
		<input type="submit" name="Subscribe" value="Subscribe">
	</form>
	<form action="http://example.com/subscribe.php">
		<p>Subscribe to our email list:</p>
		<input type="text" name="email">
		<input type="image" src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fd2omoky3s7n2wz.cloudfront.net%2Frg%2520misc%2520youtube%2520subscribe%2520button%2520small.png&f=1&nofb=1" width="100" height="20">
	</form>
	<hr />
	<form>
		<button><img src="https://products.aspose.app/page/signature/content/img/processing.gif" alt="Add" width="10" height="10" />Add</button>
		<input type="hidden" name="bookmark" value="lyrics">
	</form>
	<hr />
	<label>Age: <input type="text" name="age"></label> <br />
	Gender:
	<input id="female" type="radio" name="gender">
	<label for="female">Female</label>
	<input id="male" type="radio" name="gender">
	<label for="male">Male</label>
	<hr />
	<fieldset>
		<legend>Contact Details</legend>
		<label>Email:<br />
		<input type="text" name="email" /></label><br />
		<label>Mobile <br />
		<input type="text" name="mobile" /></label><br />
		<label>Telephone <br />
		<input type="text" name="Telephone"></label>
	</fieldset>
	<hr />
	<form action="http://www.example.com/login/" method="post">
		<label for="username">Username:</label>
		<input type="text" name="username" required="required" ><br />
		<label for="password">Password:</label>
		<input type="password" name="password" required="required">
		<input type="submit" value="Submit">
	</form>
	<hr />
	<form action="http://www.example.com/bookings/" method="post">
		<label for="username">Departure Date</label>
		<input type="date" name="depart">
		<input type="submit" name="Submit">
	</form>
	<hr />
	<iframe src="https://open.spotify.com/embed/playlist/37i9dQZF1E391Xmb4QN3M2" width="300" height="380" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
	<form action="http://www.example.com/subscribe.php">
		<p>Please enter your email address:</p>
		<input type="email" name="email">
		<input type="submit" name="submit">
	</form>
	<hr />
	<form>
		<p>Please enter an Url:</p>
		<input type="Url" name="Url">
		<input type="submit" name="submit">
	</form>
	<hr />
	<form>
		<p>Search:</p>
		<input type="Search" name="Search">
		<input type="submit" name="Search">
	</form>
	<hr />
	<form>
		<p>Search:
		<input type="Search" name="Search" placeholder="Enter Keyword">
		<input type="Submit" name="Search"></p>
	</form>
</body>
</html>
