# ThemeDemo
It is a demo about Theme

这是一个关于怎么实现自定义主题风格的Demo。供交流分享和以及个人总结之用。代码在不断完善中。

###实现主题的过程：
实现主题，有不同的方式。先用其中一种方式来实现。

整体的步骤和思路是：


1. 在values 下建立 attr.xm定义属性。
2. 在values styles.xml 下定义主题，根据不同风格给同一属性赋不同值。
3. 在代码中setContent前调用setTheme实现主题。如：this.setTheme(R.style.NightTheme);

根据开发需要，主题的选择可根据偏好设定来实现的。因此这个Demo在实现主题的过程中。也是使用了偏好设定实现的。主要用了PreferenceFragment这个类。

感谢以下文章作者：
http://blog.csdn.net/brokge/article/details/41247965


