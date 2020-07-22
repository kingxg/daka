<template>
	<view class="page-wrap">
		<view class="activity">
			<view class="activity__cover">
				<image class="cover-pic" src="../../static/index/cover.jpg" mode="aspectFill"></image>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	.page-wrap {
		background-color: #ededed;
	}
	
	.activity__cover {
		height: 400rpx;
	}
	
	.cover-pic {
		width: 100%;
		height: 100%;
	}
</style>
