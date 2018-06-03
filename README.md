# WeChat_tbk
微信小程序_淘宝客开发

# 配置
````JS
	{
	  "pages":[ //设置页面路径
	    "pages/index/index",	//首页
	    "pages/logs/logs",
      "pages/search/search",  //搜索
      "pages/member/member"   //会员（我的）

	  ],
	  "window":{    //设置默认页面的窗口表现
	    "backgroundTextStyle":"light",				//下拉 loading 的样式，仅支持 dark/light
	    "navigationBarBackgroundColor": "#ff5858",		//导航栏背景颜色，如"#000000"
	    "navigationBarTitleText": "物折购",			//导航栏标题文字内容
	    "navigationBarTextStyle":"black"			//导航栏标题颜色，仅支持 black/white
	  },
	  "tabBar": {   //设置底部 tab 的表现
	    "color": "#444",						//tab 上的文字默认颜色
	    "selectedColor": "#ff5858",				//tab 上的文字选中时的颜色
	    "backgroundColor": "#fff",				//tab 的背景色
	    "borderStyle": "white",					//tabbar上边框的颜色， 仅支持 black/white
	    "list": [
	      {
	        "pagePath": "pages/index/index",
	        "text": "首页",
	        "iconPath": "images/home.png",
	        "selectedIconPath": "images/home_click.png"
	      },
	      {
	        "pagePath": "pages/search/search",
	        "text": "搜索",
	        "iconPath": "images/search.png",
	        "selectedIconPath": "images/search_click.png"
	      },
	      {
	        "pagePath": "pages/member/member",
	        "text": "我的",
	        "iconPath": "images/member.png",
	        "selectedIconPath": "images/member_click.png"
	      }
	    ]
	  },
	  "networkTimeout": {		//设置网络超时时间
	    "request": 20000		//	wx.request的超时时间，单位毫秒，默认为：60000
	  },
	  "debug": true	//设置是否开启 debug 模式

	}
````