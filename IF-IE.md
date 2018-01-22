## 用于选择IE浏览器及IE的不同版本

### 语法：

      <!--[if <keywords>? IE <version>?]>
      HTML代码块
      <![endif]-->
      
### 取值：< keywords >
> if条件共包含6种选择方式：是否、大于、大于或等于、小于、小于或等于、非指定版本

> 是否：
> 指定是否IE或IE某个版本。关键字：空

> 大于：
>选择大于指定版本的IE版本。关键字：gt（greater than）

>大于或等于：
>选择大于或等于指定版本的IE版本。关键字：gte（greater than or equal）

>小于：
>选择小于指定版本的IE版本。关键字：lt（less than）

>小于或等于：
>选择小于或等于指定版本的IE版本。关键字：lte（less than or equal）

>非指定版本：
>选择除指定版本外的所有IE版本。关键字：!


### < version >
> 目前的常用IE版本为6.0及以上，推荐酌情忽略低版本，把精力花在为使用高级浏览器的用户提供更好的体验上

> **IE10及以上版本已将条件注释特性移除，使用时需注意。**
      
#### 如不想在非IE中看到某区域，可这样写：

      <!--[if IE]>
         <p>你在非IE中将看不到我的身影</p>
         <style>
            .test{color:red;}
         </style>
      <![endif]-->
      *述p代码块，将只在IE中可见*

#### 实例
    
      <!--[if IE 8]>
        <style>
        .ie8{display:inline;}
        </style>
      <![endif]-->
      
#### 不同版本
      
      ~ 小于或等于，示例代码：~

      <!--[if lte IE 7]>
      <style>
      .test{color:red;}
      </style>
      <![endif]-->
      *在上述代码中，只有IE7以下（含IE7），才能看到应用了test类的元素是红色文本。*
