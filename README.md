一、数据库设计
       表名	            描述	                               所属模块

    customerList	客户评价列表	                           客户评价模块
    evaluation	    客户评价详情表（关联客户评价列表）      	 客户评价模块
    customerPhoto	客照欣赏表	                               客照欣赏模块
    travel_image	旅拍城市列表	                           旅拍城市模块
    city_carousel	城市列表	                                首页模块

二、后台API列表
   接口地址	
   http://127.0.0.1:3000/city                     获取首页city轮播的数据
   http://127.0.0.1:3000/customerphoto            获取首页customer轮播的数据
   http://127.0.0.1:3000/travel                   获取旅拍城市页面城市名称的数据 
   http://127.0.0.1:3000/travelList               获取旅拍城市列表页面的数据    
   http://127.0.0.1:3000/photoShow                获取客照欣赏页面数据
   http://127.0.0.1:3000/photoList                获取客照欣赏列表页面数据  
   http://127.0.0.1:3000/list                     获取客户评价列表页面数据
   http://127.0.0.1:3000/details                  获取客户评价详情页的数据
   http://127.0.0.1:3000/li                       查询客户评价详情页右边列表的数据（当前页以及下两页）

三、前端功能描述
	1.通过浏览网站，查看最新的风光照片，来了解地方景色；
	2.通过整体网站浏览以及公司和摄影师的介绍，了解摄影团队的实力，为自己的选择作参考；
	3.与客服交流，进一步了解详细信息；
	4.成为会员后，登陆公司分配的账号，可选择下载自己的旅拍照片，发表旅拍感受。

四、职责划分
   考虑：考虑到大家以后都从事前端开发工作，侧重点在前端，所以采取纵向开发的分工方式，按照功能模块进行了分工，所以开发过程中前端页面，数据接口，数据库表的设计都会涉及到。
   具体分工：
        邓  轩：首页及所需接口  
        张  鑫：客照欣赏及所需接口和数据表
        张沥丹：客户评论及所需接口和数据表 
        师  念：旅拍城市及所需接口和数据表


五、项目运行方式
    前端：在bj_app目录下npm run serve
    后端：在bj_server目录下 node app.js
    数据库：启动XAMPP,打开Apache和MySQL

