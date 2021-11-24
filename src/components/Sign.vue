<template>
    <div class="background-4">
        <div class="container">
            <div class="button">
                SIGN-UP NOW!
            </div>

            <div class="follow">
                <h1>FOLLOW US</h1>
                <img src="@/assets/img/footer-facebook.png" alt="">
                <img src="@/assets/img/footer-twitter.png" alt="">
                <img src="@/assets/img/footer-youtube.png" alt="">
                <img src="@/assets/img/footer-pinterest.png" alt="">
                <img src="@/assets/img/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name : `Sign`
}
</script>

<style lang="scss">
    .background-4 {
        height: 100%;
        padding: 50px 0;
        position: relative;
        z-index: 1;
        background: #303030;
        .button {
            color: white;
            cursor: pointer;
            padding: 15px;
            border: 4px solid #0282f9;
            &:hover {
                color: #0282f9;
            }
        }
        .follow {
            display: flex;
            align-items: center;
            justify-content: space-between;
            img {
                width: 50px;
                margin: 0 10px;
            }
            h1 {
                color: #0282f9;
            }
        }
    }
</style>