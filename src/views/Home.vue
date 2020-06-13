<template>
	<div class="wrapper">
		<section class="left__sec">
			<h1>Jason <br> Cameron</h1>
			<h2>Front-end JavaScript Developer</h2>
			<router-link class="btn" to="/contact">CONTACT ME</router-link>
		</section>
		<!--  -->
		<section class="right__sec">
			<article>
				&lt;template&gt; <br />
				<p>&lt;h1&gt;Jason Cameron&lt;/h1&gt;</p>
				&lt;template&gt;
			</article>
		</section>
	</div>
</template>

<style lang="scss" scoped>
.left__sec {
	width: 35%;
	h1 {
		font-size: 4.5em;
		font-weight: bold;
	}

	h2 {
		font-size: 1.2em;
		margin-top: 20px;
		margin-bottom: 60px;
	}

	.btn {
		border: 2px solid #fdcb6e;
		padding: 10px 40px;
		border-radius: 5px;
		font-weight: 400;
	}
}

.right__sec {
	article {
		margin-top: 100px;
		font-size: 4em;
		opacity: 0.1;
		font-style: italic;

		p {
			margin-left: 100px;
		}
	}
}
</style>
