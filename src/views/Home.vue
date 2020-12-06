<template>
  <div id="home">
    <Header />
    <el-container class="wrapper">  
    <el-main>
      <el-row>
        <el-col :xs="4" :lg="6" class="side">
    <SideNav />
        </el-col>
        <el-col :xs="20" :lg="18" class="main">
    <Timeline />
        </el-col>
      </el-row>
    </el-main>
    </el-container>
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
      /* margin-left: 12rem; */
  }

  }
  .main {
    padding-left: 6rem;
            @include mq(lg) {
      padding-left: 12rem;
  }
  }
    }
</style>