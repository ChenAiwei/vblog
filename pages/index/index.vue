<template>
	<view class="content">
		<text>FEATURED TAGS</text>
		<view class="tags">
			<view class="tag" @click="tagClick()" :style="{color:home[0].color,borderColor:home[0].borderColor}">笔记</view>
			<view class="tag">springboot</view>
			<view class="tag">前端技术</view>
			<view class="tag">撒大声地</view>
			<view class="tag">撒大声地</view>
			<view class="tag">笔记</view>
			<view class="tag">22</view>
			<view class="tag">撒大声地</view>
			<view class="tag">22</view>
			<view class="tag">22</view>
			<view class="tag">笔记</view>
			<view class="tag">springboot</view>
			<view class="tag">前端技术</view>
			<view class="tag">撒大声地</view>
			<view class="tag">撒大声地</view>
			<view class="tag">笔记</view>
			<view class="tag">22</view>
			<view class="tag">撒大声地</view>
			<view class="tag">22</view>
			<view class="tag">22ssss</view>
		</view>
		
		
		<view class="item-list">
			
		<view class="item">
		<view class="item-year">
			<text>2020</text>
		</view>
		<view class="item-detail">
			<view class="title">总结是多少Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		</view>
		
		
		<view class="item">
		<view class="item-year">
			<text>2019</text>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		</view>
		
		<view class="item">
		<view class="item-year">
			<text>2018</text>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		<view class="item-detail">
			<view class="title">Peter John Landin</view>
			<view class="sub-title">计算机科学偶像」- 彼得·约翰·兰丁</view>
			<view class="split"></view>
		</view>
		</view>
		
		</view>
		
		
	</view>
</template>

<script>
export default {
	data() {
		return {
			home: [
				{
					tagId: 1,
					count: 2,
					tag: 'Google',
					check:false,
					color:'#DFD8CA',
					borderColor:'#4E4C48',
					selectedColor:'#AFE1E2',
					selectedBorderColor:'#AFE1E2',
					yearList: [
						{
							articleList: [
								{
									view: 15,
									createTime: 1584693927099,
									like: 1,
									subtitle: 'talk how to use',
									comment: 0,
									id: 1,
									title: 'Google mail trans as diff '
								}
							],
							year: '2020',
							id: 1
						}
					]
				}
			]
		};
	},
	onLoad() {},
	methods: {
		tagClick(){
			//此方法还要入参 ID 和 check字段 根据字段改变颜色和渲染数据
			this.home[0].color = this.home[0].selectedColor
			this.home[0].borderColor = this.home[0].selectedBorderColor
			
		}
		
	}
};
</script>

<style lang="scss">
page{
	width: 100%;
	height: 100vh;
	background-color: $blog-bg-color-night;
	color: $blog-font-color-night;
}
.content {
	margin: 20rpx 15rpx 20rpx 15rpx;
	text{
		font-size: 30rpx;
		font-weight: bold;
		color: #e5e5e8;
		
	}
	.tags{
		//margin: 30rpx 50rpx 15rpx 15rpx;
		margin-top: 20rpx;
		.tag{
			border: 1px solid #4E4C48;
			border-radius: 30rpx;
			font-size: 24rpx;
			padding: 10rpx 20rpx;
			width: auto;
			display: inline-block !important;
			margin-right: 6rpx;
			margin-left: 6rpx;
			margin-bottom: 20rpx;
		}
	}
	.item-list{
		margin-top: 30rpx;
		margin-bottom: 20rpx;
		.item{
			margin-top: 50rpx;
			.item-year{
				text{
					color: #AFE1E2;
					font-size: 35rpx;
					font-family:-apple-system,BlinkMacSystemFont,"Helvetica Neue",Arial,"PingFang SC","Hiragino Sans GB",STHeiti,"Microsoft YaHei","Microsoft JhengHei","Source Han Sans SC","Noto Sans CJK SC","Source Han Sans CN","Noto Sans SC","Source Han Sans TC","Noto Sans CJK TC","WenQuanYi Micro Hei",SimSun,sans-serif;
					font-weight: 200;
				}
			}
			.item-detail{
				margin-top: 30rpx;
				.title{
					font-size: 32rpx;
					font-weight: 500;
					margin-top: 25rpx;
				}
				.sub-title{
					line-height: 1.3;
					margin: 0;
					font-size: 25rpx;
					font-weight: 300;
					margin-bottom: 25rpx;
					margin-top: 10rpx;
				}
				.split{
					background: #44423F;
					height: 0.8px;
					margin-top: 30rpx;
				}
			}
		}
	}
	
	.footer{
		margin-top: 50rpx;
		margin-bottom: 50rpx;
		margin-left: 30rpx;
		margin-right: 30rpx;
		font-size: 30rpx;
		font-weight: 200;
		
	}
}
</style>
