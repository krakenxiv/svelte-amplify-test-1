<script lang="ts">
	import '../app.css';

	let count = $state(0);

	const onclickPlus = () => {
		count = count + 1;
	};

	const onclickMinus = () => {
		count = count - 1;
	};
</script>

<section>
	<h1>Super basic Svelte - Amplify test</h1>
	<p>
		{count}
	</p>
	<button onclick={onclickPlus}>+</button>
	<button onclick={onclickMinus}>-</button>
</section>

<style>
	section {
		text-align: center;
	}

	p {
		font-size: 20px;
		margin: 4em 20em;
		padding: 2em;
		border: 1px solid #555;
	}

	button {
		background: #222;
		border: 1px solid #555;
		border-radius: 6px;
		color: #ccc;
		padding: 1em 2em;
		margin: 2em;
	}
</style>
