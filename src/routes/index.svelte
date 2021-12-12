<script context="module">
	export const prerender = true;
	import pic1thumb from '$lib/images/thumb/20211003_131040_Thumb.webp';
	import pic2thumb from '$lib/images/thumb/20211003_131117_Thumb.webp';
	import pic3thumb from '$lib/images/thumb/20211003_135914_Thumb.webp';
	import pic4thumb from '$lib/images/thumb/20211003_131052_Thumb.webp';
	import pic5thumb from '$lib/images/thumb/20211003_131139_Thumb.webp';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>
<!-- <a href="https://frontpage-czi.pages.dev/" ><button>Back</button></a> -->
<div class="column">
	<a href="/day1zoom/pic1zoom"><img src={pic1thumb} alt="fuckit" /></a>
	<a href="/day1zoom/pic2zoom"><img src={pic2thumb} alt="fuckit" /></a>
	<a href="/day1zoom/pic3zoom"><img src={pic3thumb} alt="fuckit" /></a>
	<a href="/day1zoom/pic4zoom"><img src={pic4thumb} alt="fuckit" /></a>
	<a href="/day1zoom/pic5zoom"><img src={pic5thumb} alt="fuckit" /></a>
</div>
<a href="https://frontpage-czi.pages.dev/"><button>Home</button></a>

<style>
	button {
		width: 25%;
		padding: 8px;
		border-radius: 7px;
		background-color: white;
		font-size: 1em;
		color: black;
	}

	.column {
		flex: 25%;
		padding: 0 4px;
	}

	.column img {
		margin-top: 8px;
		border-radius: 15%;
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
