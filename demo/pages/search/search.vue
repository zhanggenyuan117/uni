<template>
	<view class="search">
		<input type="text" v-model="search" placeholder="请输入商品名"/>
	</view>
</template>

<script>
	export default{
		data(){
			return{
				
			}
		},
		created(){
			this.includs();
		},
		methods:{
			includs(){
				let str = 'hello';
				let bool = str.includes('he')
				console.log(bool)
			}
		}
	}
</script>

<style lang="scss" scoped>
	.search{
		width: 100%;
		height: 80rpx;
		box-sizing: border-box;
		padding: 10rpx 20rpx;
		background-color: #F0AD4E;
		input{
			border: 1rpx solid #C0C4CC;
			border-radius: 30rpx;
			height: 100%;
			background-color: #fff;
			padding-left: 30rpx;
			font-size: 28rpx;
			color: #ccc;
		}
	}
</style>
