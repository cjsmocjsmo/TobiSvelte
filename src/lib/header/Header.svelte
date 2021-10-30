<script>
	import { page } from '$app/stores';
</script>

<header>
	<nav>
		<ul>
			<li class:active={$page.path === '/'}></li>
			<li class:active={$page.path === '/p1'}></li>
			<li class:active={$page.path === '/p2'}></li>
			<li class:active={$page.path === '/p3'}></li>
			<li class:active={$page.path === '/p4'}></li>
			<li class:active={$page.path === '/p5'}></li>
			<li class:active={$page.path === '/pic1_1'}></li>
			<li class:active={$page.path === '/pic2_1'}></li>
			<li class:active={$page.path === '/pic3_1'}></li>
			<li class:active={$page.path === '/pic4'}></li>
			<li class:active={$page.path === '/pic5'}></li>
			<li class:active={$page.path === '/pic7'}></li>
			<li class:active={$page.path === '/pic8'}></li>
			<li class:active={$page.path === '/pic9'}></li>
			<li class:active={$page.path === '/pic10'}></li>
			<li class:active={$page.path === '/pic11'}></li>
			<li class:active={$page.path === '/pic12'}></li>
			
		</ul>
	</nav>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	nav {
		display: flex;
		justify-content: center;
		--background: rgba(255, 255, 255, 0.7);
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
</style>
