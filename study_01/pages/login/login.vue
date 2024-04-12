<template>
	<view>
		<view id="login">
			<view class="account">
				<form action="">
					<p>账号：<input type="text"  v-model="User_id"/></p>
					<p>密码：<input type="safe-password"  v-model="User_password"/></p>
					<button type="submit" @click="login">登录</button>
				</form>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		el:'#login',
		data() {
			return {
				User_id:"",
				User_password:""
				
			};
		},
		methods: {
			login(){
				
			}
		}
	}
</script>

<style lang="scss">
.account{
	flex: auto;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
</style>
