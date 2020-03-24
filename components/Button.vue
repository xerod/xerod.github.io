<template>
  <div class="rounded-md shadow">
    <a href="#" class="w-full flex items-center justify-center px-8 py-3 border border-transparent text-base leading-6 font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-500 focus:outline-none focus:shadow-outline transition duration-150 ease-in-out md:py-4 md:text-lg md:px-10">
      {{ buttonText }}
    </a>
  </div>
</template>

<script>
export default {
  props: {
    buttonText: {
      type: String,
      default: 'Next'
    }
  }
}
</script>

<style>

</style>
