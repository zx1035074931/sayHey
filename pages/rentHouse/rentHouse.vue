<template>
	<view class="">
		<u-action-sheet :list="list" v-model="show"></u-action-sheet>
		<view style="padding: 20px;">
			<u-button type="primary" text="确定"></u-button>
		</view>
	</view>

</template>

<script>
	export default {
		data() {
			return {
				list: [{
					text: '点赞',
					color: 'blue',
					fontSize: 28
				}, {
					text: '分享'
				}, {
					text: '评论'
				}],
				show: true
			}
		}
	}
</script>
<style>

</style>
