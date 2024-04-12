<template>
	<view>
		<view class="register">
			<form action="" class="centerWord">
				<p>注册昵称：<input type="text" v-model="User_nickname"/></p>
				<p>设置密码：<input type="password"  v-model="User_password"/></p>
				<p>请确认密码：<input type="password" v-model="User_password"/></p>
				<p>填写手机号：<input type="tel" v-model="User_phone"/></p>
				<p>填写姓名：<input type="text" v-model="User_name"/></p>
				<p>填写地址：<input type="text" v-model="User_add"/></p>
				<p>填写邮箱：<input type="text" v-model="User_email"/></p>
				
				<button type="submit" @click="register"></button>
			</form>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				User_nickname:"",
				User_password:",",
				User_phone:"",
				User_name:"",
				User_email:"",
				User_add:""
			};
		},
		method:{
			register(){
				
			}
		}
	}
</script>

<style lang="scss">

</style>
