<template>
	<view>
		<view class="Block">
			<view class="time">
				任务发送时间：{{time}}
			</view>
		</view>
		<view class="Block">
			<view class="fasongren">
				任务发起人：{{name}}
			</view>
		</view>
		<view class="Block">
			<view class="jieshouren">
				<text v-if="receive">任务接收人：{{name1}}</text>
				<text v-else>暂未有人接收</text>
			</view>
		</view>
		<view class="Block">
			<view class="Location">
				任务地点：{{location}}
			</view>
		</view>
		<view class="Block">
			<view class="TraceMoney">
				时间币：{{money}}
			</view>
		</view>
		<view class="Block">
			<view class="classfy">
				任务类别：{{taskClass}}
			</view>
		</view>
		<view class="LargeBlock">
			<view class="detail">
				{{Text}}
			</view>
		</view>
		<view class="Block">
			<button>提交接收申请</button>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				User_id:"",
				Voserver_joinnum:"",
				Voserver_starttime:"2021/1/1",
				name:"李四",
				Voserver_stause:"",
				name1:"王五",
				Voserver_add:"教学楼",
				Voserver_content:"地点：XXXX，任务内容：XXXX，时间币：XXXX",
				money:123,
				Voserver_type:"其他类别",
				//发布时间
				Voserver_annotime:"",
				Voserver_title:"",
				//截止时间
				Voserver_endtime:""
			};
		}
	}
</script>

<style lang="scss">
.Block{
	height: 100rpx;
	background-color: pink;
	margin: 5rpx;
}
.LargeBlock{
	height: 450rpx;
	background-color: pink;
	margin: 5rpx;
}
.time{
	flex: auto;
	display: flex;
	flex-direction: column;
	line-height: 100rpx;
	justify-content: center;
	align-items: center;
}
.fasongren{
	flex: auto;
	display: flex;
	line-height: 100rpx;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
.jieshouren{
	flex: auto;
	display: flex;
	line-height: 100rpx;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
.Location{
	flex: auto;
	display: flex;
	line-height: 100rpx;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
.TraceMoney{
	flex: auto;
	display: flex;
	line-height: 100rpx;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
.classfy{
	flex: auto;
	display: flex;
	line-height: 100rpx;
	flex-direction: column;
	justify-content: center;
	align-items: center;
}
.detail{
	text-indent: 2em;
}
</style>
