<script>
</script>

<section>
	<div>
		<h3>We serve great meals</h3>
		<h1>Cuisine vit ici</h1>
		<button class="btn btn-outline-primary">Book a table</button>
	</div>
</section>

<style>
	section{
		background-image: url(/1.jpg);
		background-size: cover;
		background-position: center;
		height: 100vh;
		display: flex;
		justify-content: center;
		align-items: center;
		color: #fff;
		text-align: center;
	}
	h1{
		font-size: 200px;
		font-family: Great Vibes;
		font-style: italic;
		font-weight: 500;
	}
	h1::after{
		content: "";
    width: 30%;
    display: block;
    background-color: #fff;
    height: 5px;
    margin: 0 auto;
	}
	h3{
		text-transform: uppercase;
		font-weight: 700;
	}
	button{
		margin-top: 100px;
		font-size: 14px;
	  font-style: normal;
	  font-weight: 500;
	  line-height: 1.5em;
	  text-transform: uppercase;
	  letter-spacing: .03em;
	  position: relative;
	  padding: 16px 52px;
	  border-radius: 0;
		color: #fff;
		border-color: #fff;
		z-index: 2;
	}
	button::before{
		content: "";
		background-color: #fff;
		position: absolute;
		top: 0;
		left: 0;
		right: 0;
		bottom: 0;
		z-index: -1;
		width: 0;
		transition: width .6s;
	}

	button:hover,
	button:focus{
		background-color: transparent;
		border-color: #fff;
		color: #000;
	}

	button:hover::before{
		width: 204.3px;
	}
</style>
