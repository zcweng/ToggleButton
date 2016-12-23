ToggleButton
============

ToggleButton Widget For Android Developers

@Deprecated  
！！！项目已经停止维护，新项目移至https://github.com/zcweng/SwitchButton ！！！

<img src="https://github.com/zcweng/ToggleButton/blob/master/ToggleButtonSample/21879.gif"/>

<b>How To Use</b>
```xml
        xmlns:toggle="http://schemas.android.com/apk/res-auto"


        <com.zcw.togglebutton.ToggleButton
            android:layout_width="54dp"
            toggle:tbOnColor="#f00"
            toggle:tbOffColor="#ddd"
            toggle:tbSpotColor="#00f"
            toggle:tbOffBorderColor="#000"
            toggle:tbBorderWidth="2dp"
            android:layout_height="30dp" >
        </com.zcw.togglebutton.ToggleButton>
```

```java
        ToggleButton toggleBtn;
        
        //切换开关
        toggleBtn.toggle();
        //切换无动画
        toggleBtn.toggle(false);
        //开关切换事件
        toggleBtn.setOnToggleChanged(new OnToggleChanged(){
                @Override
                public void onToggle(boolean on) {
                }
        });
        
        toggleBtn.setToggleOn();
        toggleBtn.setToggleOff();
        //无动画切换
        toggleBtn.setToggleOn(false);
        toggleBtn.setToggleOff(false);
        
        //禁用动画
        toggleBtn.setAnimate(false);
```
Default Size:width=50dp,height=30dp.


<img src="https://github.com/zcweng/ToggleButton/blob/master/ToggleButtonSample/device-2014-08-31-231538.png" width="300" height="500"/>

<b>引用方式</b>
```
2016/8/3 17:04:53 
compile 'com.zcw:togglebutton-library:1.0.0'
```
