<script>
	let visible = "solid";
</script>

<main>


	<div class="top">	
		<div class="imag"><br></div>		
		<div class="padding"></div>
		<div class="title">
			<h1 class="title">Hi, I am <strong>Jason</strong></h1>

		</div>
		
	</div>
	<div class="container">
		<div class="topic1">
			<h2><strong class=noBlur>Game Development<strong class=noBlur/></h2>
			<!-- <div class="padding"></div> -->
		</div>
		<div class="topic2">
			<!-- <div class="padding"></div> -->
		</div>	<div class="topic3">
			<!-- <div class="padding"></div> -->
		</div>
	</div>
</main>

<style>
/* //linear-gradient(rgb(5, 5, 56),black) */
	.top{
		background-image: url('src\\resources\\31zbaa9a.bmp');
		background-size: 100%;
		border-radius: 1rem;
		padding-bottom: 6rem;
	}

	.padding{
		padding-top: 6rem;
	}



	.title {
	filter: blur(0px);
	-webkit-filter: blur(0px);

	overflow: hidden; /* Ensures the content is not revealed until the animation */
	white-space: nowrap; /* Keeps the content on a single line */
	margin: 0 auto; /* Gives that scrolling effect as the typing happens */
	letter-spacing: .15em; /* Adjust as needed */
	font-size: 2.5rem;
	text-align: center;
	/* animation: 
		typing 3.5s steps(40, end),
		blink-caret .75s step-end infinite; */
	}
	.container > div { 
		top:-50px; 
		left:-35px; 
		display:block; 
		z-index:99; 
		cursor: pointer; 
		-webkit-transition-property: all; 
		-webkit-transition-duration: 0.3s; 
		-webkit-transition-timing-function: ease; 
	} 

	/*change the number below to scale to the appropriate size*/ 
	.container > div:hover { 
		z-index:999; 
		filter:blur(0);
		transform: scale(1.2); 
	}


	/* The typing effect */
	@keyframes typing {
	from { width: 0 }
	to { width: 100% }
	}

	/* The typewriter cursor effect */
	@keyframes blink-caret {
	from, to { border-color: transparent }
	50% { border-color: orange; }
	}


	@keyframes slideInUp {
	0% {
		transform: translateY(100%);
	}
	100% {
		transform: translateY(0%);
	}
	}

	strong{

		color:rgb(11, 183, 57);

	}
	.noBlur{
		filter: blur(0px);
	}

	:global(body) {
		font-family: monospace;
		background-color: #0d161e;
		color: #bfc2c7;
	}

	.container{
		display:flex;
	}

	.topic1{
		background-image: url('C:\Programs\Programming\GitHub\portfolio-website\portfolio\src\resources\a2kh1k4i.bmp');
		background-size: 100%;
		border-radius: 1rem;
		padding-bottom: 26rem;
		background-size:cover;
		filter: blur(1rem);
		
	}
	.topic2{
		background-image: url('src\\resources\\niiqaijl.bmp');
		background-size: 100%;
		border-radius: 1rem;
		padding-bottom: 26rem;
		background-size:cover;
		filter: blur(1rem);
		
	}
	.topic3{
		background-image: url('src\\resources\\Untitled.jpeg');
		background-size: 100%;
		border-radius: 1rem;
		padding-bottom: 26rem;
		background-size:cover;
		filter: blur(1rem);
		
	}

	.container > div {
		vertical-align: top;
		background-color: #f1f1f1;
		width: 30%;
		padding-bottom: flex;
		margin: 2%;
		text-align: center;
		line-height: 57%;
		font-size: 1.75rem;
	}
</style>