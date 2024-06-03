<script setup>
import { reactive } from 'vue'

const objData = reactive([
	{
		img: '/images/t-shirt1	.png',
		text: '1 999 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/boy8.png',
		text: '1 375 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/t-shirt6.png',
		text: '599 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 01',
	},
	{
		img: '/images/phone5.png',
		text: '599 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/phone7.png',
		text: '2 399 ₽',
		describtion: 'Бейсболка с дизайнерским принтом Super Shape 01',
	},
	{
		img: '/images/hat1.png',
		text: '1 375 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/phone8.png',
		text: '599',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/t-shirt1.png',
		text: '3 179 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 05',
	},
	{
		img: '/images/phone9.png',
		text: '1 999 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/t-shirt6.png',
		text: '2 399 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/phone4.png',
		text: '1 999 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/boy3.png',
		text: '1 999 ₽',
		describtion:
			'-25% 1 999 ₽ 2 499 ₽ Футболка с дизайнерским принтом Super Shape 02фиолетовая',
	},
	{
		img: '/images/t-shirt1	.png',
		text: '1 999 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/boy8.png',
		text: '1 375 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/t-shirt6.png',
		text: '599 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 01',
	},
	{
		img: '/images/phone5.png',
		text: '599 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/phone7.png',
		text: '2 399 ₽',
		describtion: 'Бейсболка с дизайнерским принтом Super Shape 01',
	},
	{
		img: '/images/hat1.png',
		text: '1 375 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/phone8.png',
		text: '599',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/t-shirt1.png',
		text: '3 179 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 05',
	},
	{
		img: '/images/phone9.png',
		text: '1 999 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/t-shirt6.png',
		text: '2 399 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/phone4.png',
		text: '1 999 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/boy3.png',
		text: '1 999 ₽',
		describtion:
			'-25% 1 999 ₽ 2 499 ₽ Футболка с дизайнерским принтом Super Shape 02фиолетовая',
	},
	{
		img: '/images/t-shirt1	.png',
		text: '1 999 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/boy8.png',
		text: '1 375 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/t-shirt6.png',
		text: '599 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 01',
	},
	{
		img: '/images/phone5.png',
		text: '599 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/phone7.png',
		text: '2 399 ₽',
		describtion: 'Бейсболка с дизайнерским принтом Super Shape 01',
	},
	{
		img: '/images/hat1.png',
		text: '1 375 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/phone8.png',
		text: '599',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/t-shirt1.png',
		text: '3 179 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 05',
	},
	{
		img: '/images/phone9.png',
		text: '1 999 ₽',
		describtion: 'Чехол для iphone 12 с дизайнерским принтом Super Shape 03',
	},
	{
		img: '/images/t-shirt6.png',
		text: '2 399 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/phone4.png',
		text: '1 999 ₽',
		describtion: 'Футболка с дизайнерским принтом Super Shape 04',
	},
	{
		img: '/images/boy3.png',
		text: '1 999 ₽',
		describtion:
			'-25% 1 999 ₽ 2 499 ₽ Футболка с дизайнерским принтом Super Shape 02фиолетовая',
	},
])
</script>

<template>
	<div>
		<div class="">
			<h2 class="text-[28px] font-normal pt-0 mb-4">
				Рекомендуемые для вас товары
			</h2>
			<div class="grid grid-cols-6 gap-10">
				<div v-for="(item, index) in objData" :key="index">
					<div class="px-[20px] py-4 border border-white-500">
						<img class="mb-5 w-full h-[160px] object-cover" :src="item.img" />
						<h2
							class="text-[16x] font-medium mb-3 text-[#000000] text font-bold"
						>
							{{ item.text }}
						</h2>
						<p class="max-w-[180px] text-[12px] font-light">
							{{ item.describtion }}
						</p>
					</div>
				</div>
			</div>
		</div>

		<div class="flex justify-end pr-5 py-5">
			<button class="text-[14px] font-bold py-3 px-7 border border-[#F64D4D]">
				Все товары
			</button>
		</div>
		<div>
			<h2 class="text-[28px] font-medium mb-4">
				Широкий ассортимент и высокое качество
			</h2>
			<p class="mb-3">
				Интернет-магазин PlaceMik – это доступные цены, широкий, регулярно
				обновляемый ассортимент. В онлайн-каталоге PlaceMik представлено около
				35 000 ведущих брендов женской, мужской и детской одежды и обуви.
				Покупателям предлагается электроника, книжная продукция, детские товары.
				В интернет-магазине можно приобрести продукцию для дома, продукты
				питания, товары для красоты, ювелирные изделия, игрушки. Для удобства
				пользования онлайн-каталог поделен на разделы, все товары можно
				сортировать по ряду критериев: цена, материал изготовления,
			</p>
			<a class="text-[#F64D4D] text-[16px]">Читать полностью</a>
		</div>
	</div>
</template>

<style lang="scss" scoped></style>
