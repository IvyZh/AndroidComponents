#ExpandableListView


## 去掉ExpandableListView的箭头图标
* settingLists.setGroupIndicator(null);  


## 指定各组内各子列表之间的分割条
* android:childDivider="@drawable/list_divider_lr"

* list_divider_lr

		<?xml version="1.0" encoding="utf-8"?>
		<inset xmlns:android="http://schemas.android.com/apk/res/android"
		    android:insetLeft="@dimen/margin_lr"
		    android:insetRight="@dimen/margin_lr">
		
		    <shape android:shape="rectangle">
		        <solid android:color="@color/divide_color" />
		    </shape>
		
		</inset>


## 调整ExpandableListView item的间距
* android:dividerHeight="10dp"