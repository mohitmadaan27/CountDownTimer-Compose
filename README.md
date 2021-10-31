# Countdown timer
ComposeCountDownTimer


## :scroll: Description
Countdown timer built in Jetpack compose.


## :bulb: Motivation and Context
Uses jetpack compose animation API to fill up a circle while the timer counts down.

## :camera_flash: Screenshots
<img src="/results/screenshot_1.png" width="260">&emsp;<img src="/results/screenshot_2.png" width="260">

## Built With
* [Compose](https://developer.android.com/jetpack/androidx/releases/compose?gclid=Cj0KCQjw_fiLBhDOARIsAF4khR3idT9sGH2SW4JAgq2KaA6Wlnj0eshL7WLyUC-RqJ0amcJ4e65hSQUaAhj2EALw_wcB&gclsrc=aw.ds) - androidx.compose.
* [Android Jetpack lifecycle](https://developer.android.com/jetpack) - androidx.lifecycle:lifecycle-runtime-ktx.
* [Compose Ui Test](https://developer.android.com/jetpack/androidx/releases/compose?gclid=Cj0KCQjw_fiLBhDOARIsAF4khR3idT9sGH2SW4JAgq2KaA6Wlnj0eshL7WLyUC-RqJ0amcJ4e65hSQUaAhj2EALw_wcB&gclsrc=aw.ds) - androidx.compose.ui:ui-test-junit4.
* [Compose Material](https://developer.android.com/jetpack/androidx/releases/compose?gclid=Cj0KCQjw_fiLBhDOARIsAF4khR3idT9sGH2SW4JAgq2KaA6Wlnj0eshL7WLyUC-RqJ0amcJ4e65hSQUaAhj2EALw_wcB&gclsrc=aw.ds)  - androidx.compose.material:material.
* [Compose Ui](https://developer.android.com/jetpack/androidx/releases/compose?gclid=Cj0KCQjw_fiLBhDOARIsAF4khR3idT9sGH2SW4JAgq2KaA6Wlnj0eshL7WLyUC-RqJ0amcJ4e65hSQUaAhj2EALw_wcB&gclsrc=aw.ds)  - androidx.compose.ui:ui-tooling.

```groovy
    implementation 'com.google.android.material:material:1.4.0'
    implementation "androidx.activity:activity-compose:1.4.0"
    implementation "androidx.compose.ui:ui:$compose_version"
    implementation "androidx.compose.material:material:$compose_version"
    implementation "androidx.compose.material:material-icons-extended:$compose_version"
    implementation "androidx.compose.ui:ui-tooling:$compose_version"
    implementation 'androidx.lifecycle:lifecycle-runtime-ktx:2.4.0'

    testImplementation 'junit:junit:4.13.2'

    androidTestImplementation 'androidx.test.ext:junit:1.1.2'
    androidTestImplementation "androidx.compose.ui:ui-test-junit4:$compose_version"
```
