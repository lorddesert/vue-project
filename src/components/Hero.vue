<script setup>
 const { title, subTitle, buttonMessage } = defineProps({
    title: String,
    subTitle: String,
    buttonMessage: String,
  })

function goToGoogle() {
  location.href ="https://google.com"
}

</script>

<template>
<main class=" font-mono bg-slate-900 min-h-screen">
  <div class=" 
    px-2
    min-h-screen text-center bg-opacity-25 
    max-w-screen-sm
    grid gap-4 
    place-content-center
  ">
    <hgroup class="text-slate-200 grid gap-7">
      <h1 class=" font-bold text-left text-4xl">{{ title }}</h1>
      <h2 class=" text-left text-xl">{{subTitle}}</h2>
    </hgroup>
    <button class="transition-all ease text-lg py-3 bg-gradient-to-tr border border-transparent from-cyan-700 to-green-700 text-slate-200 shadow-sm shadow-green-500 hover:shadow-cyan-500 hover:border-cyan-700" 
    v-bind:click="goToGoogle">{{buttonMessage}}</button>
  </div>
  </main>
</template>
