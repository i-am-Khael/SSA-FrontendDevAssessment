
<template>
  <nav>
    <div class="container">
      <div class="imgContainer">
        <img src="../assets/imgs/logo1.svg" alt="logo1">
        <h3>Protoapp</h3>
      </div>
      <div class="links">
        <a href="#">HOME</a>
      </div>
    </div>
  </nav>  
</template>

<style lang="scss" scoped>

nav {
  width: 100%;
  padding: 1rem 0;

  div.container {
    width: 80%;
    margin: 0 auto;
    display: flex;
    align-self: center;
    gap: 2rem;
  }

  div.imgContainer, div.links{
    display: flex;
    align-items: center;
    justify-content: center;
  }

  div.imgContainer img {
    width: 50px;
    height: 50px;
    cursor: pointer;
  }

  div.links a {
    color: var(--primary-font-color);
    text-decoration: none;
    font-weight: 500;
  }

}

</style>
