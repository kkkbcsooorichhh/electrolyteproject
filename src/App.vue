<script setup lang="ts">
import { RouterLink, RouterView } from "vue-router";
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
	<header>
		<div class="wrapper">
			<HelloWorld />
		<p></p>
			
		</div>
	</header>


</template>

<style>
html {
	font-size: 26px !important;
}

body {
	margin: 0;
}
header {
  line-height: 1.5;
  max-height: 100vh;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}


</style>
