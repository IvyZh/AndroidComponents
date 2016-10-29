# Android_EditText

## 改变光标的颜色
*  设成和文字一样的颜色

	`android:textCursorDrawable="@null" ` 

* 改变为其他颜色

    `android:textCursorDrawable="@drawable/edittext_cursor"`


	- edittext_cursor.xml

			<?xml version="1.0" encoding="utf-8"?>  
			<shape xmlns:android="http://schemas.android.com/apk/res/android" >  
			    <size android:width="2dp" />  
			    <solid android:color="#BDC7D8" />  
			</shape>  