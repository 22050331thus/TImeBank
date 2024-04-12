<template>
	<view>
		<view class="apply">
			<form action="">
				<p>申请时间：<input type="text" v-model="Audit_subtime"/></p>
				<p>申请内容：<input type="text" v-model="Audit_content"/></p>
				<!-- <p>申请材料：<input type="image" /></p> -->
				<button @click="sendapply()">提交申请</button>
			</form>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				Audit_subtime:"",
				Audit_content:"",
				Audit_material:""
			};
		},
		methods:{
			sendapply(){
				
			}
		}
	}
</script>

<style lang="scss">

</style>
