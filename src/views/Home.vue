<template>
  <div id="home">
      <Header />

<el-container style="height: 900px;" class="wrapper">
          <SideNav />
    <el-container>
      <el-main>
        <Timeline />
      </el-main>
    </el-container>
    </el-container>

    <el-footer>
      &copy; 2020 marigotten<a target="_blank" href="https://github.com/marigotten"><span class="iconify" data-icon="brandico:github" data-inline="false"></span></a>
    </el-footer>
  </div>
</template>

<script>
  import Header from '@/components/Header'
  import SideNav from '@/components/SideNav'
  import Timeline from '@/components/Timeline'

  export default {
    name: 'Home',
    components: {
      Header,
      SideNav,
      Timeline
    }
  }
</script>
<style lang="scss" scoped>
  @import "@/assets/sass/_mixin";

  #home {
    .wrapper {
padding-top: 16rem; 
      @include mq(lg) {
        padding-top: 24rem;
      }
    }

    .side {
      width: 3.6rem;
      @include mq(xl) {
        width: 24%;
      }

    }

    .main {
      margin-left: 6rem;

      @include mq(xl) {
        margin-left: 12rem;
      }
    }
  }

  footer {
    position: sticky;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: #f8f9fa;
    text-align: center;
    font-size: 1.2rem;
    line-height: 60px;
  }

  svg[data-icon="brandico:github"] {
    color: #555;
    font-size: 1.2rem;
    margin-left: 2rem;
    vertical-align: -0.2rem;

    &:hover {
      opacity: .6;
    }
  }

  img {
    width: 100%;
  }
</style>