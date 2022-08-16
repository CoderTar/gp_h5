<template>
	<view>
		<!-- 1.partOne -->
		<view class="partOne">

			<!-- 头像和号码 -->
			<view class="profile_title">
				<u-avatar size='60'></u-avatar>
				<text style="font-size: 66rpx;color: white;">19612348970</text>
			</view>
			
			<view class="money_text">
				
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {

		}
	}
</script>

<style>
	.partOne {
		height: 400rpx;
		background-color: #ff4d4f;
	}
	
	.profile_title{
		border: 1px solid green;
		display: flex;
	}
</style>
