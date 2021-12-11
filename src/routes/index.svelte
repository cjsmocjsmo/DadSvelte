<script context="module">
	export const prerender = true;

	import d1thumbwebp from '$lib/images/thumbs/d1thumb2.webp';
	import d2thumbwebp from '$lib/images/thumbs/d2thumb2.webp';
	import d4thumbwebp from '$lib/images/thumbs/d4thumb2.webp';
	import d5thumbwebp from '$lib/images/thumbs/d5thumb2.webp';
	import d6thumbwebp from '$lib/images/thumbs/d6thumb2.webp';
	import d7thumbwebp from '$lib/images/thumbs/d7thumb2.webp';
	import d8thumbwebp from '$lib/images/thumbs/d8thumb2.webp';
	import d9thumbwebp from '$lib/images/thumbs/d9thumb2.webp';
	import d10thumbwebp from '$lib/images/thumbs/d10thumb2.webp';

</script>



<svelte:head>
	<title>Dad</title>
</svelte:head>

<a href="https://frontpage-czi.pages.dev/" ><button>Back</button></a>
<div class="column">
	<a href="/d1zoom"><img src={d1thumbwebp} alt="fuckit" ></a>
	<a href="/d2zoom"><img src={d2thumbwebp} alt="fuckit" ></a>	
	<a href="/d4zoom"><img src={d4thumbwebp} alt="fuckit" ></a>
	<a href="/d5zoom"><img src={d5thumbwebp} alt="fuckit" ></a>
	<a href="/d6zoom"><img src={d6thumbwebp} alt="fuckit" ></a>
	<a href="/d7zoom"><img src={d7thumbwebp} alt="fuckit" ></a>
	<a href="/d8zoom"><img src={d8thumbwebp} alt="fuckit" ></a>
	<a href="/d9zoom"><img src={d9thumbwebp} alt="fuckit" ></a>
	<a href="/d10zoom"><img src={d10thumbwebp} alt="fuckit" ></a>
</div>
<a href="https://frontpage-czi.pages.dev/" ><button>Back</button></a>

<style>

	button {
        width: 25%;
		padding: 8px;
		border-radius: 7px;
		background-color: white;
		font-size: 1.25em;
		color: black;
    }


	.column {
		flex: 25%;
		padding: 0 4px;
	}

	.column img {
		margin-top: 8px;
		border-radius: 10%;
	}
	/* @media screen and (max-width: 400px) {
		img {
			width: 200px;
		}
	} */

	@media screen and (max-width: 420px) {
		img {
			width: 175px;
		}
	}

	@media screen and (max-width: 360px) {
		img {
			width: 100px;
		}
	}
</style>

