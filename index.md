
<!DOCTYPE HTML>

<html>
	<head>
		<title>Ethereal by HTML5 UP</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
		<link rel="stylesheet" href="assets/css/main.css" />z
		<script
  src="https://code.jquery.com/jquery-3.4.0.min.js"
  integrity="sha256-BJeo0qm959uMBGb65z40ejJYGSgR7REI4+CW1fNKwOg="
  crossorigin="anonymous"></script>
		<script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.9"></script>
		<noscript><link rel="stylesheet" href="assets/css/noscript.css" /></noscript>
		<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery.terminal/2.4.1/js/jquery.terminal.min.js"></script>
		<link href="https://cdnjs.cloudflare.com/ajax/libs/jquery.terminal/2.4.1/css/jquery.terminal.min.css" rel="stylesheet"/>
		<script type="text/javascript" src="https://cdn.rawgit.com/inorganik/countUp.js/master/countUp.min.js"></script>
	</head>

	<body class="is-preload">

		<!-- Page Wrapper <span id="typed"></span> -->
			<div id="page-wrapper">

				<!-- Wrapper -->
					<div id="wrapper">

						<!-- Panel (Banner) -->
							<section class="panel banner right">
								<div class="content color0 span-7">
									<h1 class="major"><span id="typed"></span></h1>
									<span id = "typed2"></span>
									<ul class="actions">
										<li><a href="#first" id = "firstButton" class="button primary color1 circle icon fa-angle-right">Next</a></li>
									</ul>
								</div>
								<!--
								<div class="image filtered span-1-75" data-position="25% 25%">
									<img src="images/pic01.jpg" alt="" />
								</div>
							-->
							</section>

						<!-- Panel (Spotlight) -->
							<section class="panel banner color1 large left" id="first">
								<div class="content">
									<h1 class="major">The numbers</h1>
									<p> We've spent <strong>a lot</strong> of time together...</p>
									<ul class="actions">
										<li><a href="#second" id = "secondButton" class="button primary color1 circle icon fa-angle-right">Next</a></li>
									</ul>
								</div>
								<div class="content">
									<h3><strong>Over the past <span id="number" class="counter" data-count="2">0</span> years, <br>
										 we've had <span id="number" class="counter" data-count="6">0</span> classes together. <br>
										 At <span id="number" class="counter" data-count="50">0</span> minutes a class, <br>
										 <br>
										 That's </strong> <span id="number" class="counter" data-count="108000">0</span> minutes, <br>
										 <span id="number" class="counter" data-count="6480000">0</span> seconds,<br>
										 <span id="number" class="counter" data-count="1800">0</span> hours,<br>
										 and <span id="number" class="counter" data-count="75">0</span> days.</h3>

										 <br>
										 <br>

										 <h2><span id = "typed3"></span></h2>

								</div>
							</section>

						<!-- Panel -->
							<section class="panel banner color2 right" id ="second">
								<div class="content">
									<h1 class="major">Dancing</h1>
									<p> I know you're <strong>better at dancing</strong> than I am...
									<h2><span id = "typed4"></span></h2></p>
									<ul class="actions">
										<li><a href="#terminal" class="button primary color1 circle icon fa-angle-right">Next</a></li>
									</ul>
								</div>
								<div class="image span-2" data-position="0% 50%">
									<img src="images/Medal.png" alt="">
								</div>
							</section>

						<!-- Panel -->
							<section class="panel banner color0" id="terminal">

								<div class="intro joined">
									<h2 class="major">The Big Question</h2>
									<p>Got a password?</p>
								</div>
								<div class="inner columns divided">
									<div class="span-3-25">
										<form method="post" action="#">
											<div class="fields">
												<div class="field">
													<textarea name="message" id="message" rows="1">password:</textarea>
												</div>
											</div>
											<ul class="actions">
												<li><input id= "pswd"value="ENTER" class="button primary" /></li>
												<li><a href="#q" class="button primary color1 circle icon fa-angle-right">Next</a></li>
											</ul>
											<h2><span id = "typed5"></span></h2></p>
										</form>
									</div>
							</section>

							<section class="panel banner color1 medium" id="q" style="display:none;">

								<div class="intro joined">
									<h1 class="major">Karina Yang,<br>Will you go to prom with me?</h1>
									<p>-Dev</p>
								</div>
								<div class="inner columns divided">
									<div class="span-1">
										<form method="post" action="#">
											<ul class="actions stacked">
												<li><input id= "yes_button" value="YES" class="button primary" /></li>
												<li><input id= "no" value="NO" class="button primary" /></li>
												<li><a href="#Y" id="ynext" class="button primary color1 circle icon fa-angle-right" style="display:none">Next</a></li>
											</ul>
										</form>
									</div>
							</section>

							<section class="panel banner color0 medium" id="Y" style="display:none;">

								<div class="intro joined">
									<h1 class="major"><span id="typed6"></span></h1>
								</div>
							</section>

						<!-- Copyright -->
							<div class="copyright">&copy; Untitled. Design: <a href="https://html5up.net">HTML5 UP</a>.</div>

					</div>

			</div>

		<!-- Scripts -->
			<script src="assets/js/browser.min.js"></script>
			<script src="assets/js/breakpoints.min.js"></script>
			<script src="assets/js/main.js"></script>

			<script>
				var typed = new Typed('#typed', {
			    strings: ['<strong>Hey Ravdeep,^800 I have </strong>something to ask you^200...'],
			    typeSpeed: 30,
			    backSpeed: 40,
					startDelay:1000,
			    smartBackspace: true,
					fadeOut: true,
					onComplete: function(){
						var typed2 = 	new Typed('#typed2', {
						strings: ["But you're so special to me,^500 I couldn't decide on just <strong>one way</strong>"],
						typeSpeed: 30,
						backSpeed: 40,
						startDelay:1000,
						smartBackspace: true,
						showCursor:false // this is a default
						//loop: true
						});
			  	} // this is a default
			    //loop: true
			  });
				var typed3 = 	new Typed('#typed3', {
				strings: ["<strong>What's another</strong> 1 evening<strong>?</strong>", "<strong>What's another</strong> 12 hours<strong>?</strong>", "<strong>What's another</strong> 720 minutes<strong>?</strong>", "<strong>What's another</strong> 43200 seconds<strong>?</strong>"],
				typeSpeed: 30,
				backSpeed: 40,
				startDelay:500,
				smartBackspace: true, // this is a default
				loop: true,
				showCursor:false
				});
				var typed4 = new Typed('#typed4', {
			    strings: ['But maybe I can sweep you off your feet this time?'],
			    typeSpeed: 30,
			    backSpeed: 40,
					startDelay:5000,
			    smartBackspace: true,
					fadeOut: true,
					onComplete: function(){
			  	} // this is a default
			    //loop: true
			  });
				var typed5 = new Typed('#typed5', {
			    strings: ['ACCESS GRANTED'],
			    typeSpeed: 30,
			    backSpeed: 40,
					startDelay:1000,
			    smartBackspace: true,
					fadeOut: true,
					showCursor:false,
					onComplete: function(){
						$('#q').show();

						//console.log('Hello');
			  	} // this is a default
			    //loop: true

			  });

				var typed6 = new Typed('#typed6', {
			    strings: ['See ya then ;)'],
			    typeSpeed: 30,
			    backSpeed: 40,
					startDelay:20000,
			    smartBackspace: true,
					fadeOut: true,
					showCursor:false,
					onComplete: function(){
						//console.log('Hello');
			  	} // this is a default
			    //loop: true

			  });

				typed3.stop();
				typed4.stop();
				typed5.stop();
				typed6.stop();
			</script>

			<script>



			jQuery(function($, undefined) {
				$("q").hide();
	$('#message').terminal(function(command) {
			if (command !== '') {
					try {
							var result = window.eval(command);
							console.log(result)
							if (result !== undefined) {
									this.echo(new String(result));
							}
					} catch(e) {
							this.error(new String(e));
					}
			} else {
				 this.echo('');
			}
	}, {
			greetings: 'JavaScript Interpreter',
			name: 'js_demo',
			height: 200,
			prompt: 'js> '
	});
	$('#firstButton').click(
		function()
		{
			console.log("hello");
			$('.counter').each(function()
			 {
				var $this = $(this),
					countTo = $this.attr('data-count');

					$({ countNum: $this.text()}).delay(1000).animate({
						countNum: countTo
						},

						{

						duration: 5000,
						easing:'linear',
						step: function() {
							$this.text(Math.floor(this.countNum));
						},
						complete: function() {
							$this.text(this.countNum);
							typed3.start();
							//alert('finished');
						}
					});
				});
			});

			$('#secondButton').click(
				function()
				{typed4.start();});

			$('#pswd').click(
				function()
				{
					if($('#message').val() == "password:karinaboo")
					{
						typed5.start();
					}
				});

			$('#yes_button').click(
				function()
				{
					$('#Y').show();
					$('#ynext').show();
				});

			$('#ynext').click(
				function()
				{
					typed6.start();
				});
});
			</script>

	</body>
</html>
