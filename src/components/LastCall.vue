
<template>
  <section class="lastCall">
    <h1>Last Call to Action</h1>
    <p>Another section goes here.</p>
    <div class="cards">
      <div class="card1">
        <div class="imgCont">
          <img src="../assets/imgs/badge.laravel-mix.svg" alt="badge-laravel-mix">
          <button>AUTOMATION</button>
        </div>
        <div class="card1Info">
          <label>ROLL OUT</label>
          <h2>Automatic Prototyping</h2>
          <p>
            Webpack is the most powerful and flexible asset compilation tool available today. With that power, however, comes a certain level of complexity.
          </p>
        </div>
      </div>
      <div class="card2">
        <div class="imgCont">
          <img src="../assets/imgs/badge.how-to-read-code.svg" alt="badge-how-to-read-code">
          <button>SIMPLICITY</button>
        </div>
        <div class="card2Info">
          <label>SIP COFFEE</label>
          <h2>Complexity Simplified</h2>
          <p>
            I know too many backend developers who are stifled by one glaring phobia. CSS. How do you construct a layout when nothing lines up? 
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
  section.lastCall {
    width: 100%;
    height: 100vh;
    padding: 5rem 0;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    background: url('../assets/imgs/bg-decals3.svg') no-repeat;
    background-position: bottom;

    h1 {
      margin-bottom: .5rem;
    }

    div.cards {
      width: 100%;
      display: flex;
      align-items: center;
      margin-top: 5rem;
      gap: 2rem;

      div.card1{
        width: 35%;
        margin-left: auto;
        padding: 2rem;
        border-radius: 1rem;
        background-color: var(--card-color-one);
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 2rem;
        color: var(--secondary-font-color);

        div.imgCont button {
          padding: .5rem 1rem;
          border: none;
          outline: none;
          border-radius: 1rem;
          margin-top: 1rem;
          font-weight: 700;
          color: var(--secondary-font-color);
          background-color: var(--btn-color-dark-gold);
        }

        label {
          font-size: .9rem;
        }

        h2 {
          margin-bottom: 1rem;
        }

      }
      
      div.card2 {
        width: 35%;
        margin-right: auto;
        padding: 2rem;
        border-radius: 1rem;
        background-color: var(--card-color-two);
        display: flex;
        align-items: center;
        justify-content: center;
        gap: 2rem;
        color: var(--secondary-font-color);

        div.imgCont button {
          padding: .5rem 1rem;
          border: none;
          outline: none;
          border-radius: 1rem;
          margin-top: 1rem;
          font-weight: 700;
          color: var(--secondary-font-color);
          background-color: var(--btn-color-dark-blue-green);
        }

        label {
          font-size: .9rem;
        }

        h2 {
          margin-bottom: 1rem;
        }


      }

      @media all and (max-width: 720px) {
        div.card1, div.card2 {
          width: 90%;
          margin: 0 auto;
          flex-direction: column;
          text-align: center;

          div.imgCont {
            display: flex;
            flex-direction: column;
          }

        }
      }
    }

    @media all and (max-width: 720px) {  
      div.cards {
        flex-direction: column;
      }
    }

  }

  @media all and (max-width: 720px) {
    section.lastCall {
        margin-top: 15rem;
      }
  }
</style>
