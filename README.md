# 🌟 New-Repository 
# 📌 to make all the files work together github--> github pages --> will make all the html + css + js work together --> this is called project deployment  

<!DOCTYPE html>
 <html>
 <head> 
<title>Bootstrap 101 Template</title> 
<meta name="viewport" content="width=device-width, initial-scale=1.0">
 <!-- Bootstrap --> 
<link href="css/bootstrap.min.css" rel="stylesheet"> 
</head>
<body> 
<h1>Hello, world!</h1>
 <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
 <script src=“https://code.jquery.com/jquery.js”></script>
 <!-- Include all compiled plugins (below), or include individual files as needed --> 
<script src="js/bootstrap.min.js"></script>
<!DOCTYPE html>
 <html lang="en"> 
<head> <title>Bootstrap - Breakpoint</title>
 <meta charset="UTF-8"> 
<meta http-equiv="X-UA-Compatible" content="IE=edge">
 <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet"> <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"> </script> 
<style> 
.custom-class { 
display: none; 
} 
@media (min-width: 768px) 
{ .custom-class { 
display: block; } @media (min-width: 768px) { .custom-class { display: block; } } </style> </head>
<body> 
    
<h5>This block is visible on all devices</h5> 
<div class="container-fluid mt-2 "> <div class="row"> 
<div class="col-md-6 bg-warning p-3"> md-6 warning 
</div> 
</div> 
</div><br> 
<h5>This block is not visible for sm breakpoint but visible for other breakpoints</h5> 
<div class="container-fluid mt-2 custom-class"> 
<div class="row"> 
<div class="col-md-6 bg-warning p-3"> md-6 warning
 </div> 
</div> 
</div>


/* <div class="card-deck"> 
	<div class="card"> 
		<img class="card-img-top" src="trial.jpg" alt="Card image cap"> 
		<div class="card-body"> 
			<h5 class="card-title">Card title</h5> 
			<p class="card-text">Sample Card text</p> 

			<p class="card-text"> 
				<small class="text-muted"> 
					Sample paragraph 
				</small> 
			</p> 

		</div> 
	</div> 
	<div class="card"> 
		<img class="card-img-top" src="trial.jpg"
			alt="Card image cap"> 
		<div class="card-body"> 
			<h5 class="card-title">Card title</h5> 
			<p class="card-text">Sample Card text</p> 

			<p class="card-text"> 
				<small class="text-muted"> 
					Sample paragraph 
				</small> 
			</p> 

		</div> 
	</div> 
	<div class="card"> 
		<img class="card-img-top" src="trial.jpg"
			alt="Card image cap"> 
		<div class="card-body"> 
			<h5 class="card-title">Card title</h5> 
			<p class="card-text">Sample Card text</p> 

			<p class="card-text"> 
				<small class="text-muted"> 
					Sample paragraph 
				</small> 
			</p> 

		</div> 
	</div> 
</div> */
<div class="form-check"> 
    <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault"> 
    <label class="form-check-label" for="flexCheckDefault"> 
        Default checkbox 
    </label> 
    </div> 
    <div class="form-check"> 
    <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1"> 
    <label class="form-check-label" for="flexRadioDefault1"> 
        Default radio 
    </label> 
    </div> 
    <div class="form-check form-switch"> 
    <input class="form-check-input" type="checkbox" id="flexSwitchCheckDefault"> 
    <label class="form-check-label" for="flexSwitchCheckDefault"> 
        Default switch checkbox input 
    </label> 
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" 
          content="width=device-width, 
                   initial-scale=1.0">
    <title>Bootstrap 5 Layout Breakpoints Example</title>
    <!-- Add the Bootstrap CSS link -->
    <link href=
"https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" 
          rel="stylesheet">
</head>
<body>
    <div class="container text-center mt-5">
        <h2>
            Welcome To
            <span class="text-success">
                GFG
            </span>
        </h2>
        <p>
            Default code has been loaded 
            into the Editor.
        </p>
        <div class="row">
            <div class="col-sm-4 bg-primary">
                Column 1
            </div>
            <div class="col-sm-4 bg-info">
                Column 2
            </div>
            <div class="col-sm-4 bg-danger">
                Column 3
            </div>
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">

<head>
	<meta charset="UTF-8">
	<meta name="viewport" content=
		"width=device-width, initial-scale=1.0">
	<link href=
"https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css"
		rel="stylesheet"
		>
</head>

<body>
	<h1 class="text-success">
		Welcome
	</h1>
	<h3>Bootstrap 5 Columns</h3>

	<div class="container">
		<div class="row">
			<div class="col-2 text-white bg-primary">
				Col 2
			</div>
			<div class="col-3 text-white bg-secondary">
				Col 3
			</div>
			<div class="col-4 text-white bg-info">
				Col 4
			</div>
		</div>
	</div>
</body>

</html>
<!DOCTYPE html>
<html>

<head>
	<!-- Bootstrap CDN -->
	<link rel="stylesheet"
		href=
"https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/css/bootstrap.min.css"
		crossorigin="anonymous"> 
</head>

<body class="m-2">
	<h1 class="text-success"> Group-10 </h1>
	<h3>Bootstrap5 Layout Utilities</h3>
	<br>
	<section class="d-inline p-2 bg-primary text-white">
		 inline element
	</section>
	<br>
	<br>
	<section class="d-block p-2 bg-dark text-white">
		 block element
	</section>
</body>
</html>
<!DOCTYPE html>
<html>

<head>
	<!-- Bootstrap CDN -->
	<link rel="stylesheet"
		href=
"https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/css/bootstrap.min.css"
		crossorigin="anonymous">
</head>

<body class="m-2">
	<h1 class="text-success"> Welcome </h1>
	<h3>Bootstrap5 Layout Utilities</h3>
	<br>
	<p><b>normal form of rows</b></p>
	<section>
		<div class="p-2 border">G 1</div>
		<div class="p-2 border">G 2</div>
		<div class="p-2 border">G 3</div>
	</section>
	<br>
	<p><b>When we applied display property in rows</b></p>
	<section class="d-flex ">
		<div class="p-2 border">G 1</div>
		<div class="p-2 border">G 2</div>
		<div class="p-2 border">G 3</div>
	</section> 
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <title> Bootstrap 5 Borders </title>
    <link href=
"https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" 
        rel="stylesheet" integrity=
"sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" 
            crossorigin="anonymous">
    <script src=
"https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
            integrity=
"sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
            crossorigin="anonymous">
    </script>
</head>

<body>
    <h2 class="text-center">Bootstrap 5 Borders</h2>
    <div class="text-center">
        <span class="border border-4">1</span>
        <span class="border-top border-5">2</span>
        <span class="border-end border-4">3</span>
        <span class="border-bottom border-5">4</span>
        <span class="border-start border-3">5</span>  
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <title> Bootstrap 5 Borders </title>
    <link href=
"https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" 
         rel="stylesheet" integrity=
"sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" 
         crossorigin="anonymous">
    <script src=
"https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
            integrity=
"sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
            crossorigin="anonymous">
    </script>
</head>

<body>
    <h2 class="text-center">
        Bootstrap 5 Borders
    </h2>
    <div class="text-center">
        <span class="border border-primary">
            1
        </span>
        <span class="border border-secondary">
            2
        </span>
        <span class="border border-success">
            3
        </span>
        <span class="border border-danger">
            4
        </span>
        <span class="border border-warning">
            5
        </span>
        <span class="border border-info">
            6
        </span>
        <span class="border border-light">
            7
        </span>
        <span class="border border-dark">
            8
        </span>
        <span class="border border-white">
            9
        </span>
    </div>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>
        Bootstrap 5 | Alerts
    </title>
    <!-- Load Bootstrap -->
    <link rel="stylesheet" href=
"https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/css/bootstrap.min.css">
</head>
<body>
    <div style="text-align: center;
            width:600px;">
        <h1 style="color: green;">
            Group 10
        </h1>
    </div>
    <div id="canvas" style="width: 600px;
            height: 200px; margin: 20px;">
        <div class="alert alert-primary" role="alert">
            Group 10
        </div>
        <div class="alert alert-secondary" role="alert">
            Group 10
        </div>
        <div class="alert alert-success" role="alert">
            Group 10
        </div>
        <div class="alert alert-danger" role="alert">
            Group 10
        </div>
        <div class="alert alert-warning" role="alert">
            Group 10
        </div>
        <div class="alert alert-info" role="alert">
            Group 10
        </div>
        <div class="alert alert-light" role="alert">
            Group 10
        </div>
        <div class="alert alert-dark" role="alert">
            Group 10
        </div>
    </div>
</body>
</html>
<!DOCTYPE html>
<html>
  
<head>
    <title>
        Bootstrap 5 | Buttons
    </title>
    <!-- Load Bootstrap -->
    <link rel="stylesheet" href=
"https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/css/bootstrap.min.css"
        integrity=
"sha384-r4NyP46KrjDleawBgD5tp8Y7UzmLA05oM1iAEQ17CSuDqnUK2+k9luXQOfXJCJ4I" 
        crossorigin="anonymous">
</head>
<body style="text-align:center;" style="width:700px;">
    <div class="container mt-3">
        <h1 style="color:green;">
            G10
        </h1>
        <h2>Block Level Buttons</h2>
        <button type="button" 
            class="btn btn-block btn-primary">
            Block Level Button
        </button>
        <button type="button" 
            class="btn btn-block btn-success">
            Block Level Button
        </button>
    </div>
</body>
  </html>
  <!DOCTYPE html> 
<html> 

<head> 
	<link rel="stylesheet" href= 
"https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
		integrity= 
"sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm"
		crossorigin="anonymous"> 

	<style> 
		.jumbotron-image { 
			background-position: center center; 
			background-repeat: no-repeat; 
			background-size: cover; 
		} 
	</style> 
</head> 

<body> 
	<div class="jumbotron text-white jumbotron-image shadow"
		style="background-image: url() "> 
		<h2 class="mb-4"> 
			Jumbotron with background image 
		</h2> 

		<p class="mb-4"> 
			Hey, check this out. 
		</p> 

		<a class="btn btn-primary"> 
			Click! 
		</a> 
	</div> 
</body> 

</html>
<!DOCTYPE html> 
<html> 

<head> 
	<link rel="stylesheet" href= 
"https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css"
		integrity= 
"sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm"
		crossorigin="anonymous"> 
</head> 

<body> 
	<div class="jumbotron"> 
		<h1>Text to catch user attention/greeting.</h1> 
		<p class="lead">lorem ipsum.</p> 

		<hr class="my-4"> 
		
		<p>Some dummy text</p> 
	</div> 
</body> 
</html>
