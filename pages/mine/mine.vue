<template>
	<view>
		<!-- 1.partOne -->
		<view class="partOne">

			<!-- 头像和号码 -->
			<view class="profile_title">
				<u-avatar size='60'></u-avatar>
				<text style="font-size: 45rpx;color: white; margin-top:20rpx;margin-left: 20rpx;">19612348970</text>
			</view>

			<view class="money_text">
				<u-row>
					<u-col span="4">
						<view class="demo-layout">
							<text>23212,299.00</text>
							<text style="font-size: 20rpx;">账户资金</text>
						</view>
					</u-col>
					<u-col span="4">
						<view class="demo-layout">
							<text>3459.00</text>
							<text style="font-size: 20rpx;">累计收益(元)</text>
						</view>
					</u-col>

					<u-col span="4">
						<view class="demo-layout">
							<text>12.00</text>
							<text style="font-size: 20rpx;">万份收益(元)</text>
						</view>
					</u-col>
				</u-row>
			</view>
		</view>

		<!-- partTwo -->
		<view class="partTwo">
			<u-row justify="center">
				<u-col span="5">
					<view class="rowItem">
						<image src="../../static/mine/recharge.png" mode=""></image>
						<text>充值</text>
					</view>
				</u-col>
				<u-col span="5">
					<view class="rowItem">
						<image src="../../static/mine/withdrawal.png" mode=""></image>
						<text>提现</text>
					</view>
				</u-col>
			</u-row>
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
	image {
		width: 50px;
		height: 50px;
	}

	.partOne {
		height: 300rpx;
		background-color: #ff4d4f;
		padding: 50rpx 40rpx;
	}

	.profile_title {
		/* border: 1px solid green; */
		display: flex;
	}

	.money_text {
		margin-top: 40rpx;
		color: white;
	}

	.demo-layout {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: space-around;
		height: 88rpx;
	}


	.partTwo {
		background-color: white;
		border-radius: 25rpx;
		margin: 0 40rpx;
		margin-top: -60rpx;
		box-shadow: 1px 1px 13px #b0b0b0;
		
		
		padding: 25rpx 0;
	
	}
	
	.rowItem{
		display: flex;
		align-items: center;
		justify-content: center;
	}
</style>
