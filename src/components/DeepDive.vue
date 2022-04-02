
<template>
  <section class="deepDive">
    <h1>Deep dive. Ready?</h1>
    <p>So are we. Unless. You're. Not. Word filler</p>
    <div class="buttons">
      <div class="imgPlaystore">
        <img src="../assets/imgs/badge.play-store.svg" alt="badge-playstore">
      </div>
      <div class="imgAppstore">
        <img src="../assets/imgs/badge.app-store.svg" alt="badge-appstore">
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
section.deepDive {
  width: 100%;
  height: 80vh;
  margin: auto 0;
  background-color: var(--bg-color);
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  gap: 1rem;
  color: var(--secondary-font-color);

  div.buttons {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 2rem;
  }

}

</style>
