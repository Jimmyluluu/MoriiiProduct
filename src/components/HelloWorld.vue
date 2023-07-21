<script setup>
import { ref } from "vue";
const items = ref([
  {
    imgUrl: "https://github.com/Jimmyluluu/image/blob/master/Selengangar-2.png?raw=true",
    title: "Dragoons 盲抽吊飾",
    specification: "6*6 cm / 1抽 NT.100 / 3抽優惠價 NT.250",
  },
]);

</script>

<template>
  <div class="navbar bg-white w-full">
    <div class="flex-1">
      <a
        class="btn btn-ghost normal-case text-xl"
        style="text-decoration-coloror: #8b75ba"
        >Moriii's Store</a
      >
    </div>
    <div class="flex-none">
      <ul class="menu menu-horizontal px-1">
        <li><a>賣場連結</a></li>
        <li>
          <details>
            <summary>聯繫我</summary>
            <ul class="p-2 bg-base-100">
              <li><a>Facebook</a></li>
              <li><a>Mail</a></li>
            </ul>
          </details>
        </li>
      </ul>
    </div>
  </div>
  <!-- <h1>歡迎光臨 Moriii's Store</h1> -->
  <div class="flex flex-col gap-8">
    <div class="flex flex-row flex-nowrap gap-8 md:flex-10 w-5/6">
      <div v-for="item in items" class="card basis-1/3 bg-violet-300 et-300 shadow-xl">
        <figure>
          <img
            :src="item.imgUrl"
            alt="Shoes"
          />
        </figure>
        <div class="card-body">
          <h2 class="card-title text-white font-black">
            {{item.title}}
            <div
              class="inline-flex items-center gap-1.5 py-1.5 px-3 rounded-full text-xs font-medium bg-pink-400 text-white"
            >
              NEW
            </div>
          </h2>
          <p class="text-white">{{item.specification}}</p>
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
    <div class="flex flex-row flex-nowrap gap-8 md:flex-10 w-5/6">
      <div class="card basis-1/3 bg-violet-300 et-300 shadow-xl">
        <figure>
          <img
            src="https://github.com/Jimmyluluu/image/blob/master/Selengangar.png?raw=true"
            alt="Shoes"
          />
        </figure>
        <div class="card-body">
          <h2 class="card-title text-white font-black">
            Selen & 耿鬼飯友
            <div
              class="inline-flex items-center gap-1.5 py-1.5 px-3 rounded-full text-xs font-medium bg-pink-400 text-white"
            >
              NEW
            </div>
          </h2>
          <p class="text-white">4*4 cm / 1隻 NT.110</p>
          <div class="card-actions justify-end">
            <div class="badge badge-outline text-violet-500">Acryl Stand</div>
            <div class="badge badge-outline text-violet-500">Products</div>
          </div>
        </div>
      </div>
      <div class="card basis-1/3 bg-violet-300 shadow-xl">
        <figure>
          <img
            src="https://github.com/Jimmyluluu/image/blob/master/Selengangar-3.png?raw=true"
            alt="Shoes"
          />
        </figure>
        <div class="card-body">
          <h2 class="card-title text-white font-black">
            明信片
            <div
              class="inline-flex items-center gap-1.5 py-1.5 px-3 rounded-full text-xs font-medium bg-pink-400 text-white"
            >
              NEW
            </div>
          </h2>
          <p class="text-white">A6 / 1張 NT.30</p>
          <div class="card-actions justify-end">
            <div class="badge badge-outline text-violet-500">Acryl Stand</div>
            <div class="badge badge-outline text-violet-500">Products</div>
          </div>
        </div>
      </div>
      <div class="card basis-1/3 bg-violet-300 shadow-xl">
        <figure>
          <img
            src="https://github.com/Jimmyluluu/image/blob/master/Picture.png?raw=true"
            alt="Shoes"
          />
        </figure>
        <div class="card-body">
          <h2 class="card-title text-white font-black">
            拍立得 feat.可卿
            <div
              class="inline-flex items-center gap-1.5 py-1.5 px-3 rounded-full text-xs font-medium bg-pink-400 text-white"
            >
              NEW
            </div>
          </h2>
          <p class="text-white">1張 NT.70 (寫字or畫圖 NT.90)</p>
          <div class="card-actions justify-end">
            <div class="badge badge-outline text-violet-500">Polaroid</div>
            <div class="badge badge-outline text-violet-500">Products</div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <footer
    class="footer w-full p-10 text-violet-50"
    style="background-color: #8b75ba"
  >
    <div>
      <a>&copy; 2023 Jimmy Lu & Moriii</a>
    </div>
    <div class="text-violet-50">
      <span class="footer-title">Social</span>
      <div class="grid grid-flow-col gap-4">
        <a>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            class="fill-current"
          >
            <path
              d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"
            ></path></svg
        ></a>
        <a>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            class="fill-current"
          >
            <path
              d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z"
            ></path>
          </svg>
        </a>
        <a>
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            class="fill-current"
          >
            <path
              d="M9 8h-3v4h3v12h5v-12h3.642l.358-4h-4v-1.667c0-.955.192-1.333 1.115-1.333h2.885v-5h-3.808c-3.596 0-5.192 1.583-5.192 4.615v3.385z"
            ></path>
          </svg>
        </a>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
