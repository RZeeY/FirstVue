<template>
	<div class="Author-wrap"> 
		<div class="Author-title">
			<div class="Author-title-png"></div>
		</div>
		<div class="Author-cont">
			<div class="Author-cont-center">
				<img src="../assets/img/author.png" height="220" width="372" alt="">
				<h1>黄沙掩埋了白骨</h1>
				<p>卷土，起点知名作家，原名陈圣夫，四川成都人，医学系毕业。2008年8月开始着手创作《王牌进化》，走出了无限流的老路开创了属于自己的新的风格，将无限流文学推上了一个新的高峰。
				<br/>
				<br/>
				在UP2016腾讯互动娱乐年度发布会上，卷土成为执笔《地下城与勇士》职业文学小说的最终人选。</p>
				<a href="javascript:;">
					<div class="read-more"></div>
				</a>
			</div>
		</div>
	</div>
</template>

<script>
	
</script>

<style>
	.Author-wrap {
		width: 420px;
		height: 590px;
	}

	.Author-wrap .Author-title {
		width: 100%;
		height: 45px;
		border-top: 2px solid #00a3ef;
		background-color: #222c47;
	}

	.Author-title .Author-title-png {
		width: 82px;
		height: 25px;
		margin: 10px 0 0 17px;
		background: url('../assets/img/content_03.png') center no-repeat;		
	}

	.Author-wrap .Author-cont {
		width: 100%;
		height: 540px;
		margin-top: 3px;
		background-color: #121b38;
		overflow: hidden;
		position: relative;	
	}

	.Author-wrap .Author-cont .Author-cont-center {
		width: 372px;
		padding-top: 20px;
		margin: 0 auto;
	}

	.Author-wrap .Author-cont .Author-cont-center h1 {
		margin: 34px 0 19px;
		font-size: 20px;
		color: #fff;
	}

	.Author-wrap .Author-cont .Author-cont-center p {
		font-size: 14px;
		line-height: 22px;
		color: #a3b0c9;
	}

	.Author-wrap .Author-cont .Author-cont-center .read-more {
		position: absolute;
		right: 30px;
		bottom: 20px;
		width: 58px;
		height: 4px;
		background: url('../assets/img/read_small.png') center no-repeat;
	}
</style>