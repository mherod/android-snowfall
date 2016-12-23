Android-Snowfall
================

[![Release](https://jitpack.io/v/jetradarmobile/android-snowfall.svg)](https://jitpack.io/#jetradarmobile/android-snowfall)

Implementation of Snowfall view.


Compatibility
-------------

This library is compatible from API 15 (Android 4.0.3).


Download
--------

Add it in your root build.gradle at the end of repositories:

```groovy
allprojects {
    repositories {
        ...
        maven { url "https://jitpack.io" }
    }
}
```

Add the dependency

```groovy
dependencies {
    compile 'com.github.jetradarmobile:android-snowfall:1.0.0'
}
```


Usage
-----

```xml
<com.jetradarmobile.snowfall.SnowfallView
      android:layout_width="match_parent"
      android:layout_height="match_parent"
      app:snowflakesNum="150"
      app:snowflakeAlphaMin="150"
      app:snowflakeAlphaMax="250"
      app:snowflakeSizeMin="2dp"
      app:snowflakeSizeMax="8dp"
      app:snowflakeFadingEnabled="false"/>
```


License
-------

    Copyright 2016 JetRadar

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
    
       http://www.apache.org/licenses/LICENSE-2.0
    
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
