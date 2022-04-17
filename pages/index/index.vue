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
							<image src=""></image>
						</swiper-item>
						<swiper-item>
							<image src=""></image>
						</swiper-item>
					</swiper>
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

		}
	}
</script>

<style>
	.top {
			height: var(--status-bar-height);
			width: 100%;
			background-color: #FFFFFF;
		}
	.swiper-c{
			width: 100%;
			height: 400rpx;
		}
		.swiper-c swiper{
			width: 100%;
			height: 100%;
		}
		.swiper-c swiper swiper-item image{
			width: 100%;
			height: 100%;
		}
</style>
