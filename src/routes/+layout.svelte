<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<div class="layout">
	<header>
		<h1>Super basic Svelte - Amplify test</h1>
	</header>
	<nav class="menu">
		<ul>
			<li>
				<a href="/">Home</a>
			</li>
			<li>
				<a href="/about">About</a>
			</li>
			<li>
				<a href="/services">Services</a>
			</li>
		</ul>
	</nav>
	<section>
		{@render children()}
	</section>
	<footer>Footer</footer>
</div>
