<template>
  <h1 id="lol">MEMES FOR THE WIN</h1>
</template>

<script>

  const sleep = (delay) => new Promise((resolve) => setTimeout(resolve, delay));

  async function hi() {
    const func = async () => {
      while(true) {
        await sleep(1);
        document.getElementById("lol").innerHTML = "M3MES";
        await sleep(1);
        document.getElementById("lol").innerHTML = "MEM3S";
        await sleep(1)
        document.getElementById("lol").innerHTML = "MEMES";
      }
    }
    func();   
  }
hi();
</script>

<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap');
    h1 {
        color: white;
        font-family: 'Press Start 2P';
        text-align: center;
        margin-top: 3in;
        font-size: 70px;
    }
</style>