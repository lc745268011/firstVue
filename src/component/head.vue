<template>
	<div id="head">
		<div id="header">
			<div class="container">
				<div id="logo">
					<img src="https://gold-cdn.xitu.io/v3/static/img/logo.a7995ad.svg" alt="" />
				</div>
				<div class="main-nav">
					<ul class="nav-list">
						<li>
							<ul id="nav">
								<li class="nav-item">
									<a href="">首页</a>
								</li>
								<li class="nav-item">
									<a href="">首页</a>
								</li>
								<li class="nav-item">
									<a href="">首页</a>
								</li>
								<li class="nav-item">
									<a href="">首页</a>
								</li>
							</ul>
						</li>
						<li id="search" class="nav-item">
							<form action="" class="search-form">
								<input type="text" />
								<img src="https://gold-cdn.xitu.io/v3/static/img/juejin-search-icon.6f8ba1b.svg" alt="搜索" class="search-icon">
							</form>
						</li>
						<li class="nav-item submit">
							<img src="https://gold-cdn.xitu.io/v3/static/img/submit-icon.53f4253.svg" class="icon">
							<span>写文章</span>
						</li>
						<li data-v-5ce25e66="" class="nav-item auth"><span data-v-5ce25e66="" class="login" @click="open4">登录</span><span data-v-5ce25e66="" class="register">注册</span></li>
					</ul>
				</div>
			</div>
		</div>
	</div>
</template>

<script type="text/javascript">
	export default {
		data() {
			return {}
		}
	}
</script>

<style>
	#header {
		height: 61px;
		background: #fff;
	}
	
	#header .container {
		max-width: 960px;
		margin: 0 auto;
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-align: center;
		-ms-flex-align: center;
		align-items: center;
		height: 100%;
	}
	
	#header #logo {
		margin-right: 24px;
	}
	
	#header .main-nav {
		height: 100%;
		-webkit-box-flex: 1;
		-ms-flex: 1 0 auto;
		flex: 1 0 auto;
	}
	
	#header .nav-list,
	.nav-item {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-align: center;
		-ms-flex-align: center;
		align-items: center;
		height: 100%;
		margin: 0;
	}
	
	#header .nav-item {
		color: #71777c;
		padding: 0 14px;
		font-size: 16px;
		-webkit-box-pack: center;
		-ms-flex-pack: center;
		justify-content: center;
		cursor: pointer;
	}
	
	#header .nav-list>li {
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
	}
	
	#header .nav-list #nav {
		display: flex;
	}
	
	#header .nav-list #nav li.nav-item {
		padding: 0 20px;
		-webkit-box-pack: center;
		-ms-flex-pack: center;
		justify-content: center;
		height: 61px;
	}
	
	#header #nav li a {
		font-size: 16px;
		color: #71777c
	}
	
	#header #search {
		-webkit-box-flex: 1;
		-ms-flex: 1 1 auto;
		flex: 1 1 auto;
		-webkit-box-pack: end;
		-ms-flex-pack: end;
		justify-content: flex-end;
		cursor: auto;
	}
	
	#header #search input {
		width: 144px;
		height: 32px;
		border: none;
		padding: 7px 12px;
		box-shadow: none;
		outline: none;
		font-size: 14px;
		color: #666;
		background-color: transparent;
		box-sizing: border-box;
	}
	
	#header .search-form {
		border: 1px solid hsla(0, 0%, 59%, .2);
		background-color: rgba(227, 231, 236, .2);
		display: -webkit-box;
		display: -ms-flexbox;
		display: flex;
		-webkit-box-align: center;
		-ms-flex-align: center;
		align-items: center;
		-webkit-box-pack: justify;
		-ms-flex-pack: justify;
		justify-content: space-between;
		border-radius: 2px;
	}
	
	#header .search-form .search-icon {
		padding: 0 .5rem;
		cursor: pointer;
	}
	
	#header .nav-item.submit {
		color: #007fff;
		position: relative;
	}
	
	#header .nav-item.auth {
		color: #007fff;
	}
	
	#header .nav-item:last-child {
		padding-right: 0;
	}
	
	#header .nav-item.auth .login:after {
		content: "\B7";
		margin: 0 4px;
	}
	
	#header .nav-item.submit:after {
		content: "|";
		position: absolute;
		top: 20px;
		left: 100%;
		color: hsla(0, 0%, 59%, .4);
	}
</style>
<script>
  export default {
    methods: {
      open4() {
       this.$alert('<div data-v-6cb98ece="" class="input-group"><div data-v-6cb98ece="" class="input-box"><input data-v-6cb98ece="" name="loginPhoneOrEmail" maxlength="64" placeholder="请填写手机号或邮箱" class="input"></div><div data-v-6cb98ece="" class="input-box"><input data-v-6cb98ece="" name="loginPassword" type="password" maxlength="64" placeholder="请输入密码" class="input"></div></div><button data-v-6cb98ece="" class="btn">登录</button><div data-v-6cb98ece="" class="prompt-box">没有账号？ <span data-v-6cb98ece="" class="clickable">注册</span><a data-v-6cb98ece="" href="/reset-password" class="right clickable">忘记密码</a></div>', '登录', {
          dangerouslyUseHTMLString: true,
          showConfirmButton:false
        });
      }
    }
  }
</script>