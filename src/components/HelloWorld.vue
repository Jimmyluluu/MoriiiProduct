<script setup>
import { ref } from "vue";

defineProps({
  msg: String,
});

const count = ref(0);
</script>

<template>
  <h1>歡迎光臨 Moriii's Store</h1>
  <div class="columns-3">
    <div class="card w-96 bg-violet-300 shadow-xl">
      <figure>
        <img
          src="https://github.com/Jimmyluluu/image/blob/master/Selengangar-2.png?raw=true"
          alt="Shoes"
        />
      </figure>
      <div class="card-body">
        <h2 class="card-title">
          Dragoons 盲抽吊飾
          <div class="badge badge-secondary">NEW</div>
        </h2>
        <p>If a dog chews shoes whose shoes does he choose?</p>
        <div class="card-actions justify-end">
          <div class="badge badge-outline">Fashion</div>
          <div class="badge badge-outline">Products</div>
        </div>
      </div>
    </div>
    <div class="card w-96 bg-violet-300 shadow-xl">
      <figure>
        <img
          src="https://github.com/Jimmyluluu/image/blob/master/Luxiem.png?raw=true"
          alt="Shoes"
        />
      </figure>
      <div class="card-body">
        <h2 class="card-title">
          Luxiem 飯友
          <div class="badge badge-secondary">NEW</div>
        </h2>
        <p>If a dog chews shoes whose shoes does he choose?</p>
        <div class="card-actions justify-end">
          <div class="badge badge-outline">Fashion</div>
          <div class="badge badge-outline">Products</div>
        </div>
      </div>
    </div>
    <div class="card w-96 bg-violet-300 shadow-xl">
      <figure>
        <img
          src="https://github.com/Jimmyluluu/image/blob/master/%E5%AE%A3%E5%82%B3%E8%BB%8A_selen%E8%80%BF%E9%AC%BC.png?raw=true"
          alt="Shoes"
        />
      </figure>
      <div class="card-body">
        <h2 class="card-title">
          小立牌
          <div class="badge badge-secondary">NEW</div>
        </h2>
        <p>If a dog chews shoes whose shoes does he choose?</p>
        <div class="card-actions justify-end">
          <div class="badge badge-outline">Fashion</div>
          <div class="badge badge-outline">Products</div>
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
