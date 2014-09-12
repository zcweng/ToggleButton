ToggleButton
============

ToggleButton Widget For Android Devers

<img src="https://github.com/zcweng/ToggleButton/blob/master/ToggleButtonSample/21879.gif"/>

<b>How To Use</b>

        xmlns:toggle="http://schemas.android.com/apk/res-auto"


        <com.zcw.togglebutton.ToggleButton
            android:layout_width="54dp"
            toggle:onColor="#f00"
            toggle:offColor="#ddd"
            toggle:spotColor="#00f"
            toggle:offBorderColor="#000"
            toggle:borderWidth="2dp"
            android:layout_height="30dp" >
        </com.zcw.togglebutton.ToggleButton>


        
        
        ToggleButton toggleBtn;
        
        //切换开关
        toggleBtn.toggle();
        //开关切换事件
        toggleBtn.setOnToggleChanged(new OnToggleChanged(){
                @Override
                public void onToggle(boolean on) {
                }
        });
        
        toggleBtn.setToggleOn();
        toggleBtn.setToggleOff();
        


<img src="https://github.com/zcweng/ToggleButton/blob/master/ToggleButtonSample/device-2014-08-31-231538.png"/>
