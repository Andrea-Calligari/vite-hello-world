<script>
export default{
  data(){
    return{
      message: 'La mia prima app con Vite!!!!'
      
    }
  }
}
</script>

<template>
  <figure>
    <img src="https://th.bing.com/th/id/R.a19c5b93d037fb0bd0600c6e1603765d?rik=QrMkvf6AkoWsCA&pid=ImgRaw&r=0" alt="Surfer on a wave">
    <figcaption>KAWABOOOOOOOONGAAA!</figcaption>
  </figure>

</template>

<style>
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
img {
  width: 100%;
}
figure{
  position: relative;
}
figcaption{
  font-size: 70px;
  position: absolute;
  top: 70%;
  left: 50%;
  transform: translate(-50%, -50%);
}


</style>