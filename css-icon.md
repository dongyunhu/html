### css 形状 ###

* 三角形（实心）

      		/*向上*/
		#triangle-up {
		    width: 0;
		    height: 0;
		    border-left: 50px solid transparent;
		    border-right: 50px solid transparent;
		    border-bottom: 100px solid red;
		}
		/*向下*/
		#triangle-down {
		    width: 0;
		    height: 0;
		    border-left: 50px solid transparent;
		    border-right: 50px solid transparent;
		    border-top: 100px solid red;
		}
		/*向右*/
		#triangle-right {
		    width: 0;
		    height: 0;
		    border-top: 50px solid transparent;
		    border-left: 100px solid red;
		    border-bottom: 50px solid transparent;
		}
		/*向左*/
		#triangle-left {
		    width: 0;
		    height: 0;
		    border-top: 50px solid transparent;
		    border-right: 100px solid red;
		    border-bottom: 50px solid transparent;
		}
		/*右下*/
		#triangle-bottomright {
		    width: 0;
		    height: 0;
		    border-bottom: 100px solid red;
		    border-left: 100px solid transparent;
		}

* 方向箭头
    	
		/*向右*/
		 #demo1{
		  position: relative;
		}
		#demo1:after, #demo16:before {
		  border: 10px solid transparent;
		  border-left: 10px solid #fff;
		  width: 0;
		  height: 0;
		  position: absolute;
		  top: 0;
		  right: -20px;
		  content: ' '
		}
		#demo1:before {
		  border-left-color: #f00;
		  right: -21px;
		}
      
