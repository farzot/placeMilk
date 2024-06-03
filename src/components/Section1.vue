<script setup>
import { reactive } from "vue";

const objData = reactive([
  {
    img: "/images/boy1.png",
    text: "1 999 ₽",
    description:
      "-25% 1 999 ₽ 2 499 ₽ Футболка с дизайнерским принтом Super Shape 02фиолетовая",
  },
  {
    img: "/images/boy2.png",
    text: "1 375 ₽",
    description:
      "-Футболка80 с дизайнерским принтом Super Shape 0201 абстракция на фиолетовом фоне",
  },
  {
    img: "/images/hat1.png",
    text: "599 ₽",
    description: "Бейсболка с дизайнерским принтом Super Shape 01",
  },
  {
    img: "/images/phone1.png",
    text: "599 ₽",
    description: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/boy1.png",
    text: "2 399 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 06",
  },
  {
    img: "/images/boy2.png",
    text: "1 375 ₽",
    description: "Бейсболка с дизайнерским принтом Super Shape 02",
  },
  {
    img: "/images/hat2.png",
    text: "599",
    description: "Чехол для iphone 12 с дизайнерским принтом Super Shape 03",
  },
  {
    img: "/images/phone2.png",
    text: "3 179 ₽",
    description: "-Чехол для iphone 12 с дизайнерским принтом Super Shape 02",
  },
  {
    img: "/images/phone4.png",
    text: "1 999 ₽",
    description: "Футболка с дизайнерским принтом Super Shape 02",
  },
  {
    img: "/images/boy3.png",
    text: "2 399 ₽",
    description: "Чехол для iphone 12 с дизайнерским принтом Super Shape 06",
  },
  {
    img: "/images/phone4.png",
    text: "1 999 ₽",
    description:
      "-25% 1 999 ₽ 2 499 ₽ Футболка с дизайнерским принтом Super Shape 02фиолетовая",
  },
  {
    img: "/images/boy3.png",
    text: "1 999 ₽",
    description:
      "-25% 1 999 ₽ 2 499 ₽ Футболка с дизайнерским принтом Super Shape 02фиолетовая",
  },
]);
</script>

<template>
  <div class="w-full h-full relative">
    <div class="">
      <h2 class="text-[28px] font-normal pt-10 mb-4">Успей купить</h2>
      <div
        class="grid grid-cols-6 gap-10 p-4 group bg-white border rounded-md shadow-3xl w-full h-auto hover:absolute top-0 left-0 z-30 hover:scale-105 duration-200"
      >
        <div v-for="(item, index) in objData" :key="index" class="relative">
          <span
            class="absolute text-[10px] rounded-xl py-0.5 px-1 font-medium right-2 top-2"
          >
            -25%
          </span>
          <div class="border border-white-500 px-[20px] py-4">
            <img class="mb-5 w-full h-[160px] object-cover" :src="item.img" />
            <h2 class="text-[14px] mb-3 text-[#FF4343] text font-bold">
              {{ item.text }}
            </h2>
            <p class="max-w-[157px] text-[12px] font-light">
              {{ item.description }}
            </p>
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
