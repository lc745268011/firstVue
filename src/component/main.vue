<template>
  <div data-v-2440c1eb="" data-v-02462315="" class="feed welcome__feed" data-v-3f216172="">
    <nav data-v-1add119e="" data-v-2440c1eb="" class="category-nav"><h5 data-v-1add119e="">热门文章</h5>

      <div data-v-1add119e="" class="more">查看更多</div>
      <ul data-v-1add119e="" class="nav-list">
        <li data-v-1add119e="" class="nav-item" @click="home"><router-link :to="{name:'home'}"><span data-v-1add119e="" class="title">推荐</span></router-link></li>
        <li data-v-1add119e="" class="nav-item" v-for="(n,index) in navs"><router-link :to="{name:'list',params:{id:n.nav}}"><span data-v-1add119e="" class="title">{{n.name}}</span></router-link></li>
      </ul>
    </nav>
    <ul data-v-f0edcf22="" data-v-2440c1eb="" st:block="entryList" class="entry-list"><!---->
      <li data-v-f0edcf22="" class="item" v-for="l in lists">
        <div data-v-9f3d7718="" data-v-f0edcf22="" class="entry-box">
          <div data-v-6b46a625="" data-v-9f3d7718="" st:block="entry" st:state="5a936ca65188257a63113170|1"
               class="entry"><a data-v-6b46a625="" href="/post/5a936c5a6fb9a0633229ca74" target="_blank" rel=""
                                st:name="link" class="entry-link">
            <div data-v-6b46a625="" class="content-box">
              <div data-v-6b46a625="" class="info-box">
                <div data-v-6b46a625="" class="info-row meta-row">
                  <ul data-v-6b46a625="" class="meta-list"><!----><!---->
                    <li data-v-6b46a625="" class="item post">专栏</li>
                    <li data-v-6b46a625="" class="item username clickable">
                      <div data-v-311d2efa="" data-v-6b46a625="" st:block="userPopover"
                           st:state="5886d699128fe1006c455fb6" class="user-popover-box"><!----><a data-v-6b46a625=""
                                                                                                  href="/user/5886d699128fe1006c455fb6"
                                                                                                  target="_blank" rel=""
                                                                                                  st:name="user"
                                                                                                  st:state="5886d699128fe1006c455fb6"
                                                                                                  data-v-311d2efa="">{{l.user.username}}</a>
                      </div>
                    </li>
                    <li data-v-6b46a625="" class="item">4小时前</li>
                    <li data-v-6b46a625="" class="item tag"><a href="/tag/Android" target="_blank" rel="" class="tag"></a></li>
                    <!----></ul>
                </div>
                <div data-v-6b46a625="" class="info-row title-row"><!----><!----><a data-v-6b46a625=""
                                                                                    href="/post/5a936c5a6fb9a0633229ca74"
                                                                                    target="_blank" rel=""
                                                                                    st:name="title" class="title">{{l.title}}</a></div>
                <div data-v-6b46a625="" class="info-row action-row">
                  <ul data-v-6b46a625="" class="action-list">
                    <li data-v-6b46a625="" st:name="likeBtn" class="item like clickable"><a data-v-6b46a625=""
                                                                                            class="title-box"><img
                      data-v-6b46a625="" src="https://gold-cdn.xitu.io/v3/static/img/like.4bf00fb.svg"
                      class="icon"><span data-v-6b46a625="" class="count">{{l.collectionCount}}</span></a></li>
                    <li data-v-6b46a625="" st:name="commentBtn" class="item comment clickable"><a data-v-6b46a625=""
                                                                                                  href="/post/5a936c5a6fb9a0633229ca74#comment"
                                                                                                  target="_blank" rel=""
                                                                                                  class="title-box"><img
                      data-v-6b46a625="" src="https://gold-cdn.xitu.io/v3/static/img/comment.4d5744f.svg" class="icon"><span data-v-6b46a625="" class="count">{{l.commentsCount}}</span><!---->
                    </a></li>
                    <li data-v-6b46a625="" st:name="shareBtn" title="分享" class="item share clickable hover"><img
                      data-v-6b46a625="" src="https://gold-cdn.xitu.io/v3/static/img/share.1d55e69.svg" class="icon">

                      <div data-v-6b46a625="" class="share-panel">
                        <div data-v-6b46a625="" st:name="shareItem" st:state="weibo" class="share-item weibo"><img
                          data-v-6b46a625="" src="https://gold-cdn.xitu.io/v3/static/img/weibo.8e2f5d6.svg"
                          class="icon">微博
                        </div>
                        <div data-v-6b46a625="" st:name="shareItem" st:state="wechat" class="share-item wechat"><img
                          data-v-6b46a625="" src="https://gold-cdn.xitu.io/v3/static/img/wechat.844402c.svg"
                          class="icon">微信扫一扫
                          <div data-v-6b46a625="" class="qr-code-box"><img data-v-6b46a625="" src="" class="qr-code">
                          </div>
                        </div>
                      </div>
                    </li>
                    <li data-v-6b46a625="" title="收藏" st:name="collectBtn" class="item collect clickable hover"><img
                      data-v-6b46a625="" src="https://gold-cdn.xitu.io/v3/static/img/collect.4456392.svg" class="icon"><!---->
                    </li>
                    <!----></ul>
                </div>
              </div>
              <div data-v-b2db8566="" data-v-009ea7bb="" data-v-6b46a625=""
                   data-src="https://user-gold-cdn.xitu.io/2018/2/26/161cfdfc5388fca2?imageView2/1/w/120/h/120/q/85/format/webp/interlace/1"
                   class="lazy thumb thumb loaded"
                   style="background-image: url(&quot;https://user-gold-cdn.xitu.io/2018/2/26/161cfdfc5388fca2?imageView2/1/w/120/h/120/q/85/format/webp/interlace/1&quot;); background-size: cover;"></div>
            </div>
          </a></div>
        </div>
      </li>
      <!----></ul>
  </div>
</template>
<script src="https://unpkg.com/axios/dist/axios.min.js"></script>
<script type="text/javascript">
  export default {
    data ()
  {
    return {
      navs:[{
        name:'前端',
        nav:'frontend'
      },{
        name:'Android',
        nav:'android'
      },{
        name:'后端',
        nav:'backend'
      },{
        name:'人工智能',
        nav:'ai'
      },{
        name:'iOS',
        nav:'ios'
      },{
        name:'工具资源',
        nav:'freebie'
      },{
        name:'阅读',
        nav:'article'
      }],
      lists:[],
      tags:[]
    }
  },
  created:function(){
  },
  methods:{
    home(){
      this.$http.get('/api/aaa.json').then(response => {
        // success callback
      this.lists=response.data.d.entrylist;
      }, response => {
        // error callback
      })

  }
  },
  }
</script>

