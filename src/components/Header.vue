<template>
	<div class="pg-1">
		<a class="toArea" href="javascript:;" target="_blank"></a>
		<a class="toHome" href="javascript:;" target="_blank"></a>
		<a class="toRead" href="javascript:;" target="_blank"></a>
	</div>
</template>

<script>
export default {
	data() {
		return {
		}
	}
}
</script>

<style scoped>
	.pg-1 {
		min-width: 1200px;
		height: 892px;
		background: url('../assets/img/bg_01.jpg') center no-repeat;
		position: relative;
	}

	.toArea {
		position: absolute;
		bottom: 138px;
		left: -610px;
		right: 0;
		display: block;
		width: 223px;
		height: 98px;
		margin: auto;
	}

	.toHome {
		position: absolute;
		bottom: 138px;
		left: 11px;
		right: 0;
		display: block;
		width: 400px;
		height: 98px;
		margin: auto;
	}

	.toRead {
		position: absolute;
		bottom: 138px;
		left: 0;
		right: -632px;
		display: block;
		width: 223px;
		height: 98px;
		margin: auto;
	}
</style>