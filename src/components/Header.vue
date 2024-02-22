<script setup>

function rickroll() {
  onclick((e) => {
    e.preventDefault()
    window.location.replace("https://www.youtube.com/watch?v=MqsrmhNmN3k&ab_channel=%D0%94%D1%83%D0%BB%D0%BA%D1%83%D0%B1%D1%8B%D0%BA")
  })
}

</script>

<template>
  <div class="header">
    <div class="main_btn">
      <img class="logo" v-on:click="rickroll" src="../assets/wtf.svg" alt="">
      <button class="hdr_btn">Home</button>
      <button class="hdr_btn">Services</button>
      <button class="hdr_btn">How to buy</button>
      <button class="hdr_btn">About us</button>
      <button class="hdr_btn">Contacts</button>
      <button class="hdr_btn">Register</button>
    </div>
    <div class="main-text">
      <h2 class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aliquam asperiores debitis dolor dolorum explicabo iusto labore mollitia, optio pariatur quibusdam quo sunt temporibus, veniam voluptatem voluptates! Accusantium in neque quas. </h2>
      <img class="photo" src="../assets/food/rolls.png" alt="rolls">
    </div>

  </div>
</template>

<style scoped>
</style>
