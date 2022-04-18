<template>
	<view>
		<view class="top"></view>
		<web-view :src="src"></web-view>
	</view>
</template>

<script>
	export default {
		onLoad(opition) {
			this.src = opition.url;
		},
		data() {
			return {
				src:""
			}
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
</style>
