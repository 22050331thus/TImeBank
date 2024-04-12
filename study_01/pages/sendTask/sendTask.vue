<template>
	<view>
		<view class="sendTask">
			<form action="" class="centerWord">
				<p>任务标题：<input type="text" v-model="Voserver_title"/></p>
				<p>服务类型：<input type="text" v-model="Voserver_type"/></p>
				<p>服务开始时间：<input type="text" v-model="Voserver_starttime"/></p>
				<p>服务地址：<input type="text" v-model="Voserver_add"/></p>
				<p>服务内容：<input type="text" v-model="Voserver_content"/></p>
				
				<button type="submit" @click="sendTask">发送</button>
			</form>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				Voserver_title:"",
				Voserver_type:"",
				Voserver_content:"",
				Voserver_starttime:"",
				Voserver_add:""
			};
		},
		methods:{
			sendTask(){
				
			}
		}
	}
</script>

<style lang="scss">

</style>
