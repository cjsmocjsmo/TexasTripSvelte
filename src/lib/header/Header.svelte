<script>
	import { page } from '$app/stores';
	// import logo from './svelte-logo.svg';
</script>

<header>
	<div class="corner">
		<!-- <a href="https://kit.svelte.dev">
			<img src={logo} alt="SvelteKit" />
		</a> -->
	</div>

	<nav>
		<svg viewBox="0 0 2 3" aria-hidden="true">
			<path d="M0,0 L1,2 C1.5,3 1.5,3 2,3 L2,0 Z" />
		</svg>
		<ul>
			<li class:active={$page.path === '/'}><a sveltekit:prefetch href="/">D1</a></li>
			<li class:active={$page.path === '/day2'}><a sveltekit:prefetch href="/day2">D2</a></li>
			<li class:active={$page.path === '/day3'}><a sveltekit:prefetch href="/day3">D3</a></li>
			<li class:active={$page.path === '/day4'}><a sveltekit:prefetch href="/day4">D4</a></li>
			<li class:active={$page.path === '/day5'}><a sveltekit:prefetch href="/day5">D5</a></li>

			<li class:active={$page.path === '/day1zoom/pic1zoom'}></li>
			<li class:active={$page.path === '/day1zoom/pic2zoom'}></li>
			<li class:active={$page.path === '/day1zoom/pic3zoom'}></li>
			<li class:active={$page.path === '/day1zoom/pic4zoom'}></li>
			<li class:active={$page.path === '/day1zoom/pic5zoom'}></li>

			<li class:active={$page.path === '/day2zoom/p1zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p2zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p3zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p4zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p5zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p6zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p7zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p2zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p8zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p9zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p10zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p11zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p12zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p13zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p14zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p15zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p16zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p17zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p18zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p19zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p20zoom'}></li>
			<li class:active={$page.path === '/day2zoom/p21zoom'}></li>

			<li class:active={$page.path === '/day3zoom/pic1zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic2zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic3zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic4zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic5zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic6zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic7zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic8zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic10zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic11zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic12zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic13zoom'}></li>
			<li class:active={$page.path === '/day3zoom/pic14zoom'}></li>

			<li class:active={$page.path === '/day4zoom/p1zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p2zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p3zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p4zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p5zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p6zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p7zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p2zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p8zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p9zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p10zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p11zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p12zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p13zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p14zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p15zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p16zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p17zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p18zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p19zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p20zoom'}></li>
			<li class:active={$page.path === '/day4zoom/p21zoom'}></li>



			<li class:active={$page.path === '/day5zoom/p1zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p2zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p3zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p4zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p5zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p6zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p7zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p2zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p8zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p9zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p10zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p11zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p12zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p13zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p14zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p15zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p16zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p17zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p18zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p19zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p20zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p21zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p22zoom'}></li>
			<li class:active={$page.path === '/day5zoom/p23zoom'}></li>


		</ul>
		<svg viewBox="0 0 2 3" aria-hidden="true">
			<path d="M0,0 L0,3 C0.5,3 0.5,3 1,2 L2,0 Z" />
		</svg>
	</nav>

	<div class="corner">
		<!-- TODO put something else here? github link? -->
	</div>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	.corner {
		width: 3em;
		height: 3em;
	}

	/* .corner a {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
	}

	.corner img {
		width: 2em;
		height: 2em;
		object-fit: contain;
	} */

	nav {
		display: flex;
		justify-content: center;
		--background: rgba(255, 255, 255, 0.7);
	}

	svg {
		width: 2em;
		height: 3em;
		display: block;
	}

	path {
		fill: var(--background);
	}

	ul {
		position: relative;
		padding: 0;
		margin: 0;
		height: 3em;
		display: flex;
		justify-content: center;
		align-items: center;
		list-style: none;
		background: var(--background);
		background-size: contain;
	}

	li {
		position: relative;
		height: 100%;
	}

	li.active::before {
		--size: 6px;
		content: '';
		width: 0;
		height: 0;
		position: absolute;
		top: 0;
		left: calc(50% - var(--size));
		border: var(--size) solid transparent;
		border-top: var(--size) solid var(--accent-color);
	}

	nav a {
		display: flex;
		height: 100%;
		align-items: center;
		padding: 0 1em;
		color: var(--heading-color);
		font-weight: 700;
		font-size: 0.8rem;
		text-transform: uppercase;
		letter-spacing: 0.1em;
		text-decoration: none;
		transition: color 0.2s linear;
	}

	a:hover {
		color: var(--accent-color);
	}
</style>
