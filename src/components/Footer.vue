<template>
	<footer>
		<div class="box">
			<div class="top">
				<ul>
					<li class="bilibili">
						<div class="title">bilibili</div>
						<ul>
							<li><a href="javascript:;">关于我们</a></li>
							<li><a href="javascript:;">练习我们</a></li>
							<li><a href="javascript:;">加入我们</a></li>
							<li><a href="javascript:;">友情链接</a></li>
							<li><a href="javascript:;">bilibili认证</a></li>
							<li><a href="javascript:;">Investor Relations</a></li>
						</ul>
					</li>
					<li class="portal">
						<div class="title">传送门</div>
						<ul>
							<li><a href="javascript:;">帮助中心</a></li>
							<li><a href="javascript:;">高级弹幕</a></li>
							<li><a href="javascript:;">活动专题页</a></li>
							<li><a href="javascript:;">侵权申诉</a></li>
							<li><a href="javascript:;">高级活动</a></li>
							<li><a href="javascript:;">用户反馈论坛</a></li>
							<li><a href="javascript:;">壁纸站</a></li>
							<li><a href="javascript:;">名人堂</a></li>
							<li><a href="javascript:;">专车号服务中心</a></li>
						</ul>
					</li>
					<li class="right">
						<a href="javascript:;" class="gf">
							<div></div>
							<span>客户端下载</span>
						</a>
						<a href="javascript:;" class="xl">
							<div></div>
							<span>新浪微博</span>
						</a>
						<a href="javascript:;" class="wx">
							<div></div>
							<span>官方微信</span>
						</a>
					</li>
				</ul>
			</div>
			<div class="bottom">
				<div class="bottom-left">
					<div></div>
					<div></div>
					<div></div>
				</div>
				<div class="bottom-right">
					<p>广播电视节目制作经营许可证：（沪）字第1248号 | 网络文化经营许可证：沪网文[2016]2296-134号 | 信息网络传播视听节目许可证：0910417 | 互联网ICP备案：沪ICP备13002172号-3 沪ICP证：沪B2-20100043 | 违法不良信息举报邮箱：help@bilibili.com | 违法不良信息举报电话：4000233233转3 | <a href="javascript:;">营业执照</a></p>
					<p> <a href="javascript:;">上海互联网举报中心</a> | 
						<a href="javascript:;">12318 全国文化市场举报网站</a> | 
						<a href="javascript:;">沪公网安备 31011002002436号</a> | 
						<a href="javascript:;">儿童色情信息举报专区</a> | 
						<a href="javascript:;">网上有害信息举报专区： 中国互联网违法和不良信息举报中心</a>
					</p>
					<p>亲爱的市民朋友，上海警方反诈劝阻电话“962110”系专门针对避免您财产被骗受损而设，请您一旦收到来电，立即接听。公司名称：上海宽娱数码科技有限公司 | 公司地址：上海市杨浦区政立路485号 | 电话：021-25099888</p>
				</div>
			</div>
		</div>
	</footer>
</template>

<script>
	export default {
		name:'Footer'
	}
</script>

<style scoped>
	li{
		list-style: none;
		float: left;
	}
	footer{
		/* float: left; */
		max-width: 100%;
		min-width: 1518px;
		background-color: #f6f9fa;
		padding-top: 40px;
		padding-bottom: 60px;
		margin: 0 auto;
	}
	.box{
		width: 980px;
		margin: 0 auto;
	}
	.top{
		width: 100%;
		margin-bottom: 30px;
	}
	.top>ul{
		width: 100%;
		height: 123px;
	}

	.bilibili{
		width: 290px;
		padding-right: 65px;
	}
	.title{
		margin-bottom: 22px;
		color: #c1b7bb;
	}
	.bilibili li{
		width: 33.33%;
		height: 30px;
		white-space: nowrap;
	}
	.portal{
		width: 270px;
		padding-left: 25px;
		padding-right: 55px;
		border-left: solid 1px #e5e9ef;
		border-right: solid 1px #e5e9ef;
	}
	.portal li{
		width: 33.33%;
		height: 30px;
		white-space: nowrap;
	}
	.right{
		padding-left: 25px;
		width: 248px;
	}
	.right a{
		float: left;
		width: 33.33%;
		text-align: center;
	}
	.right a div{
		width: 60px;
		height: 60px;
	}
	.gf div{
		margin: 0 auto;
		margin-bottom: 5px;
		background: url(../assets/img/icons.png) no-repeat -1024px -194px;
	}
	.xl div{
		margin: 0 auto;
		margin-bottom: 5px;
		background: url(../assets/img/icons.png) no-repeat -1024px -322px;
	}
	.wx div{
		margin: 0 auto;
		margin-bottom: 5px;
		background: url(../assets/img/icons.png) no-repeat -1024px -66px;
	}
	.bottom{
		width: 980px;
	}
	.bottom-left{
		float: left;
		width: 100px;
	}
	.bottom-left div:first-child{
		height: 80px;
		background: url(data:image/png;base64,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) no-repeat;
	}
	.bottom-left div:nth-child(2){
		background: url(../assets/img/pic962110.png);
		background-size: 100px 40px;
		height: 40px;
	}
	.bottom-left div:nth-child(3){
		background: url(../assets/img/confirm.png);
		background-size: 100px 40px;
		height: 40px;
	}
	.bottom-right{
		float: left;
		margin-left: 20px;
		width: 860px;
		line-height: 24px;
	}
	.bottom-right p{
		margin-bottom: 5px;
		color: #99a2aa;
		font-size: 12px;
	}
	.bottom-right p a{
		color: #99a2aa;
		font-size: 12px;
	}
</style>
