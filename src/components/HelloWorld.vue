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
    <div class="card w-96 bg-base-100 shadow-xl">
      <figure>
        <img
          src="https://github.com/Jimmyluluu/image/blob/master/Standingsign.png?raw=true"
          alt="Shoes"
        />
      </figure>
      <div class="card-body">
        <h2 class="card-title">
          Shoes!
          <div class="badge badge-secondary">NEW</div>
        </h2>
        <p>If a dog chews shoes whose shoes does he choose?</p>
        <div class="card-actions justify-end">
          <div class="badge badge-outline">Fashion</div>
          <div class="badge badge-outline">Products</div>
        </div>
      </div>
    </div>
    <div class="card w-96 bg-base-100 shadow-xl">
      <figure>
        <img
          src="https://github.com/Jimmyluluu/image/blob/master/Standingsign.png?raw=true"
          alt="Shoes"
        />
      </figure>
      <div class="card-body">
        <h2 class="card-title">
          Shoes!
          <div class="badge badge-secondary">NEW</div>
        </h2>
        <p>If a dog chews shoes whose shoes does he choose?</p>
        <div class="card-actions justify-end">
          <div class="badge badge-outline">Fashion</div>
          <div class="badge badge-outline">Products</div>
        </div>
      </div>
    </div>
    <div class="card w-96 bg-base-100 shadow-xl">
      <figure>
        <img
          src="https://github.com/Jimmyluluu/image/blob/master/Standingsign.png?raw=true"
          alt="Shoes"
        />
      </figure>
      <div class="card-body">
        <h2 class="card-title">
          Shoes!
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
