<template>
  <section class="author">
    <article class="item">
      <h1 class="logo">
        <img src="../assets/images/logo.png" alt="LOGO">
      </h1>
    </article>
    <article class="text">
      <p>
        我叫曹鑫，职业是一名前端工程师，这个博客属于我的个人博客网站，同时也在 <a href="https://github.com/Cvitas/nodejs-koa-blog" target="_blank"></a>
      </p>
    </article>
    <article class="end">
      <p>最后，祝大家每天开心，每天幸福！</p>
    </article>
  </section>
</template>

<style scoped lang="less">
  .author {
    box-sizing: border-box;
    width: @window-Width;
    min-height: 80vh;
    margin: 24px auto;
    overflow: hidden;
    padding-bottom: 24px;
    background-color: #fff;
    border-radius: 6px;
  }

  .item {
    width: 100%;
    padding: 48px 0;
    text-align: center;
    background: white;
  }

  .logo {
    width: 320px;
    margin: 32px auto 0;

    & img {
      width: 100%;
    }
  }

  a {
    color: #409EFF;
  }

  .text {
    padding: 0 32px 32px;
    line-height: 42px;
    font-size: 20px;
    color: #666;
    text-indent: 2em;
  }

  .content {
    padding-top: 32px;
  }

  .end {
    line-height: 42px;
    font-size: 20px;
    color: #666;
    text-indent: 2em;
  }

  @media screen and (min-width: 200px) and (max-width: 750px) {
    .author {
      width: 100%;
    }
  }
</style>
