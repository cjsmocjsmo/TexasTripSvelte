<script context="module">
    export const prerender = true;
    import p1 from '$lib/images/thumb/20211010_132048_Thumb.jpg';
    // 20211010_132048-2.jpg
    import p2 from '$lib/images/thumb/20211010_133144_HDR_Thumb.jpg';
    // 20211010_133144_HDR2.jpg
    import p3 from '$lib/images/thumb/20211010_133147_HDR_Thumb.jpg';
    // 20211010_133147_HDR2.jpg
    import p4 from '$lib/images/thumb/20211010_133151_HDR_Thumb.jpg';
    // 20211010_133151_HDR2.jpg
    import p5 from '$lib/images/thumb/20211010_133407_HDR_Thumb.jpg';
    // 20211010_133407_HDR2.jpg
    import p6 from '$lib/images/thumb/20211010_133420_HDR_Thumb.jpg';
    // 20211010_133420_HDR2.jpg
    import p7 from '$lib/images/thumb/20211010_133427_HDR_Thumb.jpg';
    // 20211010_133427_HDR2.jpg
    import p8 from '$lib/images/thumb/20211010_133432_HDR_Thumb.jpg';
    // 20211010_133432_HDR2.jpg


    import p9 from '$lib/images/thumb/20211010_134023_HDR_Thumb.jpg';
    // 20211010_134023_HDR2.jpg
    import p10 from '$lib/images/thumb/20211010_134028_HDR_Thumb.jpg';
    // 20211010_134028_HDR2.jpg
    import p11 from '$lib/images/thumb/20211010_134037_HDR_Thumb.jpg';
    // 20211010_134037_HDR2.jpg
    import p12 from '$lib/images/thumb/20211010_134950_Thumb.jpg';
    // 20211010_134950-2.jpg
    import p13 from '$lib/images/thumb/20211010_134954_HDR_Thumb.jpg';
    // 20211010_134954_HDR2.jpg
    import p14 from '$lib/images/thumb/20211010_134959_HDR_Thumb.jpg';
    // 20211010_134959_HDR2.jpg
    import p15 from '$lib/images/thumb/20211010_141105_HDR_Thumb.jpg';
    // 20211010_141105_HDR2.jpg
    import p16 from '$lib/images/thumb/20211010_141107_HDR_Thumb.jpg';
    // 20211010_141107_HDR2.jpg



    import p17 from '$lib/images/thumb/20211010_141549_HDR_Thumb.jpg';
    // 20211010_141549_HDR2.jpg
    import p18 from '$lib/images/thumb/20211010_141553_HDR_Thumb.jpg';
    // 20211010_141553_HDR2.jpg
    import p19 from '$lib/images/thumb/20211010_141555_HDR_Thumb.jpg';
    // 20211010_141555_HDR2.jpg
    import p20 from '$lib/images/thumb/20211010_141600_HDR_Thumb.jpg';
    // 20211010_141600_HDR2.jpg
    import p21 from '$lib/images/thumb/20211010_144813_Burst01_Thumb.jpg';
    // 20211010_144813_Burst01-2.jpg
    import p22 from '$lib/images/thumb/20211010_164841_Thumb.jpg';
    // 20211010_164841-2.jpg
    import p23 from '$lib/images/thumb/20211010_164844_Thumb.jpg';
    // 20211010_164844-2.jpg
</script>

<div class="column">
    <img src={ p1 } alt="fuckit">
    <img src={ p2 } alt="fuckit">
    <img src={ p3 } alt="fuckit">
    <img src={ p4 } alt="fuckit">
    <img src={ p5 } alt="fuckit">
    <img src={ p9 } alt="fuckit">
    <img src={ p10 } alt="fuckit">
    <img src={ p11 } alt="fuckit">
    <img src={ p12 } alt="fuckit">
    <img src={ p13 } alt="fuckit">
    <img src={ p14 } alt="fuckit">
    <img src={ p15 } alt="fuckit">
    <img src={ p16 } alt="fuckit">
    <img src={ p17 } alt="fuckit">
    <img src={ p18 } alt="fuckit">
    <img src={ p19 } alt="fuckit">
    <img src={ p20 } alt="fuckit">
    <img src={ p21 } alt="fuckit">
</div>
<div>
    <img src={ p6 } alt="fuckit">
    <img src={ p7 } alt="fuckit">
    <img src={ p8 } alt="fuckit">
    <img src={ p22 } alt="fuckit">
    <img src={ p23 } alt="fuckit">
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
