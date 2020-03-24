<template>
  <div class="example relative whitespace-no-wrap scrolling-touch px-4">
    <!-- <div class="border-4 p-12 inline-block">
      <p>test</p>
    </div>
    <div class="border-4 p-12 inline-block">
      <p>test</p>
    </div>
    <div class="border-4 p-12 inline-block">
      <p>test</p>
    </div>
    <div class="border-4 p-12 inline-block">
      <p>test</p>
    </div> -->
    <card>
      <img class="mx-auto w-12 object-contain" src="~/assets/logo-riliv.png" style="filter: grayscale(100%)">
      <p class="text-sm font-semibold mt-6">
        Freelance Front-end Dev
      </p>
      <p class="text-xs font-semibold text-gray-600">
        2019 - 2020
      </p>
    </card>
    <card>
      <img class="w-32 mx-auto object-contain opacity-75" src="~/assets/logo-vigma.png" style="filter: grayscale(100%)">
      <p class="text-sm text-gray-800 font-semibold mt-6">
        Full-Stack Developer
      </p>
      <p class="text-xs text-gray-600">
        2018 - Now
      </p>
    </card>
    <card>
      <div class="flex text-xl justify-center opacity-75">
        <p class="text-gray-800 font-extrabold">
          TEDx
        </p>
        <p>JalanTunjungan</p>
      </div>
      <p class="text-sm font-semibold mt-6">
        Web Runner and Maintainer
      </p>
      <p class="text-xs text-gray-600">
        2018
      </p>
    </card>
  </div>
</template>

<script>
import card from '@/components/Card.vue'
export default {
  components: {
    card
  }
}
</script>

<style>
.example {
  overflow-x: scroll;
  overflow-y: hidden;
}
.example::-webkit-scrollbar {
  display: none;
}
.example {
  -ms-overflow-style: none;
}
</style>
