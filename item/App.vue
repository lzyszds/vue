<template>
    <div id="app">
        <div class="login-container">
        	<router-link to="./login" tag="span">登录</router-link>
			<router-link to="./register" tag="span">注册</router-link>
        </div>
		<router-view></router-view>
    </div>
</template>
<style lang="scss"  scoped>
		.login-container{
			display: flex;
			justify-content: center;
			padding-top: 10px;
			width: 500px;
			
			span{
				padding: 5px 20px;
				border-radius: 5px;
				font-size: 16px;
			}
		}
		.router-link-active{
			color: #007AFF;
		}
</style>