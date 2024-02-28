<script setup>
import { images } from "./data/data.js";
</script>

<template>
  <div class="">
    <!-- <h1>{{ data.message }}</h1>
    <p class="mt-3">{{ data.date }}</p>
    <h5>
      You have <span>{{ data.task[4] }}</span>
    </h5>
    <h6>{{ data.name }}</h6> -->
  </div>

  <section>
    <div class="row">
      <div class="col">
        <img src="{{ images[0].image }}" alt="" />
        <h3>{{ images[1].title }}</h3>
        <button>button</button>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
