# html
  模板及标准

###  head

*  viewport 实现移动端的

  
       <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0, user-scalable=no" />
    
        width：控制 viewport 的大小，可以指定的一个值，如 600，或者特殊的值，如 device-width 为设备的宽度（单位为缩放为 100% 时的 CSS 的像素）。  
        height：和 width 相对应，指定高度。  
        initial-scale：初始缩放比例，也即是当页面第一次 load 的时候缩放比例。  
        maximum-scale：允许用户缩放到的最大比例。  
        minimum-scale：允许用户缩放到的最小比例。  
        user-scalable：用户是否可以手动缩放。  
