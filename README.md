# bootstrap-website
<html>
    <head>
        <title>Custom Website</title>
        <link rel="stylesheet" href="Assets/style.css">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
        <script src="https://code.jquery.com/jquery-3.4.1.slim.min.js"></script>
        <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css">
    </head>
    <body>
        <!--Navigation bar-->
        <section id="nav-bar">
            <nav class="navbar navbar-expand-lg navbar-light">
                <a class="navbar-brand" href="#"><img src="img\logo.png"></a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                  <ul class="navbar-nav ml-auto">
                    <li class="nav-item active">
                      <a class="nav-link" href="#top">Home</a>
                    </!--<li>
                    <li class="nav-item">
                        <a class="nav-link" href="#about">About US</a>
                      </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#services">Services</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#team">Our Team</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#price">Our Plans</a>
                    </li>
                    <li class="nav-item">
                    	<li class="nav-item">
                      <a class="nav-link" href="#testimonials">Testimonials</a>
                    </li>
                    <li class="nav-item">
                      <a class="nav-link" href="#contact">Contact Us</a>
                    </li>
                  </ul>
                </div>
              </nav> 
        </section>
        <!--Slider-->
	        <div id="Slider" class="carousel slide" data-ride="carousel">
			  <ol class="carousel-indicators">
			    <li data-target="#headerSlider" data-slide-to="0" class="active"></li>
			    <li data-target="#headerSlider" data-slide-to="1"></li>
			    <li data-target="#headerSlider" data-slide-to="2"></li>
			  </ol>
			  <div class="carousel-inner">
			    <div class="carousel-item active">
			      <img  class="d-block w-100" src="img/photo-1574428512652-01ca1eb6f1ed.jpg">
			      <div class="carousel-caption">
			      		<h5>How To Make A Website</h5>
			      </div>
			    </div>
			    <div class="carousel-item">
			      <img  class="d-block w-100" src="img/photo-1575275399996-823555c24cd5.jpg">
			      <div class="carousel-caption">
			      		<h5>How To Make A Website</h5>
			      </div>
			    </div>
			    <div class="carousel-item">
			      <img  class="d-block w-100" src="img/photo-1575211447836-6b5943b34a03.jpg">
			      <div class="carousel-caption">
			      		<h5>How To Make A Website</h5>
			      </div>
			    </div>
			  </div>
			  <a class="carousel-control-prev" href="#headerSlider" role="button" data-slide="prev">
			    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
			    <span class="sr-only">Previous</span>
			  </a>
			  <a class="carousel-control-next" href="#headerSlider" role="button" data-slide="next">
			    <span class="carousel-control-next-icon" aria-hidden="true"></span>
			    <span class="sr-only">Next</span>
			  </a>
			</div>
			 <!--About Section-->
			<section id="about">
				<div class="container">
					<div class="row">
						<div class="col-md-6">
							<h2>About Us</h2>
							<div class="about-content">
								content goes here content goes here content goes here content goes here
								content goes here content goes here content goes here content goes here
								content goes here content goes here content goes here content goes here
								content goes here content goes here content goes here content goes here
								content goes here content goes here content goes here content goes here
								content goes here content goes here content goes here content goes here
							</div>
							<button type="button" class="btn btn-primary">Read More >></button>
						</div>
						<div class="col-md-6 skills-bar">
							<p>Web Development</p>
							<div class="progress">
								<div class="progress-bar" style="width: 85%;">85%</div>
						</div>
						<p>WordPress</p>
							<div class="progress">
								<div class="progress-bar" style="width: 85%;">85%</div>
						</div>
						<p>Bootstrap</p>
							<div class="progress">
								<div class="progress-bar" style="width: 85%;">85%</div>
						</div>
						<p>Adobe Photoshop</p>
							<div class="progress">
								<div class="progress-bar" style="width: 85%;">85%</div>
						</div>
					</div>
				</div>
			</section>
			<section id="services">
				<div class="container">
					<h1>Our Services</h1>	
				<div class="row services">
					<div class="col-md-3 text-center">
						<div class="icon">
							<i class="fa fa-laptop"></i>
						</div>
						<h3>Web Development</h3>
						<p>Content goes here Content goes here Content goes here Content goes here</p>
					</div>
					<div class="col-md-3 text-center">
						<div class="icon">
							<i class="fa fa-tablet"></i>
						</div>
						<h3>Mobile App</h3>
						<p>Content goes here Content goes here Content goes here Content goes here</p>
					</div>
					<div class="col-md-3 text-center">
						<div class="icon">
							<i class="fa fa-line-chart"></i>
						</div>
						<h3>Digital Marketing</h3>
						<p>Content goes here Content goes here Content goes here Content goes here</p>
					</div>
					<div class="col-md-3 text-center">
						<div class="icon">
							<i class="fa fa-paint-brush"></i>
						</div>
						<h3>Graphic Design</h3>
						<p>Content goes here Content goes here Content goes here Content goes here</p>
					</div> 
				</div>				
				</div>
			</section>
			<section id="team">
				<div class="container">
					<h1>Our Team</h1>
					<div class="row">
					<div class="col-md-3 profile-pic text-center">
						<div class="img-box">
							<img src="img/Profile-round-babs.png" class="img-responsive">
							<ul>
								<a href="#"><i><i class="fab fa-facebook-f"></i></i></a>
								<a href="#"><i><i class="fa fa instagram"></i></i></a>
								<a href="#"><i><i class="fa fa twitter"></i></i></a>
							</ul>
						</div>
						<h2>Usama</h2>
						<h3>Founder/CEO</h3>
						<p>Content goes here Content goes here Content goes here  </p>
					</div>

					<div class="col-md-3 profile-pic text-center">
						<div class="img-box">
							<img src="img/Profile-round-pj.png" class="img-responsive">
							<ul>
								<a href="#"><i><i class="fab fa-facebook-f"></i></i></a>
								<a href="#"><i><i class="fa fa instagram"></i></i></a>
								<a href="#"><i><i class="fa fa twitter"></i></i></a>
							</ul>
						</div>
						<h2>Usama</h2>
						<h3>Founder/CEO</h3>
						<p>Content goes here Content goes here Content goes here  </p>
					</div>
					<div class="col-md-3 profile-pic text-center">
						<div class="img-box">
							<img src="img/Bianca+profile+round+(1).png" class="img-responsive">
							<ul>
								<a href="#"><i><i class="fab fa-facebook-f"></i></i></a>
								<a href="#"><i><i class="fa fa instagram"></i></i></a>
								<a href="#"><i><i class="fa fa twitter"></i></i></a>
							</ul>
						</div>
						<h2>Usama</h2>
						<h3>Founder/CEO</h3>
						<p>Content goes here Content goes here Content goes here  </p>
					</div>
					<div class="col-md-3 profile-pic text-center">
						<div class="img-box">
							<img src="img/profilecircle-768x814.png" class="img-responsive">
							<ul>
								<a href="#"><i><i class="fab fa-facebook-f"></i></i></a>
								<a href="#"><i><i class="fa fa instagram"></i></i></a>
								<a href="#"><i><i class="fa fa twitter"></i></i></a>
							</ul>
						</div>
						<h2>Usama</h2>
						<h3>Founder/CEO</h3>
						<p>Content goes here Content goes here Content goes here  </p>
					</div>
					</div>
				</div>
			</section>
			<!---Promo--->
			<section id="promo">
				<div class="container">
					<p>Get Free Domain Name and Web Hosting</p>
					<a href="#" class="btn btn-primary">Contact Us</a>
				</div>
			</section>
			<!---price plans section-->
			<section id="price">
				<div class="container">
					<h1>Price Plans</h1>
					<div class="row">
					<div class="col-md-3">
						<div class="single-price">
						<div class="price-head">
							<h2>Free</h2>
							<p>$0<span>month</span></p>
						</div>
						<div class="price-content">
							<ul>
								<li><i class="fa fa-check-circle"></i>5GB Space</li>
								<li><i class="fa fa-check-circle"></i>10GB Bandwith</li>
								<li><i class="fa fa-times-circle"></i>15 Email Account</li>
								<li><i class="fa fa-times-circle"></i>Unlimited Domain</li>
								<li><i class="fa fa-times-circle"></i>Unlimited Suport</li>
							</ul>
						</div>
							<div class="price-button">
								<a class="buy-btn" href="#">Join</a>
							</div>
						</div>
					</div>
					<div class="col-md-3">
						<div class="single-price">
						<div class="price-head">
							<h2>Start Up</h2>
							<p>$10<span>month</span></p>
						</div>
						<div class="price-content">
							<ul>
								<li><i class="fa fa-check-circle"></i>50GB Space</li>
								<li><i class="fa fa-check-circle"></i>100GB Bandwith</li>
								<li><i class="fa fa-check-circle"></i>15 Email Account</li>
								<li><i class="fa fa-times-circle"></i>Unlimited Domain</li>
								<li><i class="fa fa-times-circle"></i>Unlimited Suport</li>
							</ul>
						</div>
							<div class="price-button">
								<a class="buy-btn" href="#">Buy Now</a>
							</div>
						</div>
					</div>
					<div class="col-md-3">
						<div class="single-price">
						<div class="price-head">
							<h2>Bussiness</h2>
							<p>$50<span>month</span></p>
						</div>
						<div class="price-content">
							<ul>
								<li><i class="fa fa-check-circle"></i>20GB Space</li>
								<li><i class="fa fa-check-circle"></i>200 GB Bandwith</li>
								<li><i class="fa fa-check-circle"></i>50 Email Account</li>
								<li><i class="fa fa-check-circle"></i>Unlimited Domain</li>
								<li><i class="fa fa-times-circle"></i>Unlimited Suport</li>
							</ul>
						</div>
							<div class="price-button">
								<a class="buy-btn" href="#">Buy Now</a>
							</div>
						</div>
					</div>
					<div class="col-md-3">
						<div class="single-price">
						<div class="price-head">
							<h2>Advance</h2>
							<p>$100<span>month</span></p>
						</div>
						<div class="price-content">
							<ul>
								<li><i class="fa fa-check-circle"></i>50GB Space</li>
								<li><i class="fa fa-check-circle"></i>Unlimited Bandwith</li>
								<li><i class="fa fa-check-circle"></i>Unlimited Account</li>
								<li><i class="fa fa-check-circle"></i>Unlimited Domain</li>
								<li><i class="fa fa-check-circle"></i>Unlimited Suport</li>
							</ul>
						</div>
							<div class="price-button">
								<a class="buy-btn" href="#">Buy Now</a>
							</div>
						</div>
					</div>
					</div>
				</div>
			</section>
			<!----Testimonials---->
			<section id="testimonials">
				<div class="container">
					<h1>Testimonials</h1>
					<p class="text-center">content goes here content goes here content goes here content goes here </p>
					<div class="row">
						<div class="col-md-4 text-center">
							<div class="profile">
								<img class="user" src="img/Profile-round-babs.png">		
							<blockquote>
								Content goes here Content goes here Content goes here Content goes here Content goes here Content goes here Content goes here 
							</blockquote>
							<h3>Usama <span>Co-Founder at ABC</span></h3>
							</div>
						</div>
						<div class="col-md-4 text-center">
							<div class="profile">
								<img class="user" src="img/Bianca+profile+round+(1).png">	
							<blockquote>
								Content goes here Content goes here Content goes here Content goes here Content goes here Content goes here Content goes here 
							</blockquote>
							<h3>Usama <span>Co-Founder at ABC</span></h3>
							</div>
						</div>
						<div class="col-md-4 text-center">
							<div class="profile">
								<img class="user" src="img/Profile-round-pj.png">	
							<blockquote>
								Content goes here Content goes here Content goes here Content goes here Content goes here Content goes here Content goes here 
							</blockquote>
							<h3>Usama <span>Co-Founder at ABC</span></h3>
							</div>
						</div>
					</div>
				</div>
			</section>
			<!---Get in Touch--->
			<section id="contact">
				<div class="container">
					<h1>Get in Touch</h1>
					<div class="row">
						<div class="col-md-6">
							<form class="Contact-form">
								<div class="form-group">
									<input type="text" class="form-control" placeholder="Your Name">
								</div>
								<div class="form-group">
									<input type="text" class="form-control" placeholder="Your Email">
								</div>
								<div class="form-group">
									<input type="number" class="form-control" placeholder="Your Phone Number">
								</div>
								<div class="form-group">
									<textarea  class="form-control" rows="4" placeholder="Your Message" name=""></textarea>
								</div>
								<button type="submit" class="btn btn-primary">Send Message</button>
							</form>
						</div>
						<div class="col-md-6 contact-info">
							<div class="follow"><i class="fa fa-map-marker"></i><b>Address:</b>XYZ Road, Karachi, Pakistan</div>
						
							<div class="follow"><i class="fa fa-envelope"></i><b>Email:</b>Sample@gmail.com</div>

							<div class="follow"><i class="fa fa-phone"></i><b>Phone Number:</b>000-1111-2222</div>
							<div class="follow">
								<label><b>Get Social</b></label>
								<a href=""><i class="fa fa-facebook-square"></i></a>
								<a href=""><i class="fa fa-twitter-square"></i></a>
								<a href=""><i class="fa fa-instagram"></i></a>
								<a href=""><i class="fa fa-pinterest-square"></i></a>
								<a href=""><i class="fa fa-youtube"></i></a>
							</div>
						</div>
					</div>
			</section>
			<!----Footer---->
			<section id="footer">
			<div class="container text-center">
				<p class="text-center">All Right Reserved Made <i class="fa fa-heart-o"></i> By Shafique Ahmed Kolachi</p>
			</div>
			</section>
			<!----footer End---->
			<script src="js/smooth-scroll.js"></script>
			<script>
				var scroll = new SmoothScroll('a[href*="#"]');
			</script>
    </body>
</html>
