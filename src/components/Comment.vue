<template>
	<div class="pg-4">
		<div class="center">
			<div class="comt-wrap">
				<div class="comt-title">
					<div class="comt-title-png"></div>
				</div>
				<div class="comt-cont-wrap">
					<div class="comt-cont-center">
					<a href="javascript:;" target="_blank">
						<div class="read-more"></div>
					</a>
						<ul class="comt-list">
							<li class="comt-single">
								<a href="javascript:;" target="_blank">
									<img src="../assets/img/pic.png" height="140" width="140" alt="">
									<p>
										卷土，起点知名作家，原名陈圣夫，四川成都人，医学系毕业。2008年8月开始着手创作《王牌进化》，走出了无限流的老路开创了属于自己的新的风格。
									</p>
								</a>
							</li>	
							<li class="comt-single">
								<a href="javascript:;" target="_blank">
									<img src="../assets/img/pic.png" height="140" width="140" alt="">
									<p>
										卷土，起点知名作家，原名陈圣夫，四川成都人，医学系毕业。2008年8月开始着手创作《王牌进化》，走出了无限流的老路开创了属于自己的新的风格。
									</p>
								</a>
							</li>	
							<li class="comt-single">
								<a href="javascript:;" target="_blank">
									<img src="../assets/img/pic.png" height="140" width="140" alt="">
									<p>
										卷土，起点知名作家，原名陈圣夫，四川成都人，医学系毕业。2008年8月开始着手创作《王牌进化》，走出了无限流的老路开创了属于自己的新的风格。
									</p>
								</a>
							</li>	
							<li class="comt-single">
								<a href="javascript:;" target="_blank">
									<img src="../assets/img/pic.png" height="140" width="140" alt="">
									<p>
										卷土，起点知名作家，原名陈圣夫，四川成都人，医学系毕业。2008年8月开始着手创作《王牌进化》，走出了无限流的老路开创了属于自己的新的风格。
									</p>
								</a>
							</li>	
							<li class="comt-single">
								<a href="javascript:;" target="_blank">
									<img src="../assets/img/pic.png" height="140" width="140" alt="">
									<p>
										卷土，起点知名作家，原名陈圣夫，四川成都人，医学系毕业。2008年8月开始着手创作《王牌进化》，走出了无限流的老路开创了属于自己的新的风格。
									</p>
								</a>
							</li>	
							<li class="comt-single">
								<a href="javascript:;" target="_blank">
									<img src="../assets/img/pic.png" height="140" width="140" alt="">
									<p>
										卷土，起点知名作家，原名陈圣夫，四川成都人，医学系毕业。2008年8月开始着手创作《王牌进化》，走出了无限流的老路开创了属于自己的新的风格。
									</p>
								</a>
							</li>																					
						</ul>
					</div>
					<CommentPageNum></CommentPageNum>
					<button id="want-add"></button>
				</div>
			</div>
		</div>
	</div>
</template>

<script scoped>
	import CommentPageNum from './Comment_Page_Num.vue'

	export default {
		components: {
			CommentPageNum
		}
	}
</script>

<style scoped>
	.pg-4 {
		min-width: 1200px;
		height: 858px;
		background: url("../assets/img/bg_04.jpg") center no-repeat;
	}

	.center {
		width: 1200px;
		padding-top: 34px;
		margin: 0 auto;
		overflow: hidden;
	}

	.comt-wrap {
		width: 100%;
		height: 794px;
		position: relative;
	}

	.comt-wrap .read-more {
		position: absolute;
		top: 30px;
		right: 32px;
		width: 75px;
		height: 22px;
		background: url("../assets/img/read_more_02.png") center no-repeat;
	}

	.comt-wrap .comt-title {
		width: 100%;
		height: 77px;
		border-top: 2px solid #00a3ef;
		background-color: #1f2941;
	}	

	.comt-wrap .comt-title .comt-title-png {
		position: relative;
    	top: -2px;
		width: 220px;
		height: 64px;
		margin: 0 auto;
		background: url("../assets/img/content_05.png") center no-repeat;
	}

	.comt-wrap .comt-cont-wrap {
		width: 100%;
		height: 712px;
		margin-top: 2px;
		background-color: #121b38;
	}

	.comt-wrap .comt-cont-wrap .comt-cont-center {
		position: relative;
		padding-left: 30px;
		margin: 0 auto;
	}

	.comt-wrap .comt-cont-wrap .comt-cont-center .comt-list {
		height: 500px;
		padding-top: 70px;
		overflow: hidden;
	}

	.comt-wrap .comt-cont-wrap .comt-cont-center .comt-single {
		float: left;
		width: 561px;
		height: 149px;
		margin: 0 20px 18px 0;
		background: url("../assets/img/commet_sigle_bg.png") center no-repeat;
	}

	.comt-wrap .comt-cont-wrap .comt-cont-center .comt-single img {
		display: inline-block;
		position: relative;
		top: 5px;
    	left: 5px;
	}

	.comt-wrap .comt-cont-wrap .comt-cont-center .comt-single p {
		display: inline-block;
		position: relative;
		top: -34px;
    	left: 40px;
		width: 346px;
		height: 64px;
		color: #fff;
		font-size: 14px;
		line-height: 21.18px;
		overflow: hidden;
		letter-spacing: 0.2px;
	}

	.comt-wrap #want-add {
		display: block;
		width: 155px;
		height: 56px;
		border: 0;
		margin: 25px auto;
		background: url("../assets/img/add.png") center no-repeat;
		cursor: pointer;
	}
</style>