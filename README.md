<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<!-- For Mobile Friendly -->
    <meta name="viewport" content="width=device-width, initial-scale=1">

	<title>Portfolio. - Snehal Bhojane</title>

	<!-- Custom css -->
	<link rel="stylesheet" type="text/css" href="css/style.css">
	<link rel="stylesheet" type="text/css" href="css/responsive.css">

	<!-- Bootstrap css -->
	<link rel="stylesheet" type="text/css" href="css/bootstrap.css">
	<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">

	<!-- Custom js -->
	<script type="text/javascript" src="js/customJs.js"></script>

	<!-- Bootstrap js -->
	<script type="text/javascript" src="js/bootstrap.js"></script>
	<script type="text/javascript" src="js/bootstrap.min.js"></script>
	<script type="text/javascript" src="js/bootstrap.bundle.min.js"></script>

	<!-- Font awesome icon -->
	<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>

<!-- start navbar -->
	<header class="topbar sticky-top">
		<nav class="navbar navbar-expand-lg">
	  		<div class="container">
	    		<a class="navbar-brand logo" href="#">Portf<span>olio.</span></a>
	    		<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
	      			<span class="navbar-toggler-icon"></span>
	    		</button>
	   			<div class="collapse navbar-collapse" id="navbarNav">
	      			<ul class="navbar-nav ml-500 ml-0">
	        			<li class="nav-item">
	          				<a class="nav-link active" aria-current="page" href="#home">Home</a>
	        			</li>
	        			<li class="nav-item">
	          				<a class="nav-link" href="#about">About</a>
	        			</li>
	        			<li class="nav-item">
	          				<a class="nav-link" href="#">Skills</a>
	        			</li>
	        			<li class="nav-item">
	          				<a class="nav-link" href="#">Projects</a>
	        			</li>
	        			<li class="nav-item">
	          				<a class="nav-link" href="#">Blog</a>
	        			</li>
	        			<li class="nav-item">
	          				<a class="nav-link" href="#">Contact</a>
	        			</li>
	    			</ul>
	    		</div>
	  		</div>
		</nav>
	</header>

<!-- start home section -->
	<section class="home"  id="home" style="background: url('images/home-banner.jpg');">
		<div class="container">
			<div class="row">
				<div class="col-lg-5 home-right">
					&nbsp;
				</div>
				<div class="col-lg-7 home-left">
					<div class="home-content">
						<div class="text-1">Hello, my name is</div>
						<div class="text-2">Snehal Bhojane</div>
						<div class="text-3">And I'm a <span class="sub-text"></span></div>
					</div>
				</div>
				
			</div>
		</div>
	</section>

<!-- start about section -->
	<section class="about-section mt-20" id="about">
		<div class="container">
			<div class="row about-title">
				<h2 class="text-center">About</h2>
				<h6 class="text-center">who i am</h6>
			</div>
			<div class="row p-15">
				<div class="col-lg-5 col-mg-5 col-sm-12 about-left">
					<img src="images/dummy-image.jpg" width="100%" height="100%">
				</div>
				<div class="col-lg-7 col-mg-5 col-sm-12 about-right text-left">
					<h5>I'm Snehal Bhojane</h5>
					<p>
						I have completed master's degree in computer science (MCS) in 2019. I have completed bachelor's degree in computer science (BCS) and 12th from Marathwada Mitra's College, pune. And schooling from Janta high school, pune.
					</p>
					<p>
						Now I am pusucing <strong>"Full Stack Developer - JAVA" </strong>course from <strong>"SEED Infotech institute"</strong>
					</p>
					<a href="files/snehalbhojane.pdf"><button type="button" class="btn btn-outline-danger">Download resume</button></a>
				</div>
			</div>
		</div>
	</section>

	

<!-- start footer section -->	

	<footer class="footer-section mt-20">
		<div class="container">
			<div class="row">
				<div class="col-lg-12 footer-content">
					<p class="text-center">Created by <strong><span>Snehal Bhojane</span></strong> | &copy; 2022. All rights reserved.</p>
				</div>
			</div>
		</div>
	</footer>

<!-- Popper -->
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>

<!-- for banner text animation -->
	<script type="text/javascript">
		const text = document.querySelector(".sub-text");

		const textLoad = () =>{
			setTimeout(() => {
				text.textContent = "Developer";
			}, 0);
			setTimeout(() => {
				text.textContent = "Designer";
			}, 1000);
			setTimeout(() => {
				text.textContent = "Freelancer";
			}, 2000);
		}
		textLoad();
		setInterval(textLoad, 3000);
	</script>
</body>
</html>
