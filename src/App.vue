
<template>
  <Header/>
  <MeetProtoapp/>
  <DeepDive/>
  <LastCall/>
  <Footer/>
</template>

<script setup>
  import Header from '@/components/Header.vue';
  import MeetProtoapp from '@/components/MeetProtoapp.vue';
  import DeepDive from '@/components/DeepDive.vue';
  import LastCall from '@/components/LastCall.vue';
  import Footer from '@/components/Footer.vue';
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap');

:root {
  --primary-font-color: hsl(0, 0%, 27%);
  --secondary-font-color: hsl(0, 0%, 100%);
  --card-color-one: hsl(60, 100%, 50%);
  --card-color-two: hsl(170, 72%, 52%);
  --primary-bg-color: hsl(0, 0%, 100%);
  --secondary-bg-color: hsl(0, 0%, 27%);
  --btn-color: hsl(240, 100%, 50%);
  --btn-color-dark-gold: hsl(51, 84%, 33%);
  --btn-color-dark-blue-green: hsl(152, 43%, 36%);
  --bg-color: hsl(240, 100%, 50%);
}

*, *::before, *::after {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.container {
  width: 80%;
  margin: 0 auto;
}

body {
  max-width: 1440px;
  height: 100%;
  color: var(--primary-font-color);
  font-family: 'Roboto', sans-serif;
  font-size: 1.3rem;
}

</style>
