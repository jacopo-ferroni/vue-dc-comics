<template>
  <div class="background2">
      <div class="container">
          <div class="section-left">
              <div class="first-col">
                  <h1>DC COMICS</h1>
                  <ul>
                      <li>
                          Characters
                      </li>
                      <li>
                          Comics
                      </li>
                      <li>
                          Movies
                      </li>
                      <li>
                          TV
                      </li>
                      <li>
                          Games
                      </li>
                      <li>
                          Videos
                      </li>
                      <li>
                          News
                      </li>
                  </ul>
                  <h1>SHOP</h1>
                  <ul>
                      <li>
                          Shop DC
                      </li>
                      <li>
                          Shop DC Collectibles
                      </li>
                  </ul>
              </div>
              <div class="second-col">
                  <h1>DC</h1>
                  <ul>
                      <li>
                          Terms Of Use
                      </li>
                      <li>
                          Privacy policy(New)
                      </li>
                      <li>
                          Ad Choices
                      </li>
                      <li>
                          Adversting
                      </li>
                      <li>
                          Jobs
                      </li>
                      <li>
                          Subscriptions
                      </li>
                      <li>
                          Talent Workshop
                      </li>
                      <li>
                          CPSC Certificates
                      </li>
                      <li>
                          Ratings
                      </li>
                      <li>
                          Shop Help
                      </li>
                      <li>
                          Contact Us
                      </li>
                  </ul>
              </div>
              <div class="third-col">
                  <h1>SITES</h1>
                  <ul>
                      <li>
                          DC
                      </li>
                      <li>
                          MAD Magazine
                      </li>
                      <li>
                          DC Kids
                      </li>
                      <li>
                          DC Universe
                      </li>
                      <li>
                          DC Power Visa
                      </li>
                  </ul>
              </div>
          </div>
      </div>
    
    <img src="@/assets/img/dc-logo-bg.png" alt="">
  </div>
</template>

<script>
export default {
    name : `Vue`,
}
</script>

<style lang="scss">
    .background2 {
        position: relative;
        width: 100%;
        background-image: url("../assets/img/footer-bg.jpg");
        background-size: 100%;
        img {
            position: absolute;
            z-index: 0;
            top: -23%;
            right: 18%;
        }
        .section-left {
            padding: 20px 0;
            width: 40%;
            display: flex;
            justify-content: space-between;
            .first-col {
                color: white;
            }
            .second-col {
                color: white;
            }
            .third-col {
                color: white;
            }

            li {
                border: 0px;
                cursor: pointer;
                color: grey;
                display: block;
                margin: 0%;
                padding: 0%;
                line-height: 25px;
                &:hover {
                    border: 0;
                }
            }
        }
    }
</style>