<template>
  <div class="container mx-auto">
    <div class="grid grid-cols-1 gap-8 md:grid-cols-2 lg:grid-cols-3">
      <div v-for="item in items" class="card bg-violet-300 shadow-xl">
        <figure>
          <img :src="item.imgUrl" alt="Shoes" />
        </figure>
        <div class="card-body">
          <div class="card-title text-white font-black">
            {{ item.title }}
            <div
              class="inline-flex items-center gap-1.5 py-1.5 px-3 rounded-full font-medium bg-pink-400 text-white"
            >
              NEW
            </div>
          </div>
          <p class="text-white">{{ item.specification }}</p>
          <div class="card-actions justify-end">
            <div class="badge badge-outline text-violet-500">Charm</div>
            <div class="badge badge-outline text-violet-500">Products</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref } from "vue";
const items = ref([
  {
    imgUrl:
      "https://github.com/Jimmyluluu/image/blob/master/Selengangar-2.png?raw=true",
    title: "Dragoons 盲抽吊飾",
    specification: "6*6 cm / 1抽 NT.100 / 3抽優惠價 NT.250",
  },
  {
    imgUrl:
      "https://github.com/Jimmyluluu/image/blob/master/Luxiem.png?raw=true",
    title: "Luxiem 飯友",
    specification:
      "4*4 cm / 1隻 NT.110 / Luxiem包團優惠價 NT.500 加贈一張限定款明信片",
  },
  {
    imgUrl:
      "https://raw.githubusercontent.com/Jimmyluluu/image/master/%E5%AE%A3%E5%82%B3%E8%BB%8A_selen%E8%80%BF%E9%AC%BC.png",
    title: "小立牌",
    specification: "高 9~10 cm / 1隻 NT.150",
  },
  {
    imgUrl:
      "https://github.com/Jimmyluluu/image/blob/master/Selengangar.png?raw=true",
    title: "Selen & 耿鬼飯友",
    specification: "4*4 cm / 1隻 NT.110",
  },
  {
    imgUrl:
      "https://github.com/Jimmyluluu/image/blob/master/Selengangar-3.png?raw=true",
    title: "明信片",
    specification: "A6 / 1張 NT.30",
  },
  {
    imgUrl:
      "https://github.com/Jimmyluluu/image/blob/master/Picture.png?raw=true",
    title: "拍立得 feat.可卿",
    specification: "1張 NT.70 (寫字or畫圖 NT.90)",
  },
]);
</script>
<style scoped>
.read-the-docs {
  color: #888;
}
</style>
