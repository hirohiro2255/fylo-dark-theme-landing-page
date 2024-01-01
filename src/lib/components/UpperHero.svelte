<script>
	import heroImg from '$lib/assets/illustration-intro.png';
</script>

<section class="upper-hero">
	<div class="hero-wrapper">
		<img src={heroImg} alt="hero" class="hero-image" width="100%" />
		<div class="hero-detail">
			<h1 class="hero-title">All your files in one secure location, accessible anywhere.</h1>
			<p class="hero-paragraph">
				Fylo stores all your most important files in one secure location. Access them wherever you
				need, share and collaborate with friends family, and co-workers.
			</p>
			<a href="/" class="hero-button">Get Started</a>
		</div>
	</div>
</section>

<style>
	.upper-hero {
		background-image: url('$lib/assets/bg-curvy-mobile.svg');
		background-size: cover;
		background-repeat: no-repeat;
		background-position: 50% 50%;
	}
	.hero-wrapper {
		width: min(81.07%, 720px);
		margin-right: auto;
		margin-left: auto;
	}
	.hero-detail {
		text-align: center;
		padding-top: 33px;
		padding-bottom: 120px;
	}
	.hero-title {
		font-size: 1.3rem;
		color: var(--pure-white);
		font-weight: 700;
		line-height: 1.5;
	}
	.hero-paragraph {
		opacity: 0.8;
		font-size: 0.875rem;
		color: var(--pure-white);
		font-family: 'Open Sans', sans-serif;
		line-height: 1.5;
		padding-top: 15px;
		padding-bottom: 32px;
	}
	.hero-button {
		display: inline-block;
		padding-top: 16px;
		padding-bottom: 16px;
		background: linear-gradient(135deg, #63e1d9 -42.11%, #34a0cd 100%);
		filter: drop-shadow(2px 3px 6px rgba(0, 0, 0, 0.16));
		color: var(--pure-white);
		width: min(82.2%, 280px);
		font-size: 0.875rem;
		font-weight: 700;
		text-decoration: none;
		border-radius: 24px;
	}
	.hero-button:hover {
		background: hsla(186, 62%, 72%, 1);
	}
</style>
