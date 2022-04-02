
<template>
  <header>
    <Nav/>
    <div class="container">
      <section>
        <h1>Protoapp</h1>
        <p>
          Our landing page template works on all devices, so you only have to setup it up once, and get beautiful results forever.
        </p>
        <button class="btnSubmit" type="submit">Get Started</button>
      </section>
    </div>
  </header>
</template>

<script setup>
  import Nav from './Nav.vue';
</script>

<style lang="scss" scoped>
header{
  width: 100%;
  height: 100vh;
  background: url('../assets/imgs/bg-leaves.svg') no-repeat;
  background-position: center center;
  background-size: cover;

  section {
    width: 45%;
    height: 100%;
    padding: 5rem 0;
    display: flex;
    flex-direction: column;
    gap: 1rem;

    h1 {
      font-size: 2.5rem;
      font-weight: 400;
    }

    p {
      font-size: 1.3rem;
      line-height: 1.4rem;
    }

    button.btnSubmit {
      width: 110px;
      padding: .6rem;
      color: var(--secondary-font-color);
      background-color: var(--btn-color);
      border: none;
      border-radius: .2rem;
      font-weight: 700;
      cursor: pointer;
    }
  }

  @media all and (max-width: 720px) {
    section {
      width: 100%;
    }
  }
}
</style>
