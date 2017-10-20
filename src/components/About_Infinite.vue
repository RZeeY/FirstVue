<template>
	<div class="Infinite-wrap"> 
		<div class="Infinite-title">
			<div class="Infinite-title-png"></div>
		</div>
		<div class="Infinite-cont">
			<h1>黄沙掩埋了白骨</h1>
			<p>《无限流》起源于小说《无限恐怖》的火爆，以及大量跟风小说的问世。其任务模式来源于漫画《杀戮都市》。无限流意义应该是“包罗万象”，即：包含无限的元素，包括科学、宗教、神话、传说、历史、现实、电影、动漫、游戏等，并且高于它们，有这样的包含这一切的世界观才是无限流小说的精华。但部分无限流小说只是单纯的模仿无限三部曲的“形”，而忽视了它的“神”。</p>
			<a href="javascript:;">
				<div class="read-more"></div>
			</a>
		</div>
	</div>
</template>

<script>
	export default {

	}
</script>

<style scoped>
	.Infinite-wrap {
		width: 766px;
		height: 330px;
		margin-top: 13px;
	}

	.Infinite-title {
		width: 100%;
		height: 45px;
		border-top: 2px solid #00a3ef;
		background-color: #222c47;
	}

	.Infinite-title .Infinite-title-png {
		width: 82px;
		height: 25px;
		margin: 10px 0 0 17px;
		background: url('../assets/img/content_02.png') center no-repeat;		
	}

	.Infinite-cont {
		width: 100%;
		height: 198px;
		margin-top: 3px;
		background-color: #121b38;
		overflow: hidden;
		position: relative;
	}

	.Infinite-cont h1 {
		margin-top: 20px;
		margin-left: 22px;
		font-size: 20px;
		color: #fff;
	}

	.Infinite-cont p {
		width: 721px;
		height: 90px;
		margin-top: 13px;
		margin-left: 22px;
		font-size: 14px;
		color: #a3b0c9;
		overflow: hidden;
	}

	.Infinite-cont .read-more {
		position: absolute;
		right: 30px;
		bottom: 20px;
		width: 75px;
		height: 22px;
		background: url('../assets/img/read_more.png') center no-repeat;
	}
</style>
read_more.png