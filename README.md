<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
	<title>个人简历</title>
	<link rel="stylesheet" href="http://cdn.static.runoob.com/libs/bootstrap/3.3.7/css/bootstrap.min.css">
	<script src="http://cdn.static.runoob.com/libs/jquery/2.1.1/jquery.min.js"></script>
	<script src="http://cdn.static.runoob.com/libs/bootstrap/3.3.7/js/bootstrap.min.js"></script>
	<style type="text/css">
	html, body {width:100%;height:100%;}
		.center{
			background-image: url("imgs/bg.jpg");
			background-attachment: fixed;
		}
		.carousel{
     height: 100%;
     /*height: auto;*/
     background-color: #000000;
    }
    .carousel .item{
     /*height: auto;*/
     height: 100%;
     background-color: #000000;
    }
    .carousel img{
     /*height: 360px;*/
     width: 100%;
    }
			</style>
</head>
<body class="center">
<div class="navbar navbar-inverse navbar-fixed-buttom" role="navigation">
<div class="navbar-header">
  <img class="navbar-brand" src="imgs/MY.jpg"/>
</div>
<ul class="nav nav-tabs" id="myTab">
  <li class="active"><a href="#home">首页</a></li>
  <li><a href="#Mylife">我的人生</a></li>
  <li><a href="#AttendSchool">求学之路</a></li>
  <li><a href="#LifePlanning">职业规划</a></li>
</ul>
</div>

