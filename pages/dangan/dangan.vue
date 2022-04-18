<template>
	<view>
		<view class="top"></view>
		<div class="tou">
			<view class="a1">
				<image src="../../static/icons/jk.png">
					<p>我的健康方案</p>
			</view>
		</div>
		<view class="info1">
			<p>年龄：20</p>
		</view>
		<view class="info2">
			<p>身高：180（cm）</p>
		</view>
		<view class="info3">
			<p>体重：65（kg）</p>
		</view>
		<view class="info4">
			<p>疾病史：无</p>
		</view>
		<div class="tou">
			<view class="a1">
				<image src="../../static/icons/sp.png">
					<p>智能食谱</p>
			</view>
		</div>
		<view class="input-item">
		    <view class="title-content">
		        <text class="title">食材1</text>
		    </view>
		    <input class="input" placeholder="输入食材" style="margin-left: 40rpx;" />
		</view>
		<view class="input-item">
		    <view class="title-content">
		        <text class="title">食材2</text>
		    </view>
		    <input class="input" placeholder="输入食材" style="margin-left: 40rpx;" />
		</view>
		<view class="input-item">
		    <view class="title-content">
		        <text class="title">食材3
				</text>
		    </view>
		    <input class="input" placeholder="输入食材" style="margin-left: 40rpx;" />
		</view>
		<view class="sub" @click="go()">
			<p>生成食谱</p>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {

			}
		},
		onLoad() {

		},
		methods: {
			go(){
				uni.navigateTo({
					url:"../web/web?url=https://m.idongde.com/c/Ec4E21Eb4A560c4E.shtml"
				})
			}
		}
	}
</script>

<style>
	.top {
		height: var(--status-bar-height);
		width: 100%;
		background-color: #FFFFFF;
	}
	.tou{
		height: 150rpx;
		width: 100%;
		display: flex;
		flex-direction: row;
		justify-content: left;
		align-items: center;
		background: #F8F8F8;
	}
	.a1{
		margin-left: 20rpx;
		display: flex;
		flex-direction: row;
		justify-content: left;
		align-items: center;
	}
	.a1 image{
		width: 80rpx;
		height: 80rpx;
	}
	.a1 p{
		margin-left: 20rpx;
	}
	.info1,.info3{
		width: 100%;
		background: #999999;
		height: 60rpx;
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
	}
	.info2,.info4{
		width: 100%;
		background: #808080;
		height: 60rpx;
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
	}
	.input-item {
	    display: flex;
	    margin-left: 32rpx;
	    margin-right: 32rpx;
	    height: 50px;
	    align-items: center;
	    border-bottom: 1px solid #efeff4;
	    margin-bottom: 20rpx;
	
	    .title-content {
	        display: flex;
	        justify-content: flex-start;
	        align-items: center;
	
	        .title {
	            font-size: 18px;
	        }
	    }
	
	    .input {
	        flex: 1;
	    }
	}
	.sub{
		margin-left: 100rpx;
		margin-right: 100rpx;
		height: 50px;
		background: #007AFF;
		border-radius: 25rpx;
		display: flex;
		flex-direction: row;
		justify-content: center;
		align-items: center;
	}
</style>
