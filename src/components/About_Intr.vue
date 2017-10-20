<template>
	<div class="intr-wrap">
		<div class="intr-title">
			<div class="intr-title-png"></div>
		</div>
		<div class="intr-cont">
			<div class="intr-cont-img">
				<a href="javascript:;" target="_blank">
					<img src="../assets/img/cont_img.png" height="240" width="207" alt="">
				</a>
			</div>
			<div class="intr-cont-cont">
				<h1>黄沙掩埋了白骨</h1>
				<p>夕阳下的风中，有着血腥的味道。大陆的痛楚，在朝着四面八方扩散，当大爆炸的历史出现拐点的时候，当巨大的钢铁要塞横亘而过，遮蔽住人们视野的时候， 当使徒的阴谋悄然深入到了每个人生活中的时候。和平即将被打破，恐怖即将降临！ 这时候，一个独立于命运河流之外的少年，却以“召唤物”身份开始穿梭于阿拉德与地球之间.....</p>
			</div>
			<div class="intr-cont-right">
				<a href="javascript:;" target="_blank">
					<div class="read-big"></div>
				</a>
				<a href="javascript:;" target="_blank">
					<div class="read-samll"></div>
				</a>
			</div>
		</div>
	</div>
</template>

<script>
	export default {

	}
</script>

<style scoped>
	.intr-wrap {
		width: 766px;
		height: 330px;
	}

	.intr-title {
		width: 100%;
		height: 45px;
		border-top: 2px solid #00a3ef;
		background-color: #222c47;
	}

	.intr-title .intr-title-png {
		width: 64px;
		height: 25px;
		margin: 10px 0 0 17px;
		background: url('../assets/img/content.png') center no-repeat;		
	}

	.intr-cont {
		width: 100%;
		height: 280px;
		margin-top: 3px;
		background-color: #121b38;
		overflow: hidden;
		position: relative;
	}

	.intr-cont .intr-cont-img {
        float: left;
        width: 207px;
        height: 240px;
        margin-top: 20px;
        margin-left: 18px;
	}

	.intr-cont .intr-cont-cont {
		float: left;
		width: 322px;
		height: 208px;
		padding-top: 12px;
		padding-bottom: 22px;
		margin-top: 20px;
		margin-left: 30px;
	}

	.intr-cont .intr-cont-cont h1 {
		margin-bottom: 18px;
		color: #ffffff;
		font-size: 20px;
	}

	.intr-cont .intr-cont-cont p {
		margin-bottom: 18px;
		line-height: 22px;
		color: #a0adc4;
		font-size: 14px;
	}

	.intr-cont .intr-cont-right {
		float: left;
		width: 155px;
		height: 240px;
		margin-top: 20px;
		margin-left: 16px;
	}

	.intr-cont .intr-cont-right .read-big {
		width: 155px;
		height: 56px;
		margin-top: 5px;
		background: url('../assets/img/read.png') center no-repeat;
	}

	.intr-cont .intr-cont-right .read-samll {
		width: 58px;
		height: 4px;
		margin-top: 170px;
		margin-left: 96px;
		background: url('../assets/img/read_small.png') center no-repeat;
	}
</style>