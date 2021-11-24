<template>
<div>
    <img :src="img" :alt="text">
    <div>{{text}}</div> 
</div>
</template>

<script>
export default {
    name : `Games`,
    props : {
        img : String,
        text : String,
        price : String,
    }
}
</script>

<style>

</style>