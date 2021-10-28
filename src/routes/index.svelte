<script context="module">
	export const prerender = true;
	import d2thumb from '$lib/images/thumbs/d2thumb.jpg';
	import d1thumb from '$lib/images/thumbs/d1thumb.jpg';
	import d4thumb from '$lib/images/thumbs/d4thumb.jpg';
	import d5thumb from '$lib/images/thumbs/d5thumb.jpg';
	import d6thumb from '$lib/images/thumbs/d6thumb.jpg';
	import d7thumb from '$lib/images/thumbs/d7thumb.jpg';
	import d8thumb from '$lib/images/thumbs/d8thumb.jpg';
	import d9thumb from '$lib/images/thumbs/d9thumb.jpg';
	import d10thumb from '$lib/images/thumbs/d10thumb.jpg';
</script>



<svelte:head>
	<title>Dad</title>
</svelte:head>

<div class="column">
	<a href="/d1zoom"><img src={d1thumb} alt="fuckit" ></a>
	<a href="/d2zoom"><img src={d2thumb} alt="fuckit" ></a>
	<a href="/d4zoom"><img src={d4thumb} alt="fuckit" ></a>
	<a href="/d5zoom"><img src={d5thumb} alt="fuckit" ></a>
	<a href="/d6zoom"><img src={d6thumb} alt="fuckit" ></a>
	<a href="/d7zoom"><img src={d7thumb} alt="fuckit" ></a>
	<a href="/d8zoom"><img src={d8thumb} alt="fuckit" ></a>
	<a href="/d9zoom"><img src={d9thumb} alt="fuckit" ></a>
	<a href="/d10zoom"><img src={d10thumb} alt="fuckit" ></a>
</div>

<style>
	.column {
		flex: 25%;
		padding: 0 4px;
	}

	.column img {
		margin-top: 8px;
	}

	@media screen and (max-width: 420px) {
		img {
			width: 120px;
		}
	}

	@media screen and (max-width: 360px) {
		img {
			width: 100px;
		}
	}
</style>

