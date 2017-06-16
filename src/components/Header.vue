<template>
  <div class="container">
    <div class="left">
      <div class="menu-icon">
        <svg viewBox="0 0 24 24"><path d="M3 18h18v-2H3v2zm0-5h18v-2H3v2zm0-7v2h18V6H3z"></path></svg>
      </div>
      <div class="header-title">
        <div class="inner">
          <a href=""><span class="text">Keep</span></a>
        </div>
      </div>
    </div>
    <div class="right"></div>
  </div>
</template>

<style lang="scss" scoped>
  .container {
    display: flex;
    background-color: #ffbb00;
    padding: 4px;
  }

  .left {
    display: flex;
    align-items: center;
    flex: 1 0 auto;
    height: 48px;

    .menu-icon {
      display: inline-block;
      height: 24px;
      width: 24px;
      padding: 12px;
      margin: 0 4px 0 0;
    }

    .header-title {
      display: inline-block;

      .inner {
        padding-left: 16px;

        a {
          display: inline-block;
        }

        .text {
          font-size: 22px;
          display: inline-block;
          line-height: 24px;
          padding-left: 8px;
          text-rendering: optimizeLegibility;
          -webkit-font-smoothing: antialiased;
          color: #000;
          position: relative;
          top: .5px;
        }
      }
    }
  }

  .right {
    flex: 1 1 100%;
    height: 48px;
    display: flex;
    justify-content: flex-end;
  }
</style>
