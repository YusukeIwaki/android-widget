# android-widget

Some Android widgets.

## Custom font widgets

### FontAwesome

using [FontAwesome](http://fontawesome.io/)

```
repositories {
  maven { url 'https://jitpack.io' }
}

dependencies {
  compile 'com.android.support:appcompat-v7:25.1.1' // you can use any version.
  compile 'com.github.yusukeiwaki.android-widget:widget-fontawesome:0.0.1'
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

<img src="https://cloud.githubusercontent.com/assets/11763113/22398432/ea5b7e38-e5cb-11e6-8ca4-a323350911b3.png" width=240/>


### Material Design Iconic Font

using [Material Design Iconic Font](https://zavoloklom.github.io/material-design-iconic-font/)

```
repositories {
  maven { url 'https://jitpack.io' }
}

dependencies {
  compile 'com.android.support:appcompat-v7:25.1.1' // you can use any version.
  compile 'com.github.yusukeiwaki.android-widget:widget-material-design-font:0.0.1'
}
```

---

`MaterialDesignFontTextView` and `MaterialDesignFontButton` can be used as below:

```
    <io.github.yusukeiwaki.android.widget.MaterialDesignFontTextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_margin="4dp"
        android:text="@string/zmdi_search"
        android:textSize="24sp"
        />
```

**Remark** each icon name has `zmdi_` prefix.

<img src="https://cloud.githubusercontent.com/assets/11763113/22696274/c07b8456-ed90-11e6-9a73-e43a1c1d7101.png" width=240/>

## extras

```
repositories {
  maven { url 'https://jitpack.io' }
}

dependencies {
  compile 'com.github.yusukeiwaki.android-widget:widget-extras:0.0.1'
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
* The color is `colorControlNormal` (or textColorSecondary for API<21) with alpha=40%
