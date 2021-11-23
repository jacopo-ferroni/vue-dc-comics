<template>
  <div class="background1">
      <div class="container">
          <div class="part" v-for="(info, index) in infos" :key="`info-${index}`">
            <!-- <img :src="require(`${info.img}`)" alt=""> -->
            <span>{{info.txt}}</span>
          </div>
      </div>
  </div>
</template>

<script>
export default {
    name : `Info`,
    data () {
      return {
        infos : [ 
          {
            img : `@/assets/img/buy-comics-digital-comics.png`,
            txt : `DIGITAL COMICS`,
          },
          {
            img : `@/assets/img/buy-comics-subscriptions.png`,
            txt : `DC MERCHANDISE`,
          },
          {
            img : `@/assets/img/buy-comics-shop-locator.png`,
            txt : `SUBSCRIPTION`,
          },
          {
            img : `@/assets/img/buy-comics-shop-locator.png`,
            txt : `COMI SHOP LOCATOR`,
          },
          {
            img : `@/assets/img/buy-comics-shop-locator.png`,
            txt : `DC POWER VISA`,
          },

        ],
      }
    }
}
</script>

<style lang="scss">
    .background1 {
      position: relative;
        background-color: #0282f9;
        width: 100%;
        z-index: 1;
        .container {
            padding: 40px 40px;
            .part {
                cursor: pointer;
                display: flex;
                align-items: center;
                justify-content: center;
                img {
                    width: 50px;
                }
                span {
                    color: white;
                    margin-left: 5px;
                }
            }
        }
    }
</style>