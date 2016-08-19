# phone_web
手机端的一些自己编写的页面

用light7编写的页面，因为支持jquery，所以便使用了。后续会换成SUI或MUI，使用支持触摸的zepto.

问题：

  * 使用HTML5的新特性history.pushState()和history.replaceState()函数实现无刷新改变页面以及URL。这两个API的使用可以[看这里](http://blog.csdn.net/oyiboy/article/details/44258477)
    
  * light7使用的自身路由，导致使用侧边栏时，跳转到下一个页面不出现侧边栏，返回时也必须多次点击才能消除URL中的#ID，这个问题有待后续解决
