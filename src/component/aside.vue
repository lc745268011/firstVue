<template>
  <aside data-v-25222c36="" data-v-02462315="" st:block="sidebar" class="welcome__side welcome__side"
         data-v-3f216172="">
    <section data-v-c1cc7ad0="" data-v-25222c36="" st:block="register" class="shadow section auth-section">
      <div data-v-c1cc7ad0="" class="title">
        掘金 - juejin.im
      </div>
      <div data-v-c1cc7ad0="" class="slogan">
        一个帮助开发者成长的社区
      </div>
      <div data-v-c1cc7ad0="" class="input-group">
        <div data-v-c1cc7ad0="" class="input-box">
          <input data-v-c1cc7ad0="" name="registerUsername" maxlength="20" placeholder="昵称" class="input" id="name" v-model="name"/>
        </div>
        <div data-v-c1cc7ad0="" class="input-box">
          <input data-v-c1cc7ad0="" name="registerPhoneOrEmail1" maxlength="64" placeholder="邮箱 / 手机" class="input" id="phone" v-model="phone"/>
        </div>
        <!---->
        <!---->
        <div data-v-c1cc7ad0="" class="input-box">
          <input data-v-c1cc7ad0="" name="registerPassword" type="password" maxlength="64" autocomplete="new-password"
                 placeholder="密码（不少于 6 位）" class="input" id="password1" v-model="password1"/>
        </div>
      </div>
      <button data-v-c1cc7ad0="" st:name="registerBtn" class="btn submit-btn" @click="register">立即注册</button>
      <div data-v-c1cc7ad0="" class="oauth-box">
        第三方登录：
        <img data-v-c1cc7ad0="" st:name="oauthBtn" st:state="weibo" title="微博" alt="微博"
             src="https://gold-cdn.xitu.io/v3/static/img/weibo.fa758eb.svg" class="oauth-btn"/>
        <img data-v-c1cc7ad0="" st:name="oauthBtn" st:state="github" title="GitHub" alt="GitHub"
             src="https://gold-cdn.xitu.io/v3/static/img/github.547dd8a.svg" class="oauth-btn"/>
        <img data-v-c1cc7ad0="" st:name="oauthBtn" st:state="wechat" title="微信" alt="微信"
             src="https://gold-cdn.xitu.io/v3/static/img/wechat.e0ff124.svg" class="oauth-btn"/>
      </div>
    </section>
    <div data-v-59ba9598="" data-v-26a2d138="" data-v-25222c36="" class="section shadow tags" st:block="tagList">
      <div data-v-59ba9598="" class="header">
        <div data-v-59ba9598="" class="title">
          <span data-v-26a2d138="" data-v-59ba9598="">热门标签</span>
        </div>
        <div data-v-59ba9598="" class="right">
          <a data-v-26a2d138="" href="/subscribe/all" target="_blank" rel="" st:name="allLink" class="tag-link"
             data-v-59ba9598="">查看全部</a>
        </div>
      </div>
      <div data-v-59ba9598="" class="content">
        <div data-v-26a2d138="" data-v-59ba9598="" class="tag-list">
          <a data-v-26a2d138="" href="/tag/%E6%9E%B6%E6%9E%84" target="_blank" rel="" st:name="tagLink" st:state="架构"
             class="tag" data-v-59ba9598="">架构</a>
          <a data-v-26a2d138="" href="/tag/%E5%BC%80%E6%BA%90" target="_blank" rel="" st:name="tagLink" st:state="开源"
             class="tag" data-v-59ba9598="">开源</a>
          <a data-v-26a2d138="" href="/tag/%E7%AE%97%E6%B3%95" target="_blank" rel="" st:name="tagLink" st:state="算法"
             class="tag" data-v-59ba9598="">算法</a>
          <a data-v-26a2d138="" href="/tag/GitHub" target="_blank" rel="" st:name="tagLink" st:state="GitHub"
             class="tag" data-v-59ba9598="">GitHub</a>
          <a data-v-26a2d138="" href="/tag/%E9%9D%A2%E8%AF%95" target="_blank" rel="" st:name="tagLink" st:state="面试"
             class="tag" data-v-59ba9598="">面试</a>
          <a data-v-26a2d138="" href="/tag/%E4%BB%A3%E7%A0%81%E8%A7%84%E8%8C%83" target="_blank" rel=""
             st:name="tagLink" st:state="代码规范" class="tag" data-v-59ba9598="">代码规范</a>
          <a data-v-26a2d138="" href="/tag/%E4%BA%A7%E5%93%81" target="_blank" rel="" st:name="tagLink" st:state="产品"
             class="tag" data-v-59ba9598="">产品</a>
          <a data-v-26a2d138="" href="/tag/%E6%8E%98%E9%87%91%E7%BF%BB%E8%AF%91%E8%AE%A1%E5%88%92" target="_blank"
             rel="" st:name="tagLink" st:state="掘金翻译计划" class="tag" data-v-59ba9598="">掘金翻译计划</a>
        </div>
      </div>
    </div>
    <div data-v-151dc5e1="" data-v-25222c36="" class="app-download shadow section">
      <div data-v-151dc5e1="" class="qr-box">
        <img data-v-151dc5e1="" src="https://gold-cdn.xitu.io/v3/static/img/welcome.6f27533.png" class="qr-img"/>
      </div>
      <div data-v-151dc5e1="" class="app-info">
        <span data-v-151dc5e1="" class="headline">下载掘金客户端</span>
        <span data-v-151dc5e1="" class="desc">一个帮助开发者成长的社区</span>
      </div>
      <a data-v-151dc5e1="" class="link" href="https://juejin.im/app" target="_blank"></a>
    </div>
    <section data-v-56380f68="" data-v-25222c36="" st:block="link" class="shadow section link-section section">
      <ul data-v-56380f68="" class="link-list">
        <li data-v-56380f68="" class="item"><a data-v-56380f68="" st:name="collectionsLink" class="link"
                                               href="/collections/recommended" target="_blank"><img data-v-56380f68=""
                                                                                                    src="https://gold-cdn.xitu.io/v3/static/img/collections.945b9ae.png"
                                                                                                    class="icon"/><span
          data-v-56380f68="" class="title">收藏集</span></a></li>
        <li data-v-56380f68="" class="item"><a data-v-56380f68="" st:name="extensionLink" class="link" href="/extension"
                                               target="_blank"><img data-v-56380f68=""
                                                                    src="https://gold-cdn.xitu.io/v3/static/img/juejin-extension-icon.4b79fb4.png"
                                                                    class="icon"/><span data-v-56380f68=""
                                                                                        class="title">下载掘金浏览器插件</span></a>
        </li>
        <li data-v-56380f68="" class="item"><a data-v-56380f68="" st:name="minerLink" class="link"
                                               href="https://github.com/xitu/gold-miner"
                                               rel="nofollow noopener noreferrer" target="_blank"><img
          data-v-56380f68="" src="https://gold-cdn.xitu.io/v3/static/img/juejin-miner.b78347c.png" class="icon"/><span
          data-v-56380f68="" class="title">前往掘金翻译计划</span></a></li>
        <li data-v-56380f68="" class="item"><a data-v-56380f68="" st:name="bdLink" class="link"
                                               href="https://bd.juejin.im?utm_campaign=bd&amp;utm_source=web&amp;utm_medium=link"
                                               target="_blank"><img data-v-56380f68=""
                                                                    src="https://gold-cdn.xitu.io/v3/static/img/juejin-partner.4dd2d8c.png"
                                                                    class="icon"/><span data-v-56380f68=""
                                                                                        class="title">商务合作</span></a>
        </li>
      </ul>
    </section>
    <div data-v-c929dee6="" data-v-25222c36="" class="banner section shadow banner-section">
      <a data-v-c929dee6=""
         href="http://2018.qconbeijing.com/?utm_source=juejin&amp;utm_campaign=8&amp;utm_medium=banner&amp;utm_term=0226"
         rel="nofollow noopener noreferrer" target="_blank">
        <div data-v-b2db8566="" data-v-009ea7bb="" data-v-c929dee6=""
             data-src="https://user-gold-cdn.xitu.io/151956947453595fdd4d6b721ea4dcd2597959aca05d6.jpg?imageView2/1/q/85/format/webp/interlace/1"
             class="lazy thumb banner-image loaded"
             style="background-image: url(&quot;https://user-gold-cdn.xitu.io/151956947453595fdd4d6b721ea4dcd2597959aca05d6.jpg?imageView2/1/q/85/format/webp/interlace/1&quot;); background-size: cover;"></div>
      </a>

      <div data-v-c929dee6="" class="ctrl-box">
        <i data-v-c929dee6="" class="ion-close-round close-btn"></i>
        <a data-v-c929dee6="" class="label"
           href="https://bd.juejin.im?utm_campaign=bd&amp;utm_source=web&amp;utm_medium=banner" target="_blank"><span
          data-v-c929dee6="" class="inco">投放</span><span data-v-c929dee6="">广告</span></a>
      </div>
    </div>
    <div data-v-37ee4f90="" data-v-25222c36="" st:block="follow" class="follow-section">
      <header data-v-37ee4f90="" class="header">
        关注我们
      </header>
      <ul data-v-37ee4f90="" class="account-list">
        <li data-v-37ee4f90="" st:name="weiboBtn" class="item weibo"><a data-v-37ee4f90=""
                                                                        href="http://weibo.com/xitucircle"
                                                                        rel="nofollow noopener noreferrer"
                                                                        target="_blank"><img data-v-37ee4f90=""
                                                                                             src="https://gold-cdn.xitu.io/v3/static/img/weibo.0cd39f5.png"
                                                                                             alt="微博" class="icon"/></a>
        </li>
        <li data-v-37ee4f90="" st:name="wechatBtn" class="item wechat"><img data-v-37ee4f90=""
                                                                            src="https://gold-cdn.xitu.io/v3/static/img/wechat.ce329e6.png"
                                                                            alt="微信" class="icon"/>

          <div data-v-37ee4f90="" class="qr-panel">
            <div data-v-37ee4f90="" class="title">
              微信扫一扫
            </div>
            <img data-v-37ee4f90="" src="https://gold-cdn.xitu.io/v3/static/img/xitucircle-qr.0bfaeef.jpg" class="qr"/>
          </div>
        </li>
        <li data-v-37ee4f90="" st:name="zhihuBtn" class="item zhihu"><a data-v-37ee4f90=""
                                                                        href="https://zhuanlan.zhihu.com/xitucircle"
                                                                        rel="nofollow noopener noreferrer"
                                                                        target="_blank"><img data-v-37ee4f90=""
                                                                                             src="https://gold-cdn.xitu.io/v3/static/img/zhuanlan.18265c6.png"
                                                                                             alt="知乎" class="icon"/></a>
        </li>
        <li data-v-37ee4f90="" st:name="jianshuBtn" class="item jianshu"><a data-v-37ee4f90=""
                                                                            href="http://www.jianshu.com/users/5fc9b6410f4f/latest_articles"
                                                                            rel="nofollow noopener noreferrer"
                                                                            target="_blank"><img data-v-37ee4f90=""
                                                                                                 src="https://gold-cdn.xitu.io/v3/static/img/jianshu.80c1fdd.png"
                                                                                                 alt="简书" class="icon"/></a>
        </li>
      </ul>
    </div>
    <section data-v-360336b8="" data-v-25222c36="" st:block="more" class="more-section">
      <ul data-v-360336b8="" class="more-list">
        <li data-v-360336b8="" class="item"><a data-v-360336b8="" st:name="aboutLink" href="/about"
                                               target="_blank">关于</a></li>
        <li data-v-360336b8="" class="item"><a data-v-360336b8="" st:name="jobLink" href="https://xitu.io/jobs"
                                               target="_blank">招聘</a></li>
        <li data-v-360336b8="" class="item"><a data-v-360336b8="" st:name="bdLink"
                                               href="https://bd.juejin.im?utm_campaign=bd&amp;utm_source=web&amp;utm_medium=more"
                                               target="_blank">商务合作</a></li>
        <li data-v-360336b8="" class="item"><a data-v-360336b8="" st:name="linksLink" href="/links"
                                               target="_blank">友情链接</a></li>
      </ul>
      <ul data-v-360336b8="" class="more-list">
        <li data-v-360336b8="" class="item"><a data-v-360336b8="" st:name="exploreLink" href="/explore/all"
                                               target="_blank">发现更多</a></li>
        <li data-v-360336b8="" class="item"><span data-v-360336b8="">&copy;2018 掘金</span></li>
      </ul>
    </section>
    <div data-v-25222c36="" class="sticky-section">
      <div data-v-c929dee6="" data-v-25222c36="" class="banner section shadow banner-section">
        <a data-v-c929dee6=""
           href="http://2018.qconbeijing.com/?utm_source=juejin&amp;utm_campaign=8&amp;utm_medium=banner&amp;utm_term=0226"
           rel="nofollow noopener noreferrer" target="_blank">
          <div data-v-b2db8566="" data-v-009ea7bb="" data-v-c929dee6=""
               data-src="https://user-gold-cdn.xitu.io/151956947453595fdd4d6b721ea4dcd2597959aca05d6.jpg?imageView2/1/q/85/format/webp/interlace/1"
               class="lazy thumb banner-image loaded"
               style="background-image: url(&quot;https://user-gold-cdn.xitu.io/151956947453595fdd4d6b721ea4dcd2597959aca05d6.jpg?imageView2/1/q/85/format/webp/interlace/1&quot;); background-size: cover;"></div>
        </a>

        <div data-v-c929dee6="" class="ctrl-box">
          <i data-v-c929dee6="" class="ion-close-round close-btn"></i>
          <a data-v-c929dee6="" class="label"
             href="https://bd.juejin.im?utm_campaign=bd&amp;utm_source=web&amp;utm_medium=banner" target="_blank"><span
            data-v-c929dee6="" class="inco">投放</span><span data-v-c929dee6="">广告</span></a>
        </div>
      </div>
      <div data-v-151dc5e1="" data-v-25222c36="" class="app-download shadow section">
        <div data-v-151dc5e1="" class="qr-box">
          <img data-v-151dc5e1="" src="https://gold-cdn.xitu.io/v3/static/img/welcome.6f27533.png" class="qr-img"/>
        </div>
        <div data-v-151dc5e1="" class="app-info">
          <span data-v-151dc5e1="" class="headline">下载掘金客户端</span>
          <span data-v-151dc5e1="" class="desc">一个帮助开发者成长的社区</span>
        </div>
        <a data-v-151dc5e1="" class="link" href="https://juejin.im/app" target="_blank"></a>
      </div>
    </div>
  </aside>
</template>

<script type="text/javascript">
  export default {
    data ()
  {
    return {
    	name:'',
    	phone:'',
    	password1:''
    }
  },
  methods:{
  	register(){
  		if(this.name==""||this.phone==""||this.password1==""){
        this.$notify.error({
           title: '错误',
          message: '请完整填写各项！'
        });
  		}
  	}
  }
  }
</script>

