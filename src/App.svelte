<script>
		
	import Myview from './Myview.svelte';
	export let name;

</script>

<style>
	main {
		text-align: center;
		padding:1em;
		max-width: 240px;
		margin: 0 auto;
	}
	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 40px;
		font-weight:100;
	}
	@media (min-width: 640px){
		main {
			max-width: none;
		} 
	}
</style>
<main>
	<h1>Hello {name}!</h1>
	<Myview/>
</main>
