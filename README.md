<!-- required:
   1. theme = /
   2. navigation = /
   3. button = /
   4. transition = /
   5. dialog = /
   -->
   
<!DOCTYPE html>
<html>
<head>
	<title>My Mobile Page</title>
	<link rel="stylesheet" href="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.css" />
	<script src="https://code.jquery.com/jquery-1.11.1.min.js"></script>
	
	<link rel="stylesheet" href="https://github.com/nureen00/nureen00.github.io/blob/main/nureen.min.css" />
	<link rel="stylesheet" href="themes/jquery.mobile.icons.min.css" />

	<script src="https://code.jquery.com/mobile/1.4.5/jquery.mobile-1.4.5.min.js"></script>
</head>

<body>

	<!-- Page 1 -->
	<div data-role="page" id="page1" data-theme="d">
		<div data-role="header">
			<h1>NUREEN AISYAH'S PROFILE</h1>
			
			<div data-role="navbar"> <!-- NAVIGATION BAR & TRANSITION -->
				<ul>
					<li> <a href="#page1" data-icon="grid" data-transition="flow">Personal Information</a> </li>
					<li> <a href="#page2" data-icon="heart" data-transition="flow">Hobby</a> </li>
					<li> <a href="#page3" data-icon="heart" data-transition="flow">Family Background</a> </li>
					<li> <a href="#page4" data-icon="heart" data-transition="flow">Exam Result</a> </li>
				</ul>
			</div>
			
		</div>
		<div data-role="main" class="ui-content">
			<center>
			<img src="https://i.pinimg.com/750x/a8/8f/ea/a88fea7ec04194a75e3773faf5454570.jpg" alt="woman" height=320 width=200>
			<h1>MY PERSONAL INFORMATION</h1>
			</center>
			<p>NAME :<B> NUREEN AISYAH BINTI HALIP</B></p>
			<p>AGE : <B>20 Y/O</B></p>
			<p>BIRTH DATE : <B>13 FEBRUARY 2003</B></p>
			<p>BIRTHPLACE : <B>HOSPITAL TENGKU AMPUAN RAHIMAH, KLANG, SELANGOR</B></p>
			<p>OCCUPATION : <B>STUDENT</B></p>
			
			<!-- LIST VIEW -->
			<div data-role="collapsible">
				<h3>Education</h3>
				<p><b>2008 - 2009 :</b> Tadika Permata Ilmu</p>
				<p><b>2010 - 2016 :</b> Sekolah Kebangsaan Meru, Sekolah Rendah Agama Pekan Meru </p>
				<p><b>2017 - 2021 :</b> Sekolah Menengah Kebangsaan Meru</p>
				<p><b>2021 - present :</b> Politeknik Sultan Mizan Zainal Abidin</p>
			</div>
			<div data-role="collapsible">
				<h3>Languange</h3>
				<ul>
					<li>Malay</li>
					<li>English</li>
					<li>Javanese</li>
				</ul>
				
			</div>
			
			<!-- <a href="#page2" data-transition="flow">Go To Page 2</a> -->
		</div>
		<div data-role="footer">
			<h2>&copy; Web Class 2021</h2>
		</div>
	</div>
	
	<!-- page 2 -->
	<div data-role="page" id="page2" data-theme="e">
		<div data-role="header">
			<h1>NUREEN AISYAH'S PROFILE</h1>
			
			<div data-role="navbar"> <!-- NAVIGATION BAR & TRANSITION -->
				<ul>
					<li> <a href="#page1" data-icon="grid" data-transition="flow">Personal Information</a> </li>
					<li> <a href="#page2" data-icon="heart" data-transition="flow">Hobby</a> </li>
					<li> <a href="#page3" data-icon="heart" data-transition="flow">Family Background</a> </li>
					<li> <a href="#page4" data-icon="heart" data-transition="flow">Exam Result</a> </li>
				</ul>
			</div>
			
		</div>
		<div data-role="main" class="ui-content">
			<h1>NUREEN'S HOBBY</h1>
			
		<div>  		
			<button onclick="window.dialog.show();">QUOTES OF THE DAY</button>
			
			<dialog id="dialog">
				"Hobbies are great distractions from the worries and troubles that plague daily living."<br> - Bill Malone
				<button onclick="window.dialog.close();">CLOSE</button>
			</dialog>
			<br><br><br><br><br><br><br><br>
			
			<div data-role="collapsible">
				<h4>Current Watch K-drama List</h4>
				<ul data-role="listview" data-inset="true">
					<li><a href="https://youtu.be/L7LfpZoLDlI">
						<img src="https://i.pinimg.com/564x/ed/a7/e5/eda7e5abe26db01c22a39767fd26b418.jpg">
						<h2>DR. CHA</h2>
						<p>Netflix</p></a>
					</li>
					
					<li><a href="https://youtu.be/wyk2FtMAXfY">
						<img src="https://i.pinimg.com/564x/2b/52/53/2b52530a170eba2e981f4fa39afcc605.jpg">
						<h2>THE GOOD BAD MOTHER</h2>
						<p>Netflix</p></a>
					</li>
					
					<li><a href="https://youtu.be/XteTtBH28hM">
						<img src="https://i.pinimg.com/564x/b1/23/fa/b123faaa2c135a312badb836d1e8e119.jpg">
						<h2>MISSING : THE OTHER SIDE</h2>
						<p>Viu</p></a>
					</li>
				</ul>
			</div>
			
			<div data-role="collapsible">
				<h4>Favorite Music List</h4>
				
				<ul data-role="listview" data-inset="true">
					<li><a href="https://youtu.be/eN5mG_yMDiM">
						<img src="https://cdn1.kgasa.com/wp-content/uploads/2022/04/BIGBANG-Still-Life.jpg">
						<h2>BIGBANG - Still Alive</h2>
						<p>Year : 2022</p></a>
					</li>
				
					<li><a href="https://youtu.be/ZbD2IU0J9Jw">							
						<img src="https://i.ytimg.com/an/j4ckkzbbETk/19c8ed04-c9e5-4271-b8b8-9ccd47684a06_mq.jpg?v=5bfca685">
						<h2>INSOMNIACKS - Pulang </h2>
						<p>Year : 2018</p></a>
					</li>
						
					<li><a href="https://youtu.be/k-9DOwrLdkg">
						<img src="https://i.pinimg.com/564x/8a/35/28/8a352817d584298282d8d1d092a79313.jpg">
						<h2>LABRINTH & ZENDAYA - All For Us</h2>
						<p>Year : 2019</p></a>
					</li>
				</ul>
			</div>
			
			<!-- <a href="#page2" data-transition="flow">Go To Page 2</a> -->
		</div>
		<div data-role="footer">
			<h2>&copy; Web Class 2021</h2>
		</div>
	</div>
	</div>
	
	<!-- Page 3 -->
	<div data-role="page" id="page3" data-theme="f">
		<div data-role="header">
			<h1>NUREEN AISYAH'S PROFILE</h1>
			
			<div data-role="navbar"> <!-- NAVIGATION BAR & TRANSITION -->
				<ul>
					<li> <a href="#page1" data-icon="grid" data-transition="flow">Personal Information</a> </li>
					<li> <a href="#page2" data-icon="heart" data-transition="flow">Hobby</a> </li>
					<li> <a href="#page3" data-icon="heart" data-transition="flow">Family Background</a> </li>
					<li> <a href="#page4" data-icon="heart" data-transition="flow">Exam Result</a> </li>
				</ul>
			</div>
		</div>
		<div data-role="main" class="ui-content">
			<center>
			<h1>HALIP'S FAMILY</h1>
			
			<a href="#fam" data-rel="popup" data-position-to="window" class="ui-btn ui-corner-all ui-shadow ui-btn-inline">FAMILY PICTURE</a>
				
				<div data-role="popup" id="fam" class="photopopup" data-overlay-theme="a" data-corners="false" data-tolerance="30,15">
					<a href="#" data-rel="back" class="ui-btn ui-corner-all ui-shadow ui-btn-a ui-icon-delete ui-btn-icon-notext 	ui-btn-right">Close</a>
					<img src="https://i.pinimg.com/564x/f6/b1/0e/f6b10ebcbf5188ca4d7a2b99f52d98e9.jpg" alt="fam">
				</div>
			</center>
			
			<p><b>Halip and Ruhaya's family</b> was blessed with 5 children, 3 boys and 2 girls. All of them live in Selangor. Among the 5 brothers, 3 of them are already working while the other 2 are still studying at IPTA.</p>
			
		<ul data-role="listview" data-inset="true">
			<li>
				<img src="https://i.pinimg.com/564x/41/b1/38/41b138a269d021d0f8505f37a44ccdae.jpg" width=400px; height=650px;>
				<h2>MR. HALIP BIN AHMAT@AHMAD</h2>
				<p>Father</p></a>
			</li>
			
			<li>
				<img src="https://i.pinimg.com/564x/80/c0/ba/80c0badf5c1e135ffc0993e175fa4d9e.jpg" width=400px; height=650px;>
				<h2>MRS. RUHAYA BINTI OTHMAN</h2>
				<p>Mother</p></a>
			</li>
			
			<li>
				<img src="https://i.pinimg.com/564x/dd/97/c9/dd97c9b0405274e557b03568d209e590.jpg" width=400px; height=650px;>
				<h2>ARIFF AZHAR BIN HALIP</h2>
				<p>Brother</p>
				<p>30 y/o</p>
				<p>1st sibling</p></a>
			</li>
			
			<li>
				<img src="https://i.pinimg.com/564x/9d/63/46/9d634682f32ce4e13278f7098a6da742.jpg" width=400px; height=650px;>
				<h2>NORDIANA BINTI HALIP</h2>
				<p>Sister</p>
				<p>26 y/o</p>
				<p>2nd sibling</p></a>
			</li>
			
			<li>
				<img src="https://i.pinimg.com/564x/bb/6e/3f/bb6e3f6acdc8d5aab3bbf265554b945a.jpg" width=400px; height=650px;>
				<h2>MUHAMMAD SAIFUL BIN HALIP</h2>
				<p>Brother</p>
				<p>25 y/o</p>
				<p>3rd sibling</p></a>
			</li>
			
			<li>
				<img src="https://i.pinimg.com/564x/a5/69/cb/a569cbda71079625db1454517b97e4e4.jpg" width=400px; height=650px;>
				<h2>NUREEN AISYAH BINTI HALIP</h2>
				<p>Myself</p>
				<p>20 y/o</p>
				<p>4th sibling</p></a>
			</li>
			
			<li>
				<img src="https://i.pinimg.com/564x/dd/41/3c/dd413ca157de15a226f266b8d94b7db7.jpg" width=400px; height=650px>
				<h2>MUHAMMAD SYAFIQ FITRI BIN HALIP</h2>
				<p>Lil. brother</p>
				<p>19 y/o</p>
				<p>5th sibling</p></a>
			</li>
		</ul>
	
		</div>
		<div data-role="footer">
			<h2>&copy; Web Class 2021</h2>
		</div>
	</div>
	
	<!-- Page 4 -->
	<div data-role="page" id="page4" data-theme="g">
		<div data-role="header">
			<h1>NUREEN AISYAH'S PROFILE</h1>
			
			<div data-role="navbar"> <!-- NAVIGATION BAR & TRANSITION -->
				<ul>
					<li> <a href="#page1" data-icon="grid" data-transition="flow">Personal Information</a> </li>
					<li> <a href="#page2" data-icon="heart" data-transition="flow">Hobby</a> </li>
					<li> <a href="#page3" data-icon="heart" data-transition="flow">Family Background</a> </li>
					<li> <a href="#page4" data-icon="heart" data-transition="flow">Exam Result</a> </li>
				</ul>
			</div>
		</div>
		<div data-role="main" class="ui-content">
		<CENTER>
			<h1>EXAM RESULT</h1>
			<P>Results for each semester for Diploma in Information Technology at PSMZA</p>
			<br>
			<ul data-role="listview"> <!-- BUTTON -->
				<a href="#sem1" data-rel="popup" data-position-to="window" class="ui-btn ui-corner-all ui-shadow ui-btn-inline">SEM 1</a>
				
				<div data-role="popup" id="sem1" class="photopopup" data-overlay-theme="a" data-corners="false" data-tolerance="30,15">
					<a href="#" data-rel="back" class="ui-btn ui-corner-all ui-shadow ui-btn-a ui-icon-delete ui-btn-icon-notext 	ui-btn-right">Close</a>
					<img src="C:\Users\halip\OneDrive\Pictures\Screenshots\Screenshot 2023-05-08 012634.png" alt="sem1">
				</div>
				
				<a href="#sem2" data-rel="popup" data-position-to="window" class="ui-btn ui-corner-all ui-shadow ui-btn-inline">SEM 2</a>
				
				<div data-role="popup" id="sem2" class="photopopup" data-overlay-theme="a" data-corners="false" data-tolerance="30,15">
					<a href="#" data-rel="back" class="ui-btn ui-corner-all ui-shadow ui-btn-a ui-icon-delete ui-btn-icon-notext 	ui-btn-right">Close</a>
					<img src="C:\Users\halip\OneDrive\Pictures\Screenshots\Screenshot 2023-05-08 012647.png" alt="sem2">
				</div>
				
				<a href="#sem3" data-rel="popup" data-position-to="window" class="ui-btn ui-corner-all ui-shadow ui-btn-inline" data-transition="fade">SEM 3</a>
				
				<div data-role="popup" id="sem3" class="photopopup" data-overlay-theme="a" data-corners="false" data-tolerance="30,15">
					<a href="C:\Users\halip\OneDrive\Pictures\Screenshots\Screenshot 2023-05-08 012704.png" data-rel="back" class="ui-btn ui-corner-all ui-shadow ui-btn-a ui-icon-delete ui-btn-icon-notext ui-btn-right">Close</a>
					<img src="C:\Users\halip\OneDrive\Pictures\Screenshots\Screenshot 2023-05-08 012704.png" alt="sem3">
				</div>
				
			</ul>
		</div>
		<br><br><br><br>
		<div data-role="footer">
			<h2>&copy; Web Class 2021</h2>
		</div>
	</div>
</body>
</html>
