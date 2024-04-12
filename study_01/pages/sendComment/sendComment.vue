<template>
	<view>
		<view class="sendComment">
			<form action="">
				<p>输入评价内容：<input type="text" /></p>
				<button @click="sendComment" type="submit"></button>
			</form>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				Appraise_content:""
			};
		},
		methods:{
			sendComment(){
				
			}
		}
	}
</script>

<style lang="scss">

</style>
