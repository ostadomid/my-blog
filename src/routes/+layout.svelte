<nav>
	<ul>
		<li><a href="/">Home</a></li>
		<li><a href="/about">Who am I</a></li>
	</ul>
</nav>
<slot />

<style>
	nav {
		width: 100%;
		background-color: antiquewhite;
	}
	ul {
		list-style: none;
		display: flex;
		gap: 5px;
	}
	a {
		text-decoration: none;
	}
</style>
