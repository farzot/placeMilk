<script setup>
import Carousel from './components/Carousel.vue'
import Header from './components/Header.vue'
import Section1 from './components/Section1.vue'
import Section2 from './components/Section2.vue'
import Section3 from './components/Section3.vue'
import Section4 from './components/Section4.vue'
import Section5 from './components/Section5.vue'
</script>

<template class="bg-gray-500">
	<div class="container  mx-4 my-4 ">
		<Header />
		<Carousel />
		<Section1 />
		<Section2 />
		<Section3 />
		<Section4 />
		<Section5 />
	</div>
</template>

<style scoped>
.logo {
	height: 6em;
	padding: 1.5em;
	will-change: filter;
	transition: filter 300ms;
}
.logo:hover {
	filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
	filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
