<template>
	<view class="content">
	  <web-view :webview-styles="webviewStyles" src="https://hightechex.vip"></web-view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {},
		methods: {}
	}
</script>


<style>
	.webviewStyles{
		height: 100vh !important;
	}
	.content {
		height: 100vh !important;
	}
	iframe{
		height: 100% !important;
	}
</style>

