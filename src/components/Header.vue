<template>

  <header>
    <span class="iconify" data-icon="twemoji:woman-singer-dark-skin-tone" data-inline="false"></span>
    <h1>わたしのりれき</h1>
  </header>
</template>
<style lang="scss" scoped>
  @import "@/assets/sass/_mixin";

header {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  z-index: 2;
  text-align: center;
  background-color: #D9ECFF;
  padding: 2.4rem 1.6rem 4rem;

  h1 {
    text-transform: uppercase;

  }
  .iconify {
    display: block;
    font-size: 6rem;
    margin: 0 auto;
  }
          @include mq(xl) {
  padding: 4rem 1.6rem 6rem;

  .iconify {
    font-size: 8rem;
  }

      }

}

</style>