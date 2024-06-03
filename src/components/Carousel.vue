<script setup>
import 'swiper/css'
import 'swiper/css/navigation'
import 'swiper/css/pagination'
import { Swiper, SwiperSlide } from 'swiper/vue'
import { ref } from 'vue'

import { Autoplay, Navigation, Pagination } from 'swiper/modules'

const modules = ref([Pagination, Autoplay, Navigation])
</script>

<template>
	<div class="container mx-auto mt-3">
		<div class="flex gap-8">
			<swiper
				:slidesPerView="1"
				:spaceBetween="30"
				:autoplay="{
					delay: 5000,
					disableOnInteraction: false,
				}"
				:loop="true"
				:pagination="{
					clickable: true,
				}"
				:navigation="true"
				:modules="modules"
				class="mySwiper"
			>
				<swiper-slide>
					><img class="w-full" src="/images/baner.png" alt="" />
				</swiper-slide>
				<swiper-slide>
					><img class="w-full" src="/images/baner.png" alt="" />
				</swiper-slide>
				<swiper-slide>
					><img class="w-full" src="/images/baner.png" alt="" />
				</swiper-slide>
			</swiper>
			<div class="flex flex-col gap-y-12 w-[71%] py-5">
				<img class="" src="/images/image3.png" alt="" />
				<img class="" src="/images/image4.png" alt="" />
			</div>
		</div>
	</div>
</template>

<style></style>
