# RippleDemo

----
##1、xml
```java
<library.RippleBackground
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:id="@+id/content"
    app:rb_color="#ff0000"
    app:rb_radius="32dp"
    app:rb_rippleAmount="6"
    app:rb_duration="3000"
    app:rb_scale="6"/>
```

##2、代码
```java

 RippleBackground rippleBackground=(RippleBackground)findViewById(R.id.content);
 
 rippleBackground.startRippleAnimation();
 
 rippleBackground.stopRippleAnimation();
 
```



------
![image](https://github.com/xusoku/RippleDemo/blob/master/Screenshot_2016-05-11-15-19-39.jpg)
