<template>
	<header>
		<h1 class="logo">J</h1>
		<nav>
			<ul class="nav__links">
				<li>
					<router-link to="/">Home</router-link>
				</li>
				<li>
					<router-link to="/about">About</router-link>
				</li>
				<li>
					<router-link to="/skills">Skills</router-link>
				</li>
				<li>
					<router-link to="/projects">Projects</router-link>
				</li>
				<li>
					<router-link to="/contact">Contact</router-link>
				</li>
			</ul>
		</nav>

		<ul class="social__links">
			<li>
				<a href="https://www.linkedin.com/in/jason-cameron-762907107/">
					<i class="fab fa-linkedin fa-2x"></i>
				</a>
			</li>
			<li>
				<a href="https://twitter.com/JasonKioCameron">
					<i class="fab fa-twitter-square fa-2x"></i>
				</a>
			</li>
			<li>
				<a href="https://github.com/kiocam">
					<i class="fab fa-github-square fa-2x"></i>
				</a>
			</li>
		</ul>
	</header>
</template>

<script>
export default {
	name: 'Header',
};
</script>

<style lang="scss" scoped>
@import url('https://fonts.googleapis.com/css2?family=Sriracha&display=swap');

header {
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding: 30px 10%;
}

.logo {
	cursor: pointer;
	font-family: 'Sriracha', cursive;
	font-size: 4em;
}

.nav__links,
.social__links {
	list-style: none;
	li {
		display: inline-block;
		padding: 0px 20px;
	}
	a {
		text-decoration: none;
		color: #fff;
	}
}
</style>
