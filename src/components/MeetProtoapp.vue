
<template>
  <section>
    <div class="container meet-protoapp">
    
      <div class="buttons">
        <div class="playStore">
          <img src="../assets/imgs/badge.play-store.svg" alt="badge-playstore">
        </div>
        <div class="appStore">
          <img src="../assets/imgs/badge.app-store.svg" alt="badge-appstore">
        </div>
      </div>
    
      <div class="meetProtoapp">
        <h1>Meet Protoapp</h1>
        <p>
          The app lorem ipsum is common placeholder text used to demonstrate the graphic elements of a document or visual representation.
        </p>
      </div>

      <div class="discover">
        <div class="info">
          <h2>Discover</h2>
          <p>
            Get information on using these
            guidelines whenever you are using
            therefore they have the same style and quality.
          </p>
        </div>
        <div class="discoverImg">
          <img src="../assets/imgs/product-search.svg" alt="">
        </div>
      </div>

      <div class="augmented">
        <div class="augImg">
          <img src="../assets/imgs/product-smartphone.svg" alt="">
        </div>
        <div class="auginfo">
          <h2>Augmented</h2>
          <p>
            World salad often arouses curiosity due to  its seemingly intelligent and tasteful play on words. 
          </p>
        </div>
      </div>

      <div class="endless">
        <div class="endlessInfo">
          <h2>Endless posibilities</h2>
          <p>
            Management System shouldn't be a bore. Run out of words? here's some lorem ipsum: Lorem ipsum dolor set amet. 
          </p>
        </div>
        <div class="endlessImg">
          <img src="../assets/imgs/product-work.svg" alt="">
        </div>
      </div>

    </div>
  </section>
</template>

<style lang="scss" scoped>
  section {
    width: 100%;
    background: url('../assets/imgs/bg-decals.svg') no-repeat;
    display: grid;

    div.buttons {
      width: 100%;
      margin-top: 10rem;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 2.5rem;
    }

    div.meetProtoapp {
      width: 90%;
      margin: 5rem auto;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 1rem;
      
      h1 {
        font-size: 2.5rem;
      }

      p {
        padding: 0 10rem;
        font-size: 1.3rem;
        text-align: center;
      }
    }

    @media all and (max-width: 720px) {

      div.meetProtoapp p {
        width: 100%;
        padding: 0 1rem;
        text-align: justify;
      }
      
    }

    // discover section
    div.discover, endless {
      width: 60%;
      margin: 7rem auto;
      display: flex;
      gap: 2rem;
      align-items: center;
      justify-content: center;

      div.discoverImg img, div.endlessImg img{
        width: 300px;
        height: 300px;
      }

      div.info, div.endlessInfo {
        text-align: right;
        
        h2 {
          margin-bottom: 1rem;
        }

      }


    }

    @media all and (max-width: 720px) {
      div.discover {
        width: 100%;
        flex-direction: column;
      }

      div.discoverImg {
        order: -1;
      }

    }

    // augmented section

    div.augmented {
      width: 60%;
      margin: 7rem auto;
      display: flex;
      gap: 2rem;
      align-items: center;
      justify-content: center;

        div.augImg img{
          width: 300px;
          height: 300px;
        }

        div.auginfo {
          
          h2 {
            margin-bottom: 1rem;
          }

        }

    }

    @media all and (max-width: 720px) {

      div.augmented {
        width: 100%;
        flex-direction: column;
      }
    }
    
    // endless section
    div.endless {
      width: 60%;
      margin: 7rem auto;
      display: flex;
      gap: 2rem;
      align-items: center;
      justify-content: center;

      div.endlessImg img{
        width: 300px;
        height: 300px;
      }

      div.endlessInfo {
        text-align: right;
        
        h2 {
          margin-bottom: 1rem;
        }

      }


    }

    @media all and (max-width: 720px) {
      div.endless {
        width: 100%;
        flex-direction: column;
      }

      div.endlessImg {
        order: -1;
      }

    }
  }

</style>
