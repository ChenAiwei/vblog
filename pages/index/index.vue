<template>
	<view class="content">首页</view>
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
	methods: {}
};
</script>

<style lang="scss">
.content {
	width: 100%;
	height: 100vh;
	background-color: #272725;
	color: #dfd8ca;
}
</style>
