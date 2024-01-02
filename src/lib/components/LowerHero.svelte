<script>
	import lowerHeroImg from '$lib/assets/illustration-stay-productive.png';
	import arrowIcon from '$lib/assets/icon-arrow.svg';
</script>

<section class="lower-hero">
	<div class="lower-hero-wrapper">
		<img src={lowerHeroImg} alt="hero icon at the bottom" class="lower-hero-img" />
		<div class="lower-hero-detail">
			<h2 class="lower-hero-heading">Stay productive, wherever you are</h2>
			<p class="lower-hero-paragraph">
				Never let location be an issue when accessing your files. Fylo has you covered for all of
				your file storage needs.
			</p>
			<p class="lower-hero-paragraph">
				Securely share files and folders with friends, family and colleagues for live collaboration.
				No email attachments required.
			</p>
			<div class="lower-hero-button-group">
				<a href="/" class="lower-hero-button"
					>See how Fylo works<img src={arrowIcon} alt="arrow icon" /></a
				>
			</div>
		</div>
	</div>
</section>

<style>
	.lower-hero {
		background-color: var(--primary-dark-for-main);
		padding-top: 160px;
	}
	.lower-hero-wrapper {
		display: flex;
		flex-direction: column;
		gap: 48px;
		width: min(85.33%, 1235px);
		margin-right: auto;
		margin-left: auto;
	}
	.lower-hero-img {
		width: min(100%, 614px);
	}
	.lower-hero-detail {
		display: flex;
		flex-direction: column;
		gap: 16px;
	}
	.lower-hero-heading {
		font-size: 1.125rem;
		color: var(--pure-white);
		text-align: center;
		line-height: 1.5;
	}
	.lower-hero-paragraph {
		color: var(--pure-white);
		font-size: 0.875rem;
		opacity: 0.8;
		line-height: 1.5;
	}
	.lower-hero-button {
		text-decoration: none;
		border-bottom: 1px solid var(--accent-cyan);
		color: var(--accent-cyan);
		padding-bottom: 5px;
	}
	.lower-hero-button:hover {
		-webkit-filter: brightness(0) invert(1);
		filter: brightness(0) invert(1);
	}
</style>
