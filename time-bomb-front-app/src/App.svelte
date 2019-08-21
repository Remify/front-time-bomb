<script>
	import Login from './login/Login.svelte';
	import Nav from './Nav.svelte';

	export let name;
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}!</h1>

<Nav />
<Login />