<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>My Creative Test Page</title>
	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" />
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<nav>
			<ul>
				<li><a href="#">Home</a></li>
				<li><a href="#">About</a></li>
				<li><a href="#">Services</a></li>
				<li><a href="#">Contact</a></li>
			</ul>
		</nav>
		<div class="hero-image">
			<h1>Welcome to My Creative Test Page</h1>
			<p>Explore and enjoy!</p>
			<a href="#" class="btn">Get Started</a>
		</div>
	</header>
	<section class="services">
		<div class="container">
			<h2>Our Services</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus commodo nulla eget feugiat lacinia. Curabitur euismod, sapien ut egestas dictum, ipsum elit ultricies turpis, a luctus metus magna in elit. </p>
			<div class="services-grid">
				<div class="service">
					<i class="fas fa-code"></i>
					<h3>Web Development</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus commodo nulla eget feugiat lacinia.</p>
				</div>
				<div class="service">
					<i class="fas fa-mobile-alt"></i>
					<h3>Mobile Development</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus commodo nulla eget feugiat lacinia.</p>
				</div>
				<div class="service">
					<i class="fas fa-laptop"></i>
					<h3>Software Development</h3>
					<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus commodo nulla eget feugiat lacinia.</p>
				</div>
			</div>
		</div>
	</section>
	<section class="contact">
		<div class="container">
			<h2>Contact Us</h2>
			<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus commodo nulla eget feugiat lacinia.</p>
			<form action="#" method="POST">
				<label for="name">Name</label>
				<input type="text" id="name" name="name" required>
				<label for="email">Email</label>
				<input type="email" id="email" name="email" required>
				<label for="message">Message</label>
				<textarea id="message" name="message" required></textarea>
				<button type="submit" class="btn">Submit</button>
			</form>
		</div>
	</section>
	<footer>
		<p>© 2023 My Creative Test Page. All Rights Reserved.</p>
	</footer>
</body>
</html>
