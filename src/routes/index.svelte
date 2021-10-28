<script context="module">
	export const prerender = true;
	import pic1_1thumb from '../lib/images/thumbs/pic1_1thumb.jpg';
	import pic2_1thumb from '../lib/images/thumbs/pic2_1thumb.jpg';
	import pic3_1thumb from '../lib/images/thumbs/pic3_1thumb.jpg';
	
	import pic5thumb from '../lib/images/thumbs/pic5thumb.jpg';
	import pic7thumb from '../lib/images/thumbs/pic7thumb.jpg';
	import pic8thumb from '../lib/images/thumbs/pic8thumb.jpg';
	import pic9thumb from '../lib/images/thumbs/pic9thumb.jpg';
	import pic10thumb from '../lib/images/thumbs/pic10thumb.jpg';
	import pic12thumb from '../lib/images/thumbs/pic12thumb.jpg';
	import pic14thumb from '../lib/images/thumbs/pic4thumb.jpg';

	import p1thumb from '../lib/images/thumbs/p1thumb.jpg';
	import p2thumb from '../lib/images/thumbs/p2thumb.jpg';
	import p3thumb from '../lib/images/thumbs/p3thumb.jpg';
	import p4thumb from '../lib/images/thumbs/p4thumb.jpg';
	import p5thumb from '../lib/images/thumbs/p5thumb.jpg';
</script>



<svelte:head>
	<title>Tobi</title>
</svelte:head>

<div class="column">
	<a href="/pic1_1zoom"><img src={pic1_1thumb} alt="fuckit"></a>
	<a href="/pic2_1zoom"><img src={pic2_1thumb} alt="fuckit"></a>
	<a href="/pic3_1zoom"><img src={pic3_1thumb} alt="fuckit"></a>

	<a href="/p1zoom"><img src={p1thumb} alt="fuckit"></a>
	<a href="/p2zoom"><img src={p2thumb} alt="fuckit"></a>
	<a href="/p3zoom"><img src={p3thumb} alt="fuckit"></a>
	<a href="/p4zoom"><img src={p4thumb} alt="fuckit"></a>
	<a href="/p5zoom"><img src={p5thumb} alt="fuckit"></a>
</div>
<div class="column">
	<a href="/pic5zoom"><img src={pic5thumb} alt="fuckit"></a>
	<a href="/pic7zoom"><img src={pic7thumb} alt="fuckit"></a>
	<a href="/pic8zoom"><img src={pic8thumb} alt="fuckit"></a>
	<a href="/pic10zoom"><img src={pic10thumb} alt="fuckit"></a>
	<a href="/pic12zoom"><img src={pic12thumb} alt="fuckit"></a>
	<a href="/pic14zoom"><img src={pic14thumb} alt="fuckit"></a>
	<a href="/pic9zoom"><img src={pic9thumb} alt="fuckit"></a>
</div>

<style>
	.column {
		flex: 25%;
		padding: 0 4px;
	}

	.column img {
		margin-top: 8px;
		max-width: 250px;
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
