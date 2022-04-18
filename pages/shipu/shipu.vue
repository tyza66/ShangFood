<template>
	<view>
		<view class="top"></view>
		<div class="container" @click="go1()">
			<image src="https://st-cn.meishij.net/r/157/118/9904657/s9904657_165021072017598.jpg">
			<p class="title">家常南瓜饼减脂套餐</p>
		</div>
		<view class="top"></view>
		<div class="container" @click="go2()">
			<image src="https://st-cn.meishij.net/r/121/15/3441371/s3441371_151963507774233.jpg">
			<p class="title">五彩皮冻健康食谱</p>
		</div>
		<view class="top"></view>
		<div class="container" @click="go3()">
			<image src="https://st-cn.meishij.net/r/158/87/4021908/s4021908_143217847155357.jpg">
			<p class="title">捞汁素什锦</p>
		</div>
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
			go1(){
				uni.navigateTo({
					url:'../web/web?url=https://www.meishij.net/zuofa/nanguabing_190.html'
				})
			},
			go2(){
				uni.navigateTo({
					url:'../web/web?url=https://www.meishij.net/zuofa/wucaipidong_1.html'
				})
			},
			go3(){
				uni.navigateTo({
					url:'../web/web?url=https://www.meishij.net/zuofa/laozhisushijin.html'
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
	.container{
		width: 100%;
		height: 500rpx;
		position: relative;
	}
	.container image{
		position: absolute;
		left: 0;
		top: 0;
		width: 100%;
		height: 100%;
	}
	.container .title{
		position: absolute;
		z-index: 0;
		left: 50rpx;
		top: 420rpx;
		font-size: 50rpx;
		color: black;
	}
</style>
