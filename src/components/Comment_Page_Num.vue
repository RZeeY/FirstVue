<template>
	<div class="pgs">
		<a class="prev" href="javascript:;">上一页</a>
		<!-- <a class="num" href="javascript:;">1</a> -->
		<span class="current">1</span>
		<a class="num" href="javascript:;">2</a>
		<a class="num" href="javascript:;">3</a>
		<a class="num" href="javascript:;">4</a>
		<a class="next" href="javascript:;">下一页</a>
	</div>
</template>

<script>
	
</script>

<style scoped>
	.pgs {
		max-width: 1200px;
		margin: 5px auto 0;
		font-size: 11px;
		text-align: center;
	}

	.pgs .num,
	.pgs .prev,
	.pgs .next {
		display: inline-block;
		padding: 6px 8px;
		margin-right: 6px;
		background: #364367;
		color: #fff;
	}

	.pgs .current {
		display: inline-block;
		padding: 6px 8px;
		margin-right: 6px;
    	background-color: #00aaf0;
    	color: #001823;
	}
</style>