# android-widget

Some Android widgets.

## Custom font widgets

### FontAwesome

```
repositories {
  maven { url 'https://jitpack.io' }
}

dependencies {
  compile 'com.github.yusukeiwaki.android-widget:widget-fontawesome:0.0.0'
}
```

---

`FontAwesomeTextView` and `FontAwesomeButton` can be used as below:

```
    <io.github.yusukeiwaki.android.widget.FontAwesomeTextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_margin="4dp"
        android:text="@string/fa_twitter"
        android:textSize="24sp"
        />
```

## extras

```
repositories {
  maven { url 'https://jitpack.io' }
}

dependencies {
  compile 'com.github.yusukeiwaki.android-widget:widget-extras:0.0.0'
}
```

---

DividerView can be used as below:

```
    <io.github.yusukeiwaki.android.widget.DividerView
        android:layout_width="wrap_content"
        android:layout_height="match_parent"
        /><!-- divide horizontally -->

    <io.github.yusukeiwaki.android.widget.DividerView
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        app:thickness="2dp"
        /><!-- divide vertically -->
```

* The default thickness is `1dp`
* The color is `colorControlNormal` with alpha=40%