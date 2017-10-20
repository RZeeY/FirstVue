<template>
	<div class="pg-6">
		<div class="center">
			<div class="rules-wrap">
				<div class="rules-title">
					<div class="rules-title-png"></div>
				</div>
				<div class="rules-cont-wrap">
					<div class="rules-cont-center">
						<div class="rules-condition-wrap">
							<p style="margin-bottom: 19px"><em>获奖条件</em>玩家正确回答所有问题即可参与抽奖，活动结束后从回答正确的玩家中抽取10名玩家，每位获得50QB奖励；</p>
							<p><em>活动时间</em>2016年10月27日-2016年11月7日；</p>
						</div>
						<div class="rules">
							<ul>
								<li class="rules-module">
									<p>参与答题玩家需登陆178账号，且每位玩家每天只有1次机会；</p>
								</li>
								<li class="rules-module">
									<p>请中奖玩家加入活动QQ群：123456789，以便后续联系以及奖励领取；</p>
								</li>
								<li class="rules-module">
									<p>参与截图评论活动玩家须上传在起点中文网《最后一个使徒》阅读/评论/收藏截图，并附上自己对小说内容的评价或者自己对于小说后续继续保留的人物或武器的相应看法；</p>
								</li>
								<li class="rules-module">
									<p>我们会在活动结束后公布获奖人员名单，点击下方查看获奖名单即可进行查询；</p>
								</li>
								<li class="rules-module">
									<p>我们会在活动结束后公布获奖人员名单，点击下方查看获奖名单即可进行查询；</p>
								</li>
								<li class="rules-module">
									<p>每位玩家仅可获取1次奖励，多次参与答题和评论也只能获取1份奖励；</p>
								</li>
							</ul>
						</div>
						<div class="notes">* 本次活动最终解释权归178和官网所有。</div>
						<button id="award-list-btn"></button>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>

</script>

<style scoped>
	.pg-6 {
		min-width: 1200px;
		height: 817px;
		background: url('../assets/img/bg_06.jpg') center no-repeat;
	}

	.center {
		width: 1200px;
		padding-top: 34px;
		margin: 0 auto;
		overflow: hidden;
	}

	.rules-wrap {
		width: 100%;
	}

	.rules-wrap .rules-title {
		width: 100%;
		height: 77px;
		border-top: 2px solid #00a3ef;
		background-color: #1f2941;
	}

	.rules-wrap .rules-title .rules-title-png {
		position: relative;
    	top: -2px;
		width: 220px;
		height: 64px;
		margin: 0 auto;
		background: url("../assets/img/content_07.png") center no-repeat;
	}

	.rules-wrap .rules-cont-wrap {
		width: 100%;
		height: 562px;
		margin-top: 2px;
		background-color: #121b38;
	}

	.rules-wrap .rules-cont-wrap .rules-cont-center {
		width: 1100px;
		height: 340px;
		padding: 70px 0 0 62px;
	}

	.rules-wrap .rules-cont-wrap .rules-cont-center .rules-condition-wrap {

	}

	.rules-wrap .rules-cont-wrap .rules-cont-center .rules-condition-wrap p {
		font-size: 14px;
		color: #f0f1f2;
	}

	.rules-wrap .rules-cont-wrap .rules-cont-center .rules-condition-wrap p em {
		padding: 3.5px 7px;
		margin-right: 12px;
		border-radius: 2px 2px;
		font-size: 14.5px;
		color: #000;
		background-color: #3fb8ff;
	}

	.rules-wrap .rules-cont-wrap .rules-cont-center .rules {
		margin-top: 21px;
	}

	.rules-wrap .rules-cont-wrap .rules-cont-center .rules .rules-module {
		margin-bottom: 24px;
	}

	.rules-wrap .rules-cont-wrap .rules-cont-center .rules .rules-module p {
		padding-left: 17px;
		font-size: 14px;
		color: #f0f1f2;
		background: url("../assets/img/point.png") left no-repeat;
	}

	.rules-wrap .rules-cont-wrap .rules-cont-center .notes {
		display: block;
		font-size: 12px;
		color: #fff;
	}

	#award-list-btn {
		display: block;
		width: 155px;
		height: 56px;
		border: 0;
		margin: 56px auto 0;
		background: url("../assets/img/award_list.png") center no-repeat;
		cursor: pointer;
	}
</style>
