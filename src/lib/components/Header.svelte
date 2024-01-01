<script>
	import logo from '$lib/assets/logo.svg';
</script>

<header class="header">
	<div class="header-wrapper">
		<a href="/" class="header-logo"
			><img class="header-logo-link" src={logo} alt="header logo" width="80px" /></a
		>
		<nav class="header-nav">
			<ul class="nav-list">
				<li class="nav-list-item"><a href="#">Features</a></li>
				<li class="nav-list-item"><a href="#">Team</a></li>
				<li class="nav-list-item"><a href="#">Sign In</a></li>
			</ul>
		</nav>
	</div>
</header>

<style>
	.header {
		padding-top: 24px;
		padding-bottom: 48px;
	}
	.header-wrapper {
		display: flex;
		justify-content: space-between;
		align-items: center;
		width: min(88.27%, 1280px);
		margin-right: auto;
		margin-left: auto;
	}
	.nav-list {
		list-style: none;
		display: flex;
		align-items: center;
		gap: 25px;
	}
	.nav-list-item a {
		color: var(--pure-white);
		text-decoration: none;
		font-size: 0.75rem;
		opacity: 0.8;
	}

	@media (768px < width <= 960px) {
		.header {
			padding-top: 73px;
			padding-bottom: 75px;
		}
		.header-logo-link {
			width: 176px;
		}
		.header-logo-link:hover {
			opacity: 0.8;
			transition: ease-in 0.15s;
		}
		.nav-list {
			gap: 57px;
		}
		.nav-list-item a {
			font-size: 1rem;
		}
		.nav-list-item a:hover {
			opacity: 1;
			cursor: pointer;
			text-decoration-line: underline;
			text-decoration-color: var(--pure-white);
			transition: ease-in 0.1s;
		}
	}

	@media (960px < width <= 1440px) {
		.header {
			padding-top: 73px;
			padding-bottom: 75px;
		}
		.header-logo-link {
			width: 176px;
		}
		.nav-list {
			gap: 57px;
		}
		.nav-list-item a {
			font-size: 1rem;
		}
		.nav-list-item a:hover {
			opacity: 1;
			cursor: pointer;
			text-decoration-line: underline;
			text-decoration-color: var(--pure-white);
			transition: ease-in 0.1s;
		}
	}
</style>
