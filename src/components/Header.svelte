<script>
	import logo from '$lib/assets/logo.svg';
</script>

<header class="header">
	<div class="header-wrapper">
		<a href="/" class="header-link"><img src={logo} alt="header logo" width="80px" /></a>
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
	.header-wrapper {
		display: flex;
		justify-content: space-between;
		padding-top: 24px;
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
</style>
