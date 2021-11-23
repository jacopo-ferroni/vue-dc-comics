<template>
  <div class="container">
      <img src="@/assets/img/dc-logo.png" alt="">

      <ul>
          <li>
              CHARACTERS
          </li>
          <li>
              COMICS
          </li>
          <li>
              MOVIES
          </li>
          <li>
              TV
          </li>
          <li>
              GAMES
          </li>
          <li>
              COLLECTIBLES
          </li>
          <li>
              VIDEOS
          </li>
          <li>
              FANS
          </li>
          <li>
              NEWS
          </li>
          <li>
              SHOP
          </li>
      </ul>
  </div>
</template>

<script>
export default {
    name : `Header`
}
</script>

<style lang="scss">
.container {
    position: relative;
    z-index: 1;
    max-width: 1400px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: auto;
    img {
        width: 70px;
        cursor: pointer;
    }
    ul {
        list-style: none;
        li {
            cursor: pointer;
            font-size: 14px;
            display: inline-block;
            padding: 40px 0;
            margin: 0 10px;
            color: #1c1c1c;
            border-bottom: 5px solid rgba($color: #000000, $alpha: .0);
            &:hover {
                border-bottom: 5px solid #0282f9;
                color: #0282f9;
            }
        }
    }
}
</style>