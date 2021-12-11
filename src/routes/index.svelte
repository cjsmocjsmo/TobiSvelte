<script context="module">
	export const prerender = true;
	import pic1_1thumb from '../lib/images/thumbs/pic1_1thumb.webp';
	import pic2_1thumb from '../lib/images/thumbs/pic2_1thumb.webp';
	import pic3_1thumb from '../lib/images/thumbs/pic3_1thumb.webp';
	
	import pic5thumb from '../lib/images/thumbs/pic5thumb.webp';
	import pic7thumb from '../lib/images/thumbs/pic7thumb.webp';
	import pic8thumb from '../lib/images/thumbs/pic8thumb.webp';
	import pic9thumb from '../lib/images/thumbs/pic9thumb.webp';
	import pic10thumb from '../lib/images/thumbs/pic10thumb.webp';
	import pic12thumb from '../lib/images/thumbs/pic12thumb.webp';
	import pic4thumb from '../lib/images/thumbs/pic4thumb.webp';

	import p1thumb from '../lib/images/thumbs/p1thumb.webp';
	import p2thumb from '../lib/images/thumbs/p2thumb.webp';
	import p3thumb from '../lib/images/thumbs/p3thumb.webp';
	import p4thumb from '../lib/images/thumbs/p4thumb.webp';
	import p5thumb from '../lib/images/thumbs/p5thumb.webp';

	import p1 from '$lib/images/thumbs/FB_IMG_1thumb.webp';
	import p2 from '$lib/images/thumbs/FB_IMG_2thumb.webp';
	import p3 from '$lib/images/thumbs/FB_IMG_3thumb.webp';
	import p4 from '$lib/images/thumbs/FB_IMG_4thumb.webp';
</script>

<svelte:head>
	<title>Tobi</title>
</svelte:head>

<div class="column">
	<a href="/pic4zoom"><img src={pic4thumb} alt="fuckit"></a>
	<a href="/pic5zoom"><img src={pic5thumb} alt="fuckit"></a>
	<a href="/pic7zoom"><img src={pic7thumb} alt="fuckit"></a>
	<a href="/pic8zoom"><img src={pic8thumb} alt="fuckit"></a>
	<a href="/pic10zoom"><img src={pic10thumb} alt="fuckit"></a>
	<a href="/pic12zoom"><img src={pic12thumb} alt="fuckit"></a>
	<a href="/pic4zoom"><img src={pic4thumb} alt="fuckit"></a>
	<a href="/pic9zoom"><img src={pic9thumb} alt="fuckit"></a>
	<a href="/pic1_1zoom"><img src={pic1_1thumb} alt="fuckit"></a>
	<a href="/pic2_1zoom"><img src={pic2_1thumb} alt="fuckit"></a>
	<a href="/pic3_1zoom"><img src={pic3_1thumb} alt="fuckit"></a>
	<a href="/p1zoom"><img src={p1thumb} alt="fuckit"></a>
	<a href="/p2zoom"><img src={p2thumb} alt="fuckit"></a>
	<a href="/p3zoom"><img src={p3thumb} alt="fuckit"></a>
	<a href="/p4zoom"><img src={p4thumb} alt="fuckit"></a>
	<a href="/p5zoom"><img src={p5thumb} alt="fuckit"></a>
	<a href="/pic13zoom"><img src={p1} alt="fuckit"></a>
	<a href="/pic14zoom"><img src={p2} alt="fuckit"></a>
	<a href="/pic15zoom"><img src={p3} alt="fuckit"></a>
	<a href="/pic16zoom"><img src={p4} alt="fuckit"></a>
</div>
<a href="https://frontpage-czi.pages.dev/" ><button>Home</button></a>
<style>

	button {
        width: 25%;
		padding: 8px;
		border-radius: 7px;
		background-color: white;
		font-size: 1.25em;
		color: black;
		text-align: center;
    }

	.column {
		flex: 25%;
		padding: 0 4px;
	}

	.column img {
		margin-top: 8px;
		border-radius: 10%;
		max-width: 225px;
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
