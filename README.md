ZrcListView
===========

一个顺滑又漂亮的Android下拉刷新与加载更多列表组件。

### 仿iOS列表项滑动菜单: ###
    1.滑动出现菜单，越界阻尼效果；
    2.删除列表项效果；

## 使用示例 ##

```xml
<zrc.widget.listitemmenu.ItemMenuView
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="wrap_content">

    <TextView
        android:id="@+id/delete"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:padding="20dp"
        android:text="删除"
        android:textColor="#ffffffff"
        android:textSize="20sp"
        android:background="#ffcc2500"/>
    <TextView
        android:id="@+id/info"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:padding="20dp"
        android:text="信息"
        android:textColor="#ffffffff"
        android:textSize="20sp"
        android:background="#ff308dff"/>
	<!-- 最后一项为列表项，其余为菜单项 -->
    <TextView
        android:id="@+id/item"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:padding="20dp"
        android:textSize="20sp"
        android:background="#ffffff"/>

</zrc.widget.listitemmenu.ItemMenuView>
```

##Screenshots
![Screenshot](https://raw.github.com/zarics/ListItemMenu/master/Screenshots/screenshot.png)