### css 重置 ###
	@charset "utf-8";  
	/*  
	  Document   : CSS样式初始化  
	  Created on : 2016. 8. 7,09:41:00  
	  Author :  
	  Description:  
	  CSS样式表的初始化，全局样式设置。部分样式属性请根据具体页面重置其属性  
	      导入方式：<link href="css/common.css" rel="stylesheet" type="text/css" /> */  
	/* reset */  
	
    * {
        font-family: "Arial", "microsoft yahei"; 
        margin: 0; 
        padding: 0; 
        box-sizing: border-box; 
        -webkit-box-sizing: border-box; 
        -moz-box-sizing: border-box; 
        border:none;
    }
    
    html, body {
      font-size: 12px; //全局默认文字大小
      font-family: "Arial", "microsoft yahei";
      color: #333;
      background-color:#fff;
      width:100%;
      height:100%; 
    }
    
    h2,h3{ font-weight:bold;}
    
    a, a:link, a:visited, a:hover, a:active{
        text-decoration:none;
    }
    
    ul,ul li{list-style:none;}
    
    .clearfix:after{
      content: " ";
      display: block;
      clear: both;
      height: 0;
    }
    .clearfix{
      zoom: 1;
    }

		
 
