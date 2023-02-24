<script>
import AppTitle from "./AppTitle.vue";

export default {
	components: {
		AppTitle,
	},
};
</script>

<template>
	<!-- HTML -->
	<div class="jumbotron p-5">
		<div class="container-fluid py-5 text-center">
			<h1 class="display-5 fw-bold">
				<AppTitle></AppTitle><br />
				<h2 class="fw-bold">Con BOOSTRAP!</h2>
			</h1>
			<p class="fs-4 text-center">
				Lorem ipsum, dolor sit amet consectetur adipisicing elit. Veritatis
				doloribus optio inventore dolor reprehenderit cupiditate quaerat
				laudantium suscipit officiis quo, nulla ea labore ipsam fuga
				exercitationem atque. Magnam, ipsa pariatur.
			</p>
			<button class="btn btn-danger btn-lg" type="button">
				Bottone Carino
			</button>
		</div>
	</div>
</template>

<style scoped>
.jumbotron {
	background-color: darkcyan;
}
</style>
