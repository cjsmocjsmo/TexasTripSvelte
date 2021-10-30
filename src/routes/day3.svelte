<script context="module">
    export const prerender = true;
    import pic1 from '$lib/images/20211007/thumbs/20211006_162736-2thumb.jpg';
    import pic2 from '$lib/images/20211007/thumbs/20211007_113327-2thumb.jpg';
    import pic3 from '$lib/images/20211007/thumbs/20211007_133940_HDR-2thumb.jpg';
    import pic4 from '$lib/images/20211007/thumbs/20211007_133940_HDR-2thumb.jpg';
    import pic5 from '$lib/images/20211007/thumbs/20211006_163035-2thumb.jpg';
    import pic6 from '$lib/images/20211007/thumbs/20211007_133750_HDR-2ghumb.jpg';
    import pic7 from '$lib/images/20211007/thumbs/20211007_133941_HDR-2thumb.jpg';
    import pic8 from '$lib/images/20211007/thumbs/20211007_113302-2thumb.jpg';
    import pic9 from '$lib/images/20211007/thumbs/20211007_133819-2thumb.jpg';
    import pic10 from '$lib/images/20211007/thumbs/20211007_140506_HDR-2thumb.jpg';
    import pic11 from '$lib/images/20211007/thumbs/20211007_113316-2thumb.jpg';
    import pic12 from '$lib/images/20211007/thumbs/20211007_133926_HDR-2thumb.jpg';
    import pic13 from '$lib/images/20211007/thumbs/20211007_113321-2thumb.jpg';
    import pic14 from '$lib/images/20211007/thumbs/20211007_133933_HDR-2thumb.jpg';

</script>

<div class="column">
    <a href="/day3zoom/pic1zoom"><img src={pic1} alt="fuckit"></a>
    <a href="/day3zoom/pic2zoom"><img src={pic2} alt="fuckit"></a>
    <a href="/day3zoom/pic5zoom"><img src={pic5} alt="fuckit"></a>
    <a href="/day3zoom/pic8zoom"><img src={pic8} alt="fuckit"></a>
    <a href="/day3zoom/pic10zoom"><img src={pic10} alt="fuckit"></a>
    <a href="/day3zoom/pic11zoom"><img src={pic11} alt="fuckit"></a>
    <a href="/day3zoom/pic13zoom"><img src={pic13} alt="fuckit"></a>
</div>
<div >
    <a href="/day3zoom/pic3zoom"><img src={pic3} alt="fuckit"></a>
    <a href="/day3zoom/pic4zoom"><img src={pic4} alt="fuckit"></a>
    <a href="/day3zoom/pic6zoom"><img src={pic6} alt="fuckit"></a>
    <a href="/day3zoom/pic7zoom"><img src={pic7} alt="fuckit"></a>
    <a href="/day3zoom/pic9zoom"><img src={pic9} alt="fuckit"></a>
    <a href="/day3zoom/pic12zoom"><img src={pic12} alt="fuckit"></a>
    <a href="/day3zoom/pic14zoom"><img src={pic14} alt="fuckit"></a>
</div>


<style>
	.column {
		flex: 25%;
		padding: 0 4px;
	}

	.column img {
		margin-top: 8px;
	}

    img {
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
