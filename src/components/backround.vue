<template lang="">
    <div class="video-bg">
        <video width="320" height="240" autoplay loop muted>
         <source src="@/assets/images/background.mp4" type="video/mp4">
       Your browser does not support the video tag.
       </video>
    </div>
</template>
<script>
export default {
  name: "backround",
};
</script>
<style lang="scss">
.video-bg {
  position: fixed;
  right: 0;
  top: 0;
  width: 100%;
  height: 100%;
  z-index: -100;
}
.video-bg video {
  width: 100%;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
  z-index: -100;
}
</style>