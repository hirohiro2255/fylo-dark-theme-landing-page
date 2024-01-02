<script>
	import deviceIcon from '$lib/assets/icon-access-anywhere.svg';
	import securityIcon from '$lib/assets/icon-security.svg';
	import collaborationIcon from '$lib/assets/icon-collaboration.svg';
	import fileIcon from '$lib/assets/icon-any-file.svg';
</script>

<section class="middle-hero">
	<div class="middle-hero-wrapper">
		<div class="card">
			<img class="card-img" src={deviceIcon} alt="devices icon" width="80px" />
			<h2 class="card-title">Access your files, anywhere</h2>
			<p class="card-detail">
				The ability to use a smartphone, tablet, or computer to access your account means your files
				follow you everywhere.
			</p>
		</div>

		<div class="card">
			<img class="card-img" src={securityIcon} alt="devices icon" width="80px" />
			<h2 class="card-title">Security you can trust</h2>
			<p class="card-detail">
				2-factor authentication and user-controlled encryption are just a couple of the security
				features we allow to help secure your files.
			</p>
		</div>

		<div class="card">
			<img class="card-img" src={collaborationIcon} alt="collaboration icon" width="80px" />
			<h2 class="card-title">Real-time collaboration</h2>
			<p class="card-detail">
				Securely share files and folders with friends, family and colleagues for live collaboration.
				No email attachments required.
			</p>
		</div>

		<div class="card">
			<img class="card-img" src={fileIcon} alt="files icon" width="80px" />
			<h2 class="card-title">Store any type of file</h2>
			<p class="card-detail">
				Whether you're sharing holidays photos or work documents, Fylo has you covered allowing for
				all file types to be securely stored and shared.
			</p>
		</div>
	</div>
</section>

<style>
	.middle-hero {
		padding-top: 120px;
		background-color: var(--primary-dark-for-main);
	}
	.middle-hero-wrapper {
		display: grid;
		grid-template-rows: 1fr 1fr 1fr 1fr;
		row-gap: 80px;
		width: min(85.33%, 845px);
		margin-right: auto;
		margin-left: auto;
	}
	.card {
		text-align: center;
	}
	.card-img {
		width: 80px;
		height: 80px;
	}
	.card-title {
		margin-top: 24px;
		margin-bottom: 8px;
		font-size: 1.125rem;
		color: var(--pure-white);
		font-weight: 700;
		line-height: 1.33;
	}

	.card-detail {
		font-family: 'Open Sans', sans-serif;
		color: var(--pure-white);
		opacity: 0.8;
		font-size: 0.875rem;
		line-height: 1.5;
	}

	@media (768px <= width <= 1440px) {
		.card-img {
			width: 104px;
			height: 104px;
		}
		.middle-hero-wrapper {
			grid-template-columns: 1fr 1fr;
			grid-template-rows: 1fr 1fr;
			column-gap: 147px;
			row-gap: 79px;
		}
		.card-title {
			margin-top: 16px;
			margin-bottom: 9px;
		}
	}
</style>