<div class="tab-content">
  <div class="tab-pane active" id="home">
	<div class="row">
		<div class="col-sm-3 col-sm-offset-2">
		<H1 style="text-align: center; margin-bottom: 50px;"><span>这个我</span></H1>
		<table class="table table-hover">
		  <caption>个人介绍</caption>
		  <thead>
		    <tr>
		      <th>姓名</th>
		      <th>年龄</th>
		    </tr>
		  </thead>
		  <tbody>
		    <tr>
		      <td>卢天铭</td>
		      <td>21</td>
		    </tr>
		  </tbody>
		  <thead>
		    <tr>
		      <th>籍贯</th>
		      <th>现住址</th>
		    </tr>
		  </thead>
		  <tbody>
		    <tr>
		      <td>广东云浮</td>
		      <td>广州天河</td>
		    </tr>
		  </tbody>
		  <thead>
		    <tr>
		      <th>学历</th>
		      <th>专业</th>
		    </tr>
		  </thead>
		  <tbody>
		    <tr>
		      <td>大专</td>
		      <td>软件工程</td>
		    </tr>
		  </tbody>
		  <thead>
		    <tr>
		      <th>电话</th>
		      <th>邮箱</th>
		    </tr>
		  </thead>
		  <tbody>
		    <tr>
		      <td>13059329861</td>
		      <td>13059329861@163.com</td>
		    </tr>
		  </tbody>
		  <thead>
		    <tr>
		      <th colspan="2">我是酱紫的</th>
		    </tr>
		  </thead>
		  <tbody>
		    <tr>
		      <td colspan="2"><p>我是一个敢于拼搏的小青年，努力学习，敢于迎接挑战。之前找工作发现自己的不足，现在正在努力学习新知识，希望有公司能接纳我，让我为公司的发展出一份力。</p></td>
		    </tr>
		  </tbody>
		</table>
		</div>
		<div class="col-sm-3 col-sm-offset-1">
		<H1 style="text-align: center;">这些年的那个我</H1>
		<div id="myCarousel" class="carousel slide">
		    <!-- 轮播（Carousel）指标 -->
		    <ol class="carousel-indicators">
		        <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
		        <li data-target="#myCarousel" data-slide-to="1"></li>
		        <li data-target="#myCarousel" data-slide-to="2"></li>
		        <li data-target="#myCarousel" data-slide-to="3"></li>
		    </ol>   
		    <!-- 轮播（Carousel）项目 -->
		    <div class="carousel-inner">
		        <div class="item active">
		            <img src="imgs/life.jpg" alt="First slide">
		        </div>
		        <div class="item">
		            <img src="imgs/live.jpg" alt="Second slide">
		        </div>
		        <div class="item">
		            <img src="imgs/pss.jpg" alt="Third slide">
		        </div>
		        <div class="item">
		            <img src="imgs/psd.jpg" alt="Third slide">
		        </div>
		    </div>
		    <!-- 轮播（Carousel）导航 -->
		    <a class="carousel-control left" href="#myCarousel" 
		        data-slide="prev">&lsaquo;
		    </a>
		    <a class="carousel-control right" href="#myCarousel" 
		        data-slide="next">&rsaquo;
		    </a>
		</div>
		</div>
	</div>
  </div>
  <div class="tab-pane" id="Mylife">
  	<H1 style="text-align: center; margin-top: 50px;">我的人生历程</H1>
	<div class="panel-group" id="accordion" style="width: 700px; margin:50px auto 0px auto; ">
	    <div class="panel panel-primary">
	        <div class="panel-heading">
	            <h4 class="panel-title">
	                <a data-toggle="collapse" data-parent="#accordion" 
	                href="#collapseOne">
	                1996年2月
	                </a>
	            </h4>
	        </div>
	        <div id="collapseOne" class="panel-collapse collapse in">
	            <div class="panel-body">
	                我降世在一个并不富裕的家庭，这里有爱我的父母和姐姐。
	            </div>
	        </div>
	    </div>
	    <div class="panel panel-success">
	        <div class="panel-heading">
	            <h4 class="panel-title">
	                <a data-toggle="collapse" data-parent="#accordion" 
	                href="#collapseTwo">
	                2003年9月
	            </a>
	            </h4>
	        </div>
	        <div id="collapseTwo" class="panel-collapse collapse">
	        <div class="panel-body">
	            开始我的小学生活。
	        </div>
	        </div>
	    </div>
	    <div class="panel panel-info">
	        <div class="panel-heading">
	            <h4 class="panel-title">
	                <a data-toggle="collapse" data-parent="#accordion" 
	                href="#collapseThree">
	                2008年9月
	                </a>
	            </h4>
	        </div>
	        <div id="collapseThree" class="panel-collapse collapse">
	            <div class="panel-body">
	                因为村里的小学没有6年级，所以我转学到了镇上的小学上6年级，第一次离开家住宿舍。并在这里遇到了我第一个挚友。
	            </div>
	        </div>
	    </div>
	    <div class="panel panel-warning">
	        <div class="panel-heading">
	            <h4 class="panel-title">
	                <a data-toggle="collapse" data-parent="#accordion" 
	                href="#collapseFour">
	                2009年9月
	                </a>
	            </h4>
	        </div>
	        <div id="collapseFour" class="panel-collapse collapse">
	            <div class="panel-body">
	                这一年我升上了初中，到了县城中学上学，离家又远了，但是我很庆幸，在这里我遇到了一群好兄弟，陪伴我度过了我的中学生活。
	            </div>
	        </div>
	    </div>
	    <div class="panel panel-danger">
	        <div class="panel-heading">
	            <h4 class="panel-title">
	                <a data-toggle="collapse" data-parent="#accordion" 
	                href="#collapseFive">
	                2012年6月
	                </a>
	            </h4>
	        </div>
	        <div id="collapseFive" class="panel-collapse collapse">
	            <div class="panel-body">
	                第一次外出打暑假工，结果到地方才发现被骗了，不过我和同伴们还是机智地逃了出去并找到了一份还可以的暑假工。这是我第一次自己长时间离家到别的城市，这一次经历让我重新认识了我所生活的社会。
	            </div>
	        </div>
	    </div>
	    <div class="panel panel-info">
	        <div class="panel-heading">
	            <h4 class="panel-title">
	                <a data-toggle="collapse" data-parent="#accordion" 
	                href="#collapseSix">
	                2012年9月
	                </a>
	            </h4>
	        </div>
	        <div id="collapseSix" class="panel-collapse collapse">
	            <div class="panel-body">
	                高中生活开始，离家久了也就习惯了，从独自一人到认识新朋友，最后找到志同道合的死党，人生就是如此。
	            </div>
	        </div>
	    </div>
	    <div class="panel panel-success">
	        <div class="panel-heading">
	            <h4 class="panel-title">
	                <a data-toggle="collapse" data-parent="#accordion" 
	                href="#collapseSeven">
	                2015年9月
	                </a>
	            </h4>
	        </div>
	        <div id="collapseSeven" class="panel-collapse collapse">
	            <div class="panel-body">
	                第一次到广州读书居住，一切都是那么的新鲜和陌生，还好有亲切的同学助班和老师，我并不寂寞。
	            </div>
	        </div>
	    </div>
	    	    <div class="panel panel-warning">
	        <div class="panel-heading">
	            <h4 class="panel-title">
	                <a data-toggle="collapse" data-parent="#accordion" 
	                href="#collapseEight">
	                现在
	                </a>
	            </h4>
	        </div>
	        <div id="collapseEight" class="panel-collapse collapse">
	            <div class="panel-body">
	                找工作，找了一段时间，发现越是面试的多公司了就越发现自己的不足，果然是学习不能停啊。
	                现在正在努力学习新知识提高自己ing。
	            </div>
	        </div>
	    </div>
	</div>
  </div>
  <div class="tab-pane" id="AttendSchool">
		<section id="experience" class="myexperties">
		    <div class="container">
		        <div class="heading" style="text-align: center;">
		        <h2>我的人生</h2>
		        <h3>我仍在前进道路中</h3>        
		      </div>
		        
		        <div class="row media well">
		            <div class="col-xs-12 col-sm-3 col-md-3 col-lg-3">
		                <div class="expertiesico">
		                <br>
		                    2015年9月<br>2016年1月
		                </div>
		            </div>
		            <div class="expertiesdesc col-xs-12 col-sm-9 col-md-9 col-lg-9">
		            	<H4>大一第一学期</H4>
		            	<H5>HTML</H5>
		               <p>第一次学习HTML，并用了一个学期的时间学习，到期末制作了我的第一个HTML网页。</p>
		            </div>
		        </div>
		        <div class="row media well">
		            <div class="col-xs-12 col-sm-3 col-md-3 col-lg-3">
		                <div class="expertiesico">
		                <br>
		                    2016年2月<br>2016年7月
		                </div>
		            </div>
		            <div class="expertiesdesc col-xs-12 col-sm-9 col-md-9 col-lg-9">
		              	<H4>大一第二学期</H4>
		            	<H5>CSS、JS</H5>
		                <p>接触CSS和js,一边学习一边按照老师的要求制作各种JS响应效果，学期作品是结合网上资料制作的一个简单的响应式网页</p>
		            </div>
		        </div>
		        <div class="row media well">
		            <div class="col-xs-12 col-sm-3 col-md-3 col-lg-3">
		                <div class="expertiesico">
		                <br>
		                    2016年9月<br>2017年7月
		                </div>
		            </div>
		            <div class="expertiesdesc col-xs-12 col-sm-9 col-md-9 col-lg-9">
		              	<H4>大二一年</H4>
		            	<H5>WEB、PHP、ASP、JQ</H5>
		                <p>这一年学习了WEB、PHP、ASP、JQ等课程，前段后台略有涉猎。</p>
		            </div>
		        </div>
		        <div class="row media well">
		            <div class="col-xs-12 col-sm-3 col-md-3 col-lg-3">
		                <div class="expertiesico">
		                <br>
		                    2017年7月<br>至今
		                </div>
		            </div>
		            <div class="expertiesdesc col-xs-12 col-sm-9 col-md-9 col-lg-9">
		              	<H4>暑假</H4>
		            	<H5>Bootstrap</H5>
		                <p>确定了今后要走的路，巩固学过的知识并接触学习新的前端知识，如Bootstrap</p>
		            </div>
		        </div>
		    </div>
		  </section>
  </div>
  <div class="tab-pane" id="LifePlanning">
	<div class="nav navbar">
	<section id="experience" class="myexperties">
	    <div class="container">
	        <div class="heading" style="text-align: center;">
	        <h2 style="">职业规划</h2>
	        <h3>我前进的道路</h3>        
	      </div>
	        
	        <div class="row media well">
	            <div class="col-xs-12 col-sm-3 col-md-3 col-lg-3">
	                <div class="expertiesico">
	                <br>
	                    2017年<br>2019年
	                </div>
	            </div>
	            <div class="expertiesdesc col-xs-12 col-sm-9 col-md-9 col-lg-9">
	            	<H4>巩固</H4>
	            	<H5>进阶</H5>
	               <p>我准备用两年时间巩固学过的知识并完成进阶。<br>
					因为行业的更新换代很快，所以跟上发展步伐很重要，作为一个新人，我准备用2年时间来进阶。
	               </p>
	            </div>
	        </div>
	                <div class="row media well">
	                    <div class="col-xs-12 col-sm-3 col-md-3 col-lg-3">
	                        <div class="expertiesico">
	                        <br>
	                            2019年<br>2026年
	                        </div>
	                    </div>
	                    <div class="expertiesdesc col-xs-12 col-sm-9 col-md-9 col-lg-9">
	                    	<H4>上升</H4>
	                    	<H5>向前</H5>
	                       <p>我给自己的目标是30岁之前做到项目负责人的位置，把握住这青春年岁。</p>
	                    </div>
	                </div>
	                <div class="row media well">
	                    <div class="col-xs-12 col-sm-3 col-md-3 col-lg-3">
	                        <div class="expertiesico">
	                        <br>
	                            2026年<br>2036年
	                        </div>
	                    </div>
	                    <div class="expertiesdesc col-xs-12 col-sm-9 col-md-9 col-lg-9">
	                    	<H4>前进</H4>
	                    	<H5>前进</H5>
	                       <p>我希望能在40岁之前做到项目总监的位置，我会为此而努力拼搏。</p>
	                    </div>
	                </div>
	        </div>
	        </section>
	</div>
  </div>
</div>

<script>
  $(function () {
    $('#myTab a:last').tab('show');
  })
  $('#myTab a').click(function (e) {
  e.preventDefault();
  $(this).tab('show');
})
</script>
</body>
</html>
