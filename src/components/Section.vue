<script setup>
import { defineProps } from 'vue';

const {title, assets, subTitle, content, href, cta} = defineProps({
  assets: Array,
  title: String,
  subTitle: String,
  content: String,
  href: String,
  cta: String
})

</script>

<template>
  <section class="font-mono pl-4 grid place-content-center bg-slate-900 min-h-screen text-slate-200">
    <main class="
    min-h-screen
    grid
    place-content-center
    gap-4
    px-1 max-w-3xl
    
    ">
      <article class="grid gap-5">
        <section>
          <h1 class="font-bold mb-5 text-left underline text-4xl">
              {{title}}
          </h1>
        </section>
        <section>
          <main>
            <p class=" text-left text-xl">{{content}}</p>
          </main>
        </section>
        <footer>
          <a class="underline text-lg font-bold" :href="href">
            {{cta}}
          </a>
        </footer>
      </article>
    </main>
  </section>
</template>

<style>

</style>