<template>
  <div>
     <img :src="images.i1" id="left" />
     <img :src="images.i1" id="right" />
     <img :src="images.i1" id="right" />
     <img :src="images.i1" id="right" />
     <img :src="images.i1" id="right" />
     <img :src="images.i1" id="right" />
     <img :src="images.i1" id="right" />
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
    }
    .right {
        float:right
    }

</style>