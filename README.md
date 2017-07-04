# SupperLayout
## 1.0 目标
* 增加居中功能
* 增加控件之间的依赖关系
* 移除space支持

>xml属性

```xml
<?xml version="1.0" encoding="utf-8"?>
 <!--suppress AndroidDomInspection -->
 <com.sumauto.SupperLayout
     xmlns:android="http://schemas.android.com/apk/res/android"
     xmlns:app="http://schemas.android.com/apk/res-auto"
     android:layout_width="match_parent"
     android:layout_height="match_parent"
     android:background="#fff"
     app:support_edit_mode="true"
     android:orientation="vertical"
     app:layout_height_units="1080"
     app:layout_width_units="1920">

     <ImageView
         android:src="#d91"
         app:heightUnits="160"
         app:widthUnits="160"
         app:x="50"
         app:y="50"
     />

     <TextView
         app:x="240"
         app:y="100"
         android:layout_width="match_parent"
         android:layout_height="wrap_content"
         android:text="SupperLayout"
         android:textColor="#000"
         app:textSizeUnits="40"/>

 </com.sumauto.SupperLayout>
```
1.优化EditMode下的显示效果
>dfewq
dfwer