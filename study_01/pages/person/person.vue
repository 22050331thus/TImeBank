<template>
	<view class="index">
		<view class="imformation" >
				<image src="../../static/pic/photo.jpg" class="photo" mode="aspectFill"></image>
			<view class="name">
				{{name}}
			</view>
		</view>
		<view class="Block">
			<view class="balance">
				<text>时间币余额：{{balance}}</text>
			</view>
		</view>
		<view class="Block">
			<view class="check">
				<navigator url="/pages/moneyDetail/moneyDetail"><text>时间币出入详情</text></navigator>
			</view>
		</view>
		<view class="Block">
			<view class="centerWord">
				<navigator url="/pages/todoList/todoList">待办事务</navigator>
			</view>
		</view>
		<view class="Block">
			<view class="centerWord">
				<navigator url="/pages/finishTask/finishTask">完成记录</navigator>
			</view>
		</view>
		<view class="logout">
			<view class="centerWord">
			<button class="btn">退出登录</button>
			</view>
		</view>
		
	</view>
</template>

<script>
	export default {
		data() {
			return {
				name:"zhangsan",
				balance:"1000"
			};
		}
	}
</script>

<style lang="scss">
.imformation{
	height: 180rpx;
	background-color: pink;
	display: flex;
	flex-direction: row;
	margin: 5rpx;
}
.photo{
	width: 150rpx;
	height: 150rpx;
	position: relative;
	left: 18%;
	background-color: white;
	top: 9%;
	border-radius: 50%;
}
.name{
	flex: auto;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
.Block{
	height: 180rpx;
	background-color: pink;
	display: flex;
	flex-direction: row;
	margin: 5rpx;
}
.balance{
	flex: auto;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
.check{
	flex: auto;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
.logout{
	height: 150rpx;
	flex: auto;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
.btn{
	background-color: hotpink;
	
}
</style>
