<script setup>
import { ref } from 'vue'
const data = ref([
	{
		img: [
			'/images/t-shirt1.png',
			'/images/t-shirt2.png',
			'/images/t-shirt4.png',
		],
		name: 'Marple',
		logo: '/images/logo6.png',
	},
	{
		img: ['/images/phone1.png', '/images/phone2.png', '/images/phone4.png'],
		name: 'Huawei',
		logo: '/images/logo3.png',
	},
	{
		img: ['/images/hat1.png', '/images/hat2.png', '/images/boy5.png'],
		name: 'Berlingo',
		logo: '/images/logo7.png',
	},
	{
		img: ['/images/hat1.png', '/images/hat2.png', '/images/boy5.png'],
		name: 'Berlingo',
		logo: '/images/logo7.png',
	},

	{
		img: ['/images/hat1.png', '/images/hat2.png', '/images/boy5.png'],
		name: 'Berlingo',
		logo: '/images/logo7.png',
	},
	{
		img: ['/images/hat1.png', '/images/hat2.png', '/images/boy5.png'],
		name: 'Berlingo',
		logo: '/images/logo7.png',
	},
	{
		img: ['/images/hat1.png', '/images/hat2.png', '/images/boy5.png'],
		name: 'Berlingo',
		logo: '/images/logo7.png',
	},
	{
		img: ['/images/hat1.png', '/images/hat2.png', '/images/boy5.png'],
		name: 'Berlingo',
		logo: '/images/logo7.png',
	},
])
</script>

<template>
	<h1 class="text-3xl mb-7">Магазины для вас</h1>
	<div class="container mt-10 grid grid-cols-4 gap-7">
		<div
			v-for="(item, index) in data"
			:key="index"
			class="pt-[32px] pb-[38px] border border-white-500 px-[20px]"
		>
			<div class="pb-[30px] flex items-center justify-start gap-x-20">
				<div class="py-2 px-4">
					<img :src="item.logo" alt="Logo" />
				</div>
				<h2 class="text-[26px] font-medium uppercase">{{ item.name }}</h2>
			</div>
			<div class="flex gap-x-5">
				<img :src="item.img[0]" class="w-full h-[90px] border" alt="Image 1" />
				<img :src="item.img[1]" class="w-full h-[90px] border" alt="Image 2" />
				<img :src="item.img[2]" class="w-full h-[90px] border" alt="Image 3" />
			</div>
		</div>
	</div>
</template>

<style scoped></style>
