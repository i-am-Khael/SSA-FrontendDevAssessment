
<template>
<footer>
  <div class="container">
    <div class="footerInfo">
      <div class="footerImg">
        <img src="../assets/imgs/logo1.svg" alt="footer-logo">
      </div>
      <div class="footerMsg">
        <h3>Protoapp</h3>
        <h3>Camp One Inc, LLC</h3>
        <p>
          Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nemo, nesciunt pariatur? At sit maiores tenetur quis molestiae aliquam laborum assumenda nobis nostrum ipsa? Incidunt repudiandae sint id cum, sequi perferendis! 
        </p>
      </div>
    </div>
  <p>&copy; 2022 Protoapp. All rights reserved.</p>
  </div>
</footer>
</template>

<style lang="scss" scoped>
footer {
  width: 100%;
  padding: 3rem 0;
  background-color: var(--secondary-bg-color);
  color: var(--secondary-font-color);

  div.footerInfo {
    margin-bottom: 1rem;
    display: flex;
    gap: 1rem;

    div.footerImg img{
      width: 50px;
      height: 50px;
    }

    div.footerMsg {
      width: 45%;
      display: flex;
      flex-direction: column;

      p {
        line-height: 2.3rem;
      }
    }

    @media all and (max-width: 720px) {
      div.footerMsg {
        width: 100%;
      }
    }

  }
}

@media all and (max-width: 720px) {
  footer {
    margin-top: 20rem;
  }
}

</style>
