# Android_Edu

## 안드로이드 앱 만들기 #1 (TextView) - 쉽게 앱 만드는 방법 (현직 개발자 설명) , android studio easy tutorial

[안드로이드 앱 만들기 #1 (TextView) - 쉽게 앱 만드는 방법 (현직 개발자 설명) , android studio easy tutorial - YouTube](https://www.youtube.com/watch?v=wZdImPoFjW8&list=PLC51MBz7PMyyyR2l4gGBMFMMUfYmBkZxm&index=2)

MainActivity.java를 건들이지 않고 activity_main.xml의 내부 코드를 수정 및 작성하여 작업하였다.

초반에 android.support.constraint.ConstraintLayout 을 LinearLayout으로 바꾸었다.

이후 내부에 <TextView /> 를 선언하여

```xml
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    tools:context=".MainActivity">

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="인정...?"
        android:textColor="#ff0000"
        android:textSize="40sp" />

    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="안녕하신지요?"
        android:textColor="#3CBC06"
        android:textSize="20sp" />

</LinearLayout>
```

다음과 같이 코드를 작성하였다.

```xml
    <TextView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="인정...?"
        android:textColor="#ff0000"
        android:textSize="40sp" />
```

이 부분에서

android:layout_width는 가로 길이 설정, android:layout_height는 세로 길이 설정, android:text는 보여지는 텍스트 설정, android:textColor는 텍스트 색상 설정, android:textSize는 텍스트 크기 설정이다.

