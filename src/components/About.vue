<template>
	<div class="pg-2">
		<div class="center">
			<div class="pg2-left">
				<Intr></Intr>
				<Infinite></Infinite>
			</div>
			<div class="pg2-right">
				<Author></Author>
			</div>
		</div>
	</div>
</template>

<script>
	import Intr from './About_Intr.vue'
	import Infinite from './About_Infinite.vue'
	import Author from './About_Author.vue'

	export default {
		components: {
			Intr,
			Infinite,
			Author
		}
	}
</script>

<style scoped>
	.pg-2 {
		min-width: 1200px;
		height: 752px;
		background: url('../assets/img/bg_02.jpg') center no-repeat;
	}

	.center {
		width: 1200px;
		padding-top: 128px;
		margin: 0 auto;
		overflow: hidden;
	}

	.pg2-left {
		float: left;
	}

	.pg2-right {
		float: right;
	}
</style>