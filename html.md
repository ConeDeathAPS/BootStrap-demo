<!DOCTYPE HTML>
<html>
<head>
	<meta charset="utf-8">
	<title>Formula1</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
	<link rel="stylesheet" type="text/css" href="formula1.css">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/css/bootstrap.min.css">
	<script src="http://ajax.googleapis.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script> 
	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.2/js/bootstrap.min.js"></script>
</head>
<body>
	<div class="container">
		<div class="row">
			<div class="col-md-2 col-md-offset-2">
				<button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-haspopup-"true" aria-expanded="true">
					Navigation
					<span class="caret"></span>
				</button>
				<ul class="dropdown-menu">
					<li><a href="#">Home</a></li>
					<li><a href="#">Race Results</a></li>
					<li><a href="#">Driver's Championship</a></li>
					<li><a href="#">Constructor's Championship</a></li>
					<li role="separator" class="divider"></li>
					<li><a href="#">Team Info</a></li>
					<li><a href="#">Driver Info</a></li>
				</ul>
			</div>
			<div class="col-md-2">
				<button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
					Account
					<span class="caret"></span>
				</button>
				<ul class="dropdown-menu">
					<li><a href="#">Preferences</a></li>
					<li><a href="#">Messages</a></li>
					<li><a href="#">Change Teams</a></li>
					<li role="separator" class="divider"></li>
					<li><a href="#">Security Settings</a></li>
					<li><a href="#">Privacy Settings</a></li>
				</ul>
			</div>
			<div class="col-md-2">
				<button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
					Settings
					<span class="caret"></span>
				</button>
				<ul class="dropdown-menu">
					<li><a href="#">Profile</a></li>
					<li><a href="#">Notifications</a></li>
					<li><a href="#">Security</a></li>
					<li role="separator" class="divider"></li>
					<li><a href="#">User Settings</a></li>
				</ul>
			</div>
			<div class="col-md-2 text-center"><input class="btn btn-default" type="button" value="Log Out"></div>
			</div>
		<div class="row">
			<div class="col-md-8 col-md-offset-2">
				<div class="jumbotron">
					<h1>Welcome back!</h1>
					<p id="jumbo">We're happy that you decided to come back! Take a look around, as things have changed since you were last here</p>
					<p><a class="btn btn-primary btn-lg" href="#" role="button">Learn more</a></p>
				</div>
				<div class="alert alert-info" role="alert"><button type="button" class="close" data-dismiss="alert" aria-label="Close"><span 
					aria-hidden="true">&times;</span></button>
					<strong>Look!</strong> This site has been updated since you were last here!</div>
			</div>
		</div>
	</div>
</body>
</html>
