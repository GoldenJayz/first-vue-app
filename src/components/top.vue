<template>
  <div>
      <img :src="images.i2" class="left"/>
      <img :src="images.i2" class="right"/>
      <img :src="images.i2" class="right"/>
      <img :src="images.i2" class="right"/>
  </div>
</template>

<script>
export default {
    data() {
        return {
            images: 
                {
                    i1: "https://media3.giphy.com/media/WrVOtWEay7fJS/200.gif",
                    i2: "https://i.imgur.com/Mj2iT9d.gif"
                }
            }
    }
}
</script>

<style>
    .left {
        float: left;
        margin-left: 1in;
        margin-right: auto;
    }
    .right {
        float: right;
        margin-left: 1in;
        margin-right: auto;
    }
</style>