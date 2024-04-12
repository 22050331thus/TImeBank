<template>
	<view class="index">
		<input type="text" placeholder=" 搜索" class="input" confirm-type="search"/>
		<view class="image-show">
			<swiper :indicator-dots="true" :autoplay="true" :interval="3000" :duration="800" circular="true">
				<swiper-item>
					<view class="swiper-item">
						<image src="../../static/pic/pic1.jpeg" mode="aspectFill" class="myimg"></image>
					</view>
				</swiper-item>
				<swiper-item>
					<view class="swiper-item">
						<image src="../../static/pic/pic2.jpeg" mode="aspectFill" class="myimg"></image>
					</view>
				</swiper-item>
				<swiper-item>
					<view class="swiper-item">
						<image src="../../static/pic/pic3.jpg" mode="aspectFill" class="myimg"></image>
					</view>
				</swiper-item>
			</swiper>
		<view class="often-app-block">
			<text class="little-title" selectable="true" >\n常用应用</text>
			<!-- 常用app板块 -->
			<view class="often-app">
				<view class="app">
					<view class="centerWord">
						<navigator url="/pages/todoList/todoList">待办查询</navigator>
					</view>
				</view>
				<view class="app">
					<view class="centerWord">
						<navigator url="/pages/moneyCheck/moneyCheck">余额查询</navigator>
					</view>
				</view>
				<view class="app">
					<view class="centerWord">
						<navigator url="/pages/getTask/getTask">获取任务</navigator>
					</view>
					
				</view>
			</view>
		<view class="receive-task">
			<text class="little-title" selectable="true">最新任务获取</text>
			<view class="new-task">
				<navigator url="/pages/taskDetail/taskDetail">task1</navigator>
				
			</view>
			<view class="new-task">
				<navigator url="/pages/taskDetail/taskDetail">task2</navigator>
			</view>
			<view class="new-task">
				<navigator url="/pages/taskDetail/taskDetail">task3</navigator>
			</view>
			<view class="centerWord">
				<navigator url="/pages/getTask/getTask">查看更多</navigator>
			</view>
			
		</view>
		</view>
		</view>
	</view>
	
	
</template>

<script>
	export default {
		data(){
			return{
				title:"主页",
				num:"123"
			};
		}
	}
</script>

<style lang="scss">
	.input{
		margin: 10rpx 25rpx;
		width: 700rpx;
		height: 50rpx;
		background-color:#F3F4F5;
		border-radius: 20rpx;
		border: 2rpx solid #1B1616;
	}
	.myimg{
		width: 710rpx;
		height: 400rpx;
		margin: 20rpx;
	}
	.often-app{
		margin: 20rpx;
		width: 710rpx;
		height: 300rpx;
		background-color: #F3F4F5;
		//padding: 20rpx;
		.app{
			height: 90rpx;
			//width: 100rpx;
			background-color: white;
			margin: 5rpx;
		}
	}
	.little-title{
	}
	.new-task{
		height: 200rpx;
		background-color: white;
		margin: 20rpx;
	}
	.view-more{
		flex: auto;
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}
</style>
