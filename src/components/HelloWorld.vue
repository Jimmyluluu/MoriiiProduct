<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <div class="navbar bg-white">
  <div class="flex-1">
    <a class="btn btn-ghost normal-case text-xl">daisyUI</a>
  </div>
  <div class="flex-none">
    <ul class="menu menu-horizontal px-1">
      <li><a>賣場連結</a></li>
      <li>
        <details>
          <summary>
            聯繫我
          </summary>
          <ul class="p-2 bg-base-100">
            <li><a>Facebook</a></li>
            <li><a>Mail</a></li>
          </ul>
        </details>
      </li>
    </ul>
  </div>
</div>
  <h1>歡迎光臨 Moriii's Store</h1>
  <div class="flex flex-row flex-nowrap md:flex-10">
    <div class="card basis-1/3 bg-violet-300 et-300 shadow-xl">
      <figure>
        <img
          src="https://github.com/Jimmyluluu/image/blob/master/Selengangar-2.png?raw=true"
          alt="Shoes"
        />
      </figure>
      <div class="card-body">
        <h2 class="card-title text-white font-black">
          Dragoons 盲抽吊飾
          <div
            class="inline-flex items-center gap-1.5 py-1.5 px-3 rounded-full text-xs font-medium bg-pink-400 text-white"
          >
            NEW
          </div>
        </h2>
        <p class="text-white">6*6 cm / 1抽 NT.100 / 3抽優惠價 NT.250</p>
        <div class="card-actions justify-end">
          <div class="badge badge-outline text-violet-500">Charm</div>
          <div class="badge badge-outline text-violet-500">Products</div>
        </div>
      </div>
    </div>
    <div class="card basis-1/3 bg-violet-300 shadow-xl">
      <figure>
        <img
          src="https://github.com/Jimmyluluu/image/blob/master/Luxiem.png?raw=true"
          alt="Shoes"
        />
      </figure>
      <div class="card-body">
        <h2 class="card-title text-white font-black">
          Luxiem 飯友
          <div
            class="inline-flex items-center gap-1.5 py-1.5 px-3 rounded-full text-xs font-medium bg-pink-400 text-white"
          >
            NEW
          </div>
        </h2>
        <p class="text-white">
          4*4 cm / 1隻 NT.110 / Luxiem包團優惠價 NT.500 加贈一張限定款明信片
        </p>
        <div class="card-actions justify-end">
          <div class="badge badge-outline text-violet-500">Acryl Stand</div>
          <div class="badge badge-outline text-violet-500">Products</div>
        </div>
      </div>
    </div>
    <div class="card basis-1/3 bg-violet-300 shadow-xl">
      <figure>
        <img
          src="https://github.com/Jimmyluluu/image/blob/master/%E5%AE%A3%E5%82%B3%E8%BB%8A_selen%E8%80%BF%E9%AC%BC.png?raw=true"
          alt="Shoes"
        />
      </figure>
      <div class="card-body">
        <h2 class="card-title text-white font-black">
          小立牌
          <div
            class="inline-flex items-center gap-1.5 py-1.5 px-3 rounded-full text-xs font-medium bg-pink-400 text-white"
          >
            NEW
          </div>
        </h2>
        <p class="text-white">高 9~10 cm / 1隻 NT.150</p>
        <div class="card-actions justify-end">
          <div class="badge badge-outline text-violet-500">Acryl Stand</div>
          <div class="badge badge-outline text-violet-500">Products</div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
