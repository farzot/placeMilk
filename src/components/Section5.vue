<script setup>
import { reactive } from 'vue'

const objData = reactive([
	{
		img: '/images/boy1.png',
		text: '1 999 ₽',
		describtion:
			'-25% 1 999 ₽ 2 499 ₽ Футболка с дизайнерским принтом Super Shape 02фиолетовая',
	},
	{
		img: '/images/boy2.png',
		text: '1 375 ₽',
		describtion:
			'-Футболка80 с дизайнерским принтом Super Shape 0201 абстракция на фиолетовом фоне',
	},
	{
		img: '/images/boy3.png',
		text: '599 ₽',
		describtion: 'Бейсболка с дизайнерским принтом Super Shape 01',
	},
	{
		img: '/images/boy2.png',
		text: '599 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/boy1.png',
		text: '2 399 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 06',
	},
])
</script>

<template>
	<div>
		<div class="p-4 from-slate-50 mt-5">
			<h2 class="text-[28px] font-medium pt-10 mb-4 text-[ #000000]">
				Ранее вы смотрели
			</h2>
			<div class="grid grid-cols-5 gap-x-5 py-8 px-5">
				<div v-for="(item, index) in objData" :key="index" class="">
					<div class="flex gap-x-5 border border-white-500 py-5 px-2">
						<img class="mb-5 w-full h-[160px] object-cover" :src="item.img" />
						<div>
							<p class="text-[12px] font-light mb-5">
								{{ item.describtion }}
							</p>
							<h2 class="text-[14px] mb-3 text-[##000000] text font-bold">
								{{ item.text }}
							</h2>
						</div>
					</div>
				</div>
			</div>
		</div>

		<div class="flex justify-end pr-5 py-5">
			<button
				class="gradient-border border border-gradient py-4 px-6 from-slate-300"
			>
				Все товары
			</button>
		</div>
	</div>
</template>

<style lang="scss" scoped></style>
