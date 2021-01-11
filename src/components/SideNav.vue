<template>
  <!-- <el-menu> -->
  <div class="side-nav">
    <li class="side-nav__list">
      <a class="side-nav__item" href="#bakutan">
        <div class="icon-area">
          <span class="iconify" data-icon="twemoji:baby" data-inline="false"></span>
        </div>
        <p class="mb-none">爆誕</p>
      </a>
    </li>

    <li class="side-nav__list">
      <a class="side-nav__item" href="#kids">
        <div class="icon-area">
          <span class="iconify" data-icon="twemoji:name-badge" data-inline="false"></span>
        </div>
        <p class="mb-none">保育園</p>
      </a>
    </li>

    <li class="side-nav__list">
      <a class="side-nav__item" href="#elementary">
        <div class="icon-area">
          <span class="iconify" data-icon="twemoji:child-medium-skin-tone" data-inline="false"></span>
        </div>
        <p class="mb-none">小学校</p>
      </a>
    </li>

    <li class="side-nav__list">
      <a class="side-nav__item" href="#jhs">
        <div class="icon-area">
          <span class="iconify" data-icon="twemoji:alien" data-inline="false"></span>
        </div>
        <p class="mb-none">中学校</p>
      </a>
    </li>

    <li class="side-nav__list">
      <a class="side-nav__item" href="#hs">
        <div class="icon-area">
          <span class="iconify" data-icon="twemoji:artist-palette" data-inline="false"></span>
        </div>
        <p class="mb-none">高校</p>
      </a>
    </li>

    <li class="side-nav__list">
      <a class="side-nav__item" href="#gap">
        <div class="icon-area">
          <span class="iconify" data-icon="twemoji:alien-monster" data-inline="false"></span>
        </div>
        <p class="mb-none">モラトリアム</p>
      </a>
    </li>

    <li class="side-nav__list">
      <a class="side-nav__item" href="#college">
        <div class="icon-area">
          <span class="iconify" data-icon="twemoji:graduation-cap" data-inline="false"></span>
        </div>
        <p class="mb-none">大学</p>
      </a>
    </li>

    <li class="side-nav__list">
      <a class="side-nav__item" href="#tokyo">
        <div class="icon-area">
          <span class="iconify" data-icon="twemoji:tokyo-tower" data-inline="false"></span>
        </div>
        <p class="mb-none">上京</p>
      </a>
    </li>

    <li class="side-nav__list">
      <a class="side-nav__item" href="#job-change">
        <div class="icon-area">
          <span class="iconify" data-icon="twemoji:man-biking-medium-skin-tone" data-inline="false"></span>
        </div>
        <p class="mb-none">はじめての転職</p>
      </a>
    </li>

    <li class="side-nav__list">
      <a class="side-nav__item" href="#current">
        <div class="icon-area">
          <span class="iconify" data-icon="twemoji:woman-technologist-medium-skin-tone" data-inline="false"></span>
        </div>
        <p class="mb-none">なう</p>
      </a>
    </li>

  </div>

  <!-- </el-menu> -->
</template>
<style lang="scss">
  @import "@/assets/sass/_mixin";

  .side-nav {
    text-align: left;
    margin-top: 6rem;
    padding-left: 2rem;
    
    @include mq(lg) {
      padding-left: 12rem;
    }

    &__list {
      max-width: 12rem;
      list-style: none;
      margin-bottom: 0.4rem;
    }

    &__item {
      color: #409EFF;
      text-align: left;
      display: flex;
      justify-content: flex-start;
      align-items: center;
      text-decoration: none;
      -webkit-tap-highlight-color: transparent;

      p {
        font-size: 1rem;

        @include mq(xl) {
          font-size: 1.2rem;
        }

      }

      &:hover {
        opacity: .6;
      }

      @include mq(xl) {
        &:hover {
          background-color: #ECF8FE;
        }
      }
    }

    .icon-area {
      width: 4rem;
      height: 4rem;
      display: flex;
      justify-content: center;
      align-items: center;

      .iconify {
        font-size: 2.4rem;
      }

      &:hover {
        background-color: #ECF8FE;
      }
    }

    .mb-none {
      display: none;

      @include mq(xl) {
        display: inline-block;
      }
    }
  }
</style>

<script>
</script>