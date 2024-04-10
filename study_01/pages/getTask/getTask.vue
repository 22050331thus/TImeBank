<template>
	<view>
		<view class="classfy">
			<view class="">
				<navigator url=""><text class="font">智力劳动类</text></navigator>
			</view>
		</view>
		<view class="classfy">
			<view class="">
				<navigator url=""><text class="font">体力劳动类</text></navigator>
			</view>
		</view>
		<view class="classfy">
			<view class="">
				<navigator url=""><text class="font">其他分类</text></navigator>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="scss">
.classfy{
	margin: 30rpx;
	width: 690rpx;
	height: 300rpx;
	background-color: pink;
	border-radius: 50rpx;
	// 把文字对象居中
	flex: auto;
	display: flex;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
.font{
	font-size: 50rpx;
	font-family: 黑体;
}
</style>
