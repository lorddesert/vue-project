<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import Hero from './components/Hero.vue'
import Section from './components/Section.vue'
</script>

<template>
  <Hero
    title="Beyond our imagination"
    sub-title="Explore different worlds... And moons!"
    button-message="Find your next inspiration"
  />
  <Section
    title="M.O.O.N.S"
    content="
    Moons come in many shapes,
     sizes, and types. A few have atmospheres and even hidden oceans beneath their surfaces. 
     Most planetary moons probably formed from the discs of gas and dust circulating around planets in the early solar system, 
     though some are 'captured' objects that formed elsewhere and fell into orbit around larger worlds.
    "
    href="https://solarsystem.nasa.gov/moons/overview/"
    cta="Wanna know more?"
   />
  <Section
    title="Our Saviour"
    content="
    The Sun is the largest object in our solar system. The Sun’s volume would need 1.3 million Earths to fill it. Its gravity holds the solar system together, keeping everything from the biggest planets to the smallest bits of debris in orbit around it. The hottest part of the Sun is its core, where temperatures top 27 million degrees Fahrenheit (15 million degrees Celsius). The Sun’s activity, from its powerful eruptions to the steady stream of charged particles it sends out, influences the nature of space throughout the solar system.
    "
    href="https://solarsystem.nasa.gov/solar-system/sun/overview/"
    cta="Praise the sun!"
   />
  <Section
    title="At the end..."
    content="
    The universe is a sea of opportunities to curious people that want to learn more, and discover new feelings. I encourage you to take your time to stop a minute, watch up in the sky in the midnight, and see the bast world where all of we belongs to.
    "
    href="https://lorddesert.xyz"
    cta="Launch your dreams!"
   />
</template>

<style>
</style>
