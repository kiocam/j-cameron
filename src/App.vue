<template>
	<div id="app">
		<Header />
		<router-view />
	</div>
</template>

<script>
import Header from '@/components/Header';

export default {
	name: 'App',
	components: {
		Header,
	},
};
</script>

<style lang="scss">
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	color: #fff;
	background-color: #2d3436;
	min-height: 100vh;

	a {
		text-decoration: none;
		color: #fff;
	}

	.wrapper {
		display: flex;
		margin-top: 150px;
		padding: 0px 100px;
		//flex-wrap: wrap;
	}
}
</style>
