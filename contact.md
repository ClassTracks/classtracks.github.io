---
layout: default
permalink: /contact/
---

<section class="contact-us">
	<div class="container-fluid hero-title">
		<div class="col-md-12">
			<header class="post-header">
				<h1 class="post-title">Beta SignUp</h1>
			</header>
		</div>
	</div>
	<div class="container-fluid form">
		<div class="container">
			<div class="row">
				<div class="col-md-6" id="override">
					<!-- http://stackoverflow.com/questions/11423682/cross-domain-form-posting -->
					<form action="https://classtracks-staging.herokuapp.com/welcome-beta-user" method="POST">
						<input type="text" name="name" placeholder="Your Name">
						<input type="text" name="_school" placeholder="School, School District, etc" />
						<input type="text" name="_replyto" placeholder="Your email" />
						<input type="hidden" name="_subject" value="Beta Signup" />
                            <input type="checkbox" name="_updates_option" id="inline-label" />Please keep me posted on improvements and new features, and other cool happenings at ClassTracks (no more than one update a month).
                      
                        <input type="submit" class="cta" value="Send">
						<!--input type="hidden" name="_next" value="/sign-up-confirmation.html" /-->
						<input type="text" name="_gotcha" style="display:none" />
					</form>
				</div>
			</div>
		</div>
	</div>
</section>

	
