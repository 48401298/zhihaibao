<template>
	<view class="content">
		
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
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
	
	.headerInfo {
		height: 80upx;
		width: 100%;
		line-height: 80upx;
		display: flex;
		flex-direction: row;
		border-bottom: 1upx solid #C0C0C0;
	}
	
	.changeStation {
		float: left;
		left: 0upx;
	}
	
	.stationInfo {
		float: right;
		right: 0upx;
		margin-right: 0upx;
		text-align: right;
	}
	
	.userInfo {
		float: right;
		width: 200upx;
		right: 0upx;
		margin-right: 0upx;
		text-align: right;
		background-color: red;
	}
	
</style>
