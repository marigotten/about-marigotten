<template>
  <div id="home">
    <Header />
    <el-container class="wrapper">

      <el-main>
        <el-col :xs="4" :md="6" class="side">
          <SideNav />
        </el-col>

        <el-col :xs="20" :md="18" class="main">
          <Timeline />
        </el-col>

      </el-main>

    </el-container>
    <el-footer>
&copy; 2020 mari goto<a href=""><span class="iconify" data-icon="brandico:github" data-inline="false"></span></a></el-footer>
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
      position: relative;
      margin-top: 20rem;
      padding-top: -20rem;

    }

    .side {
      position: fixed;
      top: 0;
      left: 0;
      padding-top: 16rem;

      @include mq(lg) {
        margin-left: 12rem;
      }

    }

    .main {
      margin-left: 6rem;

      @include mq(lg) {
        margin-left: 12rem;
      }
    }
  }

  footer {
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

</style>