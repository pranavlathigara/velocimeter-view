Velocimeter
-----------------
//TODO badges

A velocimeter View for Android


![Demo Screenshot][1]

![Demo Screenshot][2]

### Sample video:

[Youtube Velocimeter video](http://youtu.be/umTOKLu2syg)

### Sample app:

<a href="https://play.google.com/store/apps/details?id=com.github.glomadrian.velocimeter">
  <img alt="Get it on Google Play"
       src="https://developer.android.com/images/brand/en_generic_rgb_wo_60.png" />
</a>


How to use
----------

Default colors
```xml
<com.github.glomadrian.velocimeterlibrary.VelocimeterView
       android:layout_gravity="center"
       android:id="@+id/velocimeter"
       android:layout_width="match_parent"
       android:layout_height="0dp"
       android:layout_weight="1"
       />
```

With custom colors and attributes
```xml
<com.github.glomadrian.velocimeterlibrary.VelocimeterView
        android:layout_gravity="center"
        android:id="@+id/velocimeter2"
        android:layout_width="match_parent"
        android:layout_height="0dp"
        android:layout_weight="1"
        app:inside_progress_color="@color/inside_progress"
        app:external_progress_color="@color/external_progress"
        app:progress_blur_color="@color/external_progress"
        app:bottom_velocimeter_color="@color/bottom_velocimeter"
        app:internal_velocimeter_color="@color/internal_velocimeter"
        app:needle_color="@color/needle"
        app:needle_blur_color="@color/needle"
        app:digital_number_color="@color/digital_number"
        app:digital_number_blur_color="@color/digital_number"
        app:max="100"
        app:units="kmh"
        />
```

Remember put this for custom attribute usage

```java

xmlns:app="http://schemas.android.com/apk/res-auto"

```


For Gradle
---------------------

Add repository

```groovy
repositories {
  maven {
    url "http://dl.bintray.com/glomadrian/maven"
  }
}
```
Add dependency
```groovy
compile 'com.github.glomadrian:velocimeter-view:1.0@aar'
```
Developed By
------------
Adrián García Lomas - <glomadrian@gmail.com>
* [Twitter](https://twitter.com/glomadrian)
* [LinkedIn](https://es.linkedin.com/in/glomadrian )

License
-------

    Copyright 2015 Adrián García Lomas

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

[1]: ./art/velocimeter.png
[2]: ./art/velocimeter.gif
