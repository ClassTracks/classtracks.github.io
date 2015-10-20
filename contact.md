---
layout: default
permalink: /contact/
---

<section class="contact-us">
	<div class="container-fluid hero-title">
		<div class="col-md-12">
			<header class="post-header">
				<h1 class="post-title">Contact Us</h1>
			</header>
		</div>
	</div>
	<div class="container-fluid form">
		<div class="container">
			<div class="row">
				<div class="col-md-6">
					<h3> Sign  Up for Beta</h3>
					<form action="//formspree.io/info@myclasstracks.com" method="POST">
						<input type="text" name="name" placeholder="Your Name">
						<input type="text" name="_school" placeholder="School, School District, etc" />
						<input type="text" name="_replyto" placeholder="Your email" />
						<input type="hidden" name="_subject" value="Beta Signup" />
						<input type="submit" class="cta" value="Send">
						<input type="hidden" name="_next" value="/sign-up-confirmation.html" />
						<input type="text" name="_gotcha" style="display:none" />
					</form>
				</div>
				<div class="col-md-6">
					<h3> Send Us A Message</h3>
					<form action="//formspree.io/info@myclasstracks.com" method="POST">
						<input type="text" name="name" placeholder="Your Name">
						<input type="text" name="_school" placeholder="School, School District, etc" />
						<input type="text" name="_replyto" placeholder="Your email" />
						<input type="hidden" name="_subject" value="New submission!" />
						<textarea rows="5" name="message" placeholder="Message" id="message" required="" data-validation-required-message="Please enter a message." aria-invalid="false"></textarea>
						<input type="submit" class="cta" value="Send">
						<input type="hidden" name="_next" value="/message-confirmation.html" />
						<input type="text" name="_gotcha" style="display:none" />
					</form>
				</div>
			</div>
		</div>
	</div>
</section>
	
