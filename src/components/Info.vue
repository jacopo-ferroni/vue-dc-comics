<template>
  <div class="background1">
      <div class="container">
          <div class="part" v-for="(info, index) in infos" :key="`info-${index}`">
            <img :src="info.img" alt="">
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
            img : require(`@/assets/img/buy-comics-digital-comics.png`),
            txt : `DIGITAL COMICS`,
          },
          {
            img : require(`@/assets/img/buy-comics-subscriptions.png`),
            txt : `DC MERCHANDISE`,
          },
          {
            img : require(`../assets/img/buy-comics-merchandise.png`),
            txt : `SUBSCRIPTION`,
          },
          {
            img : require(`../assets/img/buy-comics-shop-locator.png`),
            txt : `COMI SHOP LOCATOR`,
          },
          {
            img : `<svg version="1.1" id="Layer_2_1_" xmlns="http://www.w3.org/2000/svg" x="0" y="0" viewBox="0 0 79.5 50.9" xml:space="preserve"><style>.st0{fill:none;stroke:#fff;stroke-width:1.7732;stroke-miterlimit:10}</style><path class="st0" d="M73.9 49.6H5.3c-2.1 0-3.8-1.7-3.8-3.8V5.4c0-2.1 1.7-3.8 3.8-3.8h68.6c2.1 0 3.8 1.7 3.8 3.8v40.3c0 2.1-1.7 3.9-3.8 3.9zM1.5 15.4h76.2"/><path fill="#fff" stroke="#fff" stroke-width=".998" stroke-linecap="round" stroke-linejoin="round" stroke-miterlimit="10" d="M50.1 22.1l-9.7 1.4 5.1-16.4L29 30.2l9.3-1.3L34.4 44z"/></svg>`,
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