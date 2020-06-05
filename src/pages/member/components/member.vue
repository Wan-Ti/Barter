<template>
  <div class="container" style="min-height: 581px;">
    <div class="content">
      <div class="user-infos">
        <div class="pull-left avatar">
          <div
            class="img"
            style="background-image: url(https://img.yzcdn.cn/upload_files/no_pic.png?imageView2/2/w/280/h/280/q/75/format/webp);"
          ></div>
        </div>
        <div class="pull-left desc">
          <p>党宁</p>
        </div>
      </div>
      <div class="order-related">
        <ul class="uc-order list-horizon clearfix js-order-overview">
          <li>
            <a
              class="link clearfix relative link-topay"
              data-for="topay"
              href="https://h5.youzan.com/v2/trade/record/alllist?type=topay"
              target="_blank"
            >
              <p class="title-info c-black font-size-12">待交换</p>
            </a>
          </li>
          <li>
            <a
              class="link clearfix relative link-tosend"
              data-for="tosend"
              href="https://h5.youzan.com/v2/trade/record/alllist?type=tosend"
              target="_blank"
            >
              <p class="title-info c-black font-size-12">待发货</p>
            </a>
          </li>
          <li>
            <a
              class="link clearfix relative link-send"
              data-for="send"
              href="https://h5.youzan.com/v2/trade/record/alllist?type=send"
              target="_blank"
            >
              <p class="title-info c-black font-size-12">待收货</p>
            </a>
          </li>
          <li>
            <a
              class="link clearfix relative link-rights"
              href="https://h5.youzan.com/v2/trade/record/rightsOrder"
              target="_blank"
            >
              <p class="title-info c-black font-size-12">退货/维权</p>
            </a>
          </li>
        </ul>
        <div class="block block-list list-vertical">
          <a
            class="block-item link clearfix ico-order"
            href="https://h5.youzan.com/v2/trade/record/alllist?type=all"
            target="_blank"
          >
            <p class="title-info c-black font-size-14">全部订单</p>
          </a>
        </div>
        <div class="block block-list list-vertical">
          <a class="block-item link clearfix ico-favior js-login" href="cart.html" target="_blank">
            <p class="title-info c-black font-size-14">收藏的商品</p>
          </a>
          <a
            class="block-item link clearfix ico-shop js-login"
            href="https://maijia.youzan.com/mars/collect/shop"
            target="_blank"
          >
            <p class="title-info c-black font-size-14">收藏的卖家</p>
          </a>
          <a
            class="block-item link clearfix ico-bought js-login"
            href="https://maijia.youzan.com/mars/record/bought"
            target="_blank"
          >
            <p class="title-info c-black font-size-14">我买过的</p>
          </a>
          <a
            class="block-item link clearfix ico-history js-login"
            href="https://maijia.youzan.com/mars/record/goodsbrowse"
            target="_blank"
          >
            <p class="title-info c-black font-size-14">我的浏览记录</p>
          </a>
        </div>
        <div class="block block-list list-vertical">
          <router-link class="block-item link clearfix ico-setting js-login" to="/address">
            <p class="title-info c-black font-size-14">收货地址管理</p>
          </router-link>
          <a
            class="block-item link clearfix ico-help"
            href="https://wan-ti.github.io/Vue-Chat/"
            target="_blank"
          >
            <p class="title-info c-black font-size-14">联系易物客服</p>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
@import "./member_base.css";
@import "./member.css";
</style>
