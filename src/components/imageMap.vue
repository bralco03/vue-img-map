<template>
  <div class="container">
    <img
      alt="img"
      height="500"
      width="481"
      src="../assets/eggImg.jpg"
      usemap="#workmap" />
    <map name="workmap">
      <area shape="rect" coords="0,0,100,100" alt="egg" :href="eggRef" />
    </map>
  </div>
</template>

<script>
export default {
  name: 'imageMap',
  data() {
    const eggRef =
      'https://www.google.com.mx/search?q=egg&hl=es-419&tbm=isch&sxsrf=ALiCzsY-QvtLn0-9yaGWMYMvypme8yYU9g%3A1657692064361&source=hp&biw=1366&bih=649&ei=oF_OYp6SEO6ekPIPsPqekAs&iflsig=AJiK0e8AAAAAYs5tsC1P6NQQdYIXF8VnbHl10-M-wXlf&ved=0ahUKEwie4oyVmPX4AhVuD0QIHTC9B7IQ4dUDCAc&uact=5&oq=egg&gs_lcp=CgNpbWcQA1AMWK4BYPkBaABwAHgAgAEAiAEAkgEAmAEAoAEBqgELZ3dzLXdpei1pbWewAQA&sclient=img';
    return {eggRef};
  }
};
</script>

<style scoped>
.container {
  height: 100%;
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
area:hover {
  cursor: pointer;
}
</style>
