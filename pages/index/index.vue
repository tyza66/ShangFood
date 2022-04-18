<template>
	<view>
		<view class="top"></view>
		<view class="swiper-c">
			<swiper indicator-dots="true" autoplay="autoplay" interval="1000" duration="500">
				<swiper-item>
					<image src="https://s2.loli.net/2022/04/16/Cs7fcykHFMipUjE.png"></image>
				</swiper-item>
				<swiper-item>
					<image src="https://s2.loli.net/2022/04/16/gLOiyTqZFrdGYR6.png"></image>
				</swiper-item>
				<swiper-item>
					<image src="https://s2.loli.net/2022/04/16/fEJvxtRjIdzsLU5.png"></image>
				</swiper-item>
				<swiper-item>
					<image src="https://s2.loli.net/2022/04/18/eC7fzLhXYIk9Fcx.png"></image>
				</swiper-item>
				<swiper-item>
					<image src="https://s2.loli.net/2022/04/18/KwLcxM6vnVRDAOT.png"></image>
				</swiper-item>
			</swiper>
		</view>
		<div class="zixun">
			<div class="tou">
				<view class="a1">
					<image src="../../static/icons/jp.png">
					<p>健康资讯</p>
				</view>
			</div>
			<view class="one">
				<image src="https://file.youlai.cn/cnkfile1/M01/00/2C/o4YBAFuD5FuAUKY8AAB5dhZMJJQ11.jpeg">
				<p>如何健康饮食-有来医生</p>
			</view>
			<view class="one">
				<image src="https://dss2.bdstatic.com/8_V1bjqh_Q23odCf/pacific/1992225496.png">
				<p>饮食营养与健康课程首页</p>
			</view>
			<view class="one">
				<image src="https://fc5tn.baidu.com/it/u=651266219,2472862346&fm=202&src=801">
				<p>营养师报考条件</p>
			</view>
			<view class="one">
				<image src="https://t9.baidu.com/it/u=767664801,13412636&fm=74&app=80&size=f256,256&n=0&f=JPEG&fmt=auto?sec=1650387600&t=ce02ce27a588c542ced6b114acb9306f">
				<p>健康饮食习惯</p>
			</view>
			<view class="one">
				<image src="https://gimg3.baidu.com/search/src=https%3A%2F%2Fbkimg.cdn.bcebos.com%2Fsmart%2F5243fbf2b21193130d016f7766380cd790238db3-bkimg-process%2Cv_1%2Crw_1%2Crh_1%2Cmaxl_300%2Cpad_1&refer=http%3A%2F%2Fwww.baidu.com&app=2021&size=f256,256&n=0&g=0n&q=100&fmt=auto?sec=1650387600&t=e07d286553da9a841d40ba807336c731">
				<p>健康饮食(健康饮食)</p>
			</view>
			<view class="one">
				<image src="https://fc1tn.baidu.com/it/u=1124719760,3626708762&fm=202&mola=new&crop=v1">
				<p>饮食与健康图文</p>
			</view>
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

		}
	}
</script>

<style>
	.top {
		height: var(--status-bar-height);
		width: 100%;
		background-color: #FFFFFF;
	}

	.swiper-c {
		width: 100%;
		height: 400rpx;
	}

	.swiper-c swiper {
		width: 100%;
		height: 100%;
	}

	.swiper-c swiper swiper-item image {
		width: 100%;
		height: 100%;
	}
	.zixun{
		width: 100%;
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
	.one{
		width: 100%;
		height: 150rpx;
		border-bottom: #808080 solid 1rpx;
		display: flex;
		flex-direction: row;
		justify-content: left;
		align-items: center;
	}
	.one image{
		width: 140rpx;
		height: 140rpx;
	}
</style>
