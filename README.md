# AlipayHome
项目介绍：实现原理(一个CoordinatorLayout嵌套AppBarLayout再嵌套CollapsingToolbarLayout再嵌套Toolbar的布局)
1、CoordinatorLayout嵌套AppBarLayout，这是为了让头部导航栏能够跟随内容视图下拉而展开，跟随内容视图上拉而收缩。这个内容视图可以是RecyclerView，也可以是NestedScrollView；
2、AppBarLayout嵌套CollapsingToolbarLayout，这是为了定义导航栏下面需要展开和收缩的部分视图；
3、CollapsingToolbarLayout嵌套Toolbar，这是为了定义导航栏上方显示的搜索区域或小图标区域，其中Toolbar还要定义两个不同的样式布局，用于分别显示搜索区域或小图标区域。



高仿支付宝首页的头部伸缩动画(使用design实现效果,CoordinatorLayout+AppBarLayout+CollapsingToolbarLayout+Toolbar)
