<template>
	<div class="pg-5">
		<div class="center">
			<div class="award-wrap">
				<div class="award-title">
					<div class="award-title-png"></div>
				</div>
				<div class="award-cont-wrap">
					<ul>
						<li class="award-module">
							<a href="javascript:;" target="_blank">
								<div style="width: 100%; height: 100%;">
									<div class="award-img"></div>
									<div class="award-cont">
										<div class="award-price">300 Q币</div>
										<div class="award-num">1人</div>
									</div>
								</div>
							</a>
						</li>
						<li class="award-module">
							<a href="javascript:;" target="_blank">
								<div style="width: 100%; height: 100%;">
									<div class="award-img"></div>
									<div class="award-cont">
										<div class="award-price">300 Q币</div>
										<div class="award-num">1人</div>
									</div>
								</div>
							</a>
						</li>
						<li class="award-module">
							<a href="javascript:;" target="_blank">
								<div style="width: 100%; height: 100%;">
									<div class="award-img"></div>
									<div class="award-cont">
										<div class="award-price">300 Q币</div>
										<div class="award-num">1人</div>
									</div>
								</div>
							</a>
						</li>
						<li class="award-module">
							<a href="javascript:;" target="_blank">
								<div style="width: 100%; height: 100%;">
									<div class="award-img"></div>
									<div class="award-cont">
										<div class="award-price">300 Q币</div>
										<div class="award-num">1人</div>
									</div>
								</div>
							</a>
						</li>												
					</ul>
				</div>
			</div>
		</div>
	</div>
</template>

<script>

</script>

<style scoped>
	.pg-5 {
		min-width: 1200px;
		height: 488px;
		background: url('../assets/img/bg_05.jpg') center no-repeat;
	}

	.center {
		width: 1200px;
		padding-top: 34px;
		margin: 0 auto;
		overflow: hidden;
	}

	.award-wrap {
		width: 100%;
	}

	.award-wrap .award-title {
		width: 100%;
		height: 77px;
		border-top: 2px solid #00a3ef;
		background-color: #1f2941;
	}	

	.award-wrap .award-title .award-title-png {
		position: relative;
    	top: -2px;		
		width: 220px;
		height: 64px;
		margin: 0 auto;
		background: url("../assets/img/content_06.png") center no-repeat;
	}

	.award-wrap .award-cont-wrap {
		width: 100%;
		height: 337px;
		margin-top: 2px;
		background-color: #121b38;
	}

	.award-wrap .award-cont-wrap ul {
		height: 168px;
		padding: 84px 0 0 57px;
	}

	.award-wrap .award-cont-wrap .award-module {
		float: left;
		width: 246px;
		height: 165px;
		border: 1px solid #2a354c;
		margin-right: 22px;
		background: #0f162c;
		box-shadow: inset 0px 0px 20px 4px #0e1428;
		position: relative;
	}

	.award-wrap .award-cont-wrap .award-module .award-img {
		display: block;
		width: 100%;
		height: 100%;
		background: url("../assets/img/Award_01.png") 32px 18px no-repeat;
	}

	.award-wrap .award-cont-wrap .award-module .award-cont {
		position: absolute;
		bottom: 12px;
		width: 100%;
		height: 32px;
		text-align: center;
		background-color: rgba(22, 34, 67, .8);
	}

	.award-wrap .award-cont-wrap .award-module .award-cont .award-price {
		display: inline-block;
		color: #fff;
		font-size: 14px;
		line-height: 32px;
	}

	.award-wrap .award-cont-wrap .award-module .award-cont .award-num {
		display: inline-block;
		margin-left: 16px;
		color: #a0a0a0;
		font-size: 14px;
		line-height: 32px;
	}
</style>
