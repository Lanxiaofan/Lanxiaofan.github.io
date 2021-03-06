---
layout:     post
title:      "RelativeLayout的属性"
subtitle:   " \"基础xml的布局\""
date:       2019-01-16 14:10:00
author:     "Lanxiaofan"
catalog: true
tags:
    - Android
    - RelativeLayout属性
---

> “关于Android的xml的常见布局有5大布局：LinearLayout(线性布局)、FrameLayout(单帧布局)、AbsoluteLayout(绝对布局)、TablelLayout(表格布局)、RelativeLayout(相对布局)，其中又以LinearLayout和RelativeLayout用途最为广泛，本文章主要介绍RelativeLayout布局下的属性，个人推荐不要死记硬背，先粗略扫一遍，用到的时候去记就好了，忘了也没关系，可以再去查，重点是知道有这么一个东西”


## RelativeLayout布局属性

* 第一组属性 <br> 
android:layout_below <br> 
android:layout_above <br>
android:layout_toLeftOf <br>
android:layout_toRightOf <br>
这组属性的layout_below就是将目标控件的上边缘与引用控件的下边缘对齐，layout_toRightOf就是将目标控件的左边缘与引用控件的右边缘对齐。 <br> 

* 第二组属性 <br> 
android:layout_alignTop <br>
android:layout_alignBottom <br>
android:layout_alignLeft <br>
android:layout_alignRight <br>
android:layout_alignBaseLine <br>
顾名思义，layout_alignTop就表示目标控件和引用控件的上边缘对齐，layout_alignLeft则表示目标控件与引用控件的左边缘对齐，layout_alignBaseLine是基于基准线对其，基准线就是我们写英文字母那4行线的第三条 <br> 

* 第三组属性 <br> 
layout_alignParentRight <br>
layout_alignParentLeft <br>
layout_alignParentTop <br>
layout_alignParentBottom <br>
这组属性的值是 true 或者 false，因为每个控件的直接父控件只有一个，所以用true/false来表示是否与父控件的边缘对齐 <br> 

* 第四组属性 <br> 
layout_centerInParent <br>
layout_centerVertical <br>
layout_centerHorizontal <br>
这组属性取值也是true或者false，layout_centerInParent表示与父控件在水平方向和垂直方向都对齐，处于正中央，layout_centerVertical表示与父控件在垂直方向上对其，layout_centerHorizontal表示与父控件在水平方向上对齐 <br>

* 第五组属性 <br> 
layout_alignStart <br>
layout_alignStop <br>
layout_alignParentStart <br>
layout_alignParentStop <br>
layout_alignStart <br>
这组属性的layout_alignStop是引用其他控件，表示与控件的开始位置、结束位置对齐，layout_alignParentStart, layout_alignParentStop取值为true、false，表示与父控件的开始，结束位置对齐




---



