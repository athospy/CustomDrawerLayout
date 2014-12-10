CustomDrawerLayout
==================

An android Navigation Drawer Layout that delegate gestures to your activity instead off eating it compleatly.



Usage
=====


XML
----

<py.com.mambo.CustomDrawerLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:id="@+id/drawer_layout"
    android:layout_width="match_parent"
    android:layout_height="match_parent">
    
    
</py.com.mambo.CustomDrawerLayout>




in activity
-----------

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        CustomDrawerLayout._activity=this;
        
        
    }
        
        
        
        
