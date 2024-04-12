<template>
	<view>
		<view class="sendPost">
			<form action="">
				<p>请输入帖子标题：<input type="text" v-model="Post_title"/></p>
				<p>请输入发帖内容：<input type="text" v-model="Post_content"/></p>
				<button type="submit" @click="sendPost">发送帖子</button>
			</form>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				Post_content:"",
				Post_title:""
			};
		},
		methods:{
			sendPost(){
				
			}
		}
	}
</script>

<style lang="scss">

</style>
