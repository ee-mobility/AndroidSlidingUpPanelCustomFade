# AndroidSlidingUpPanelCustomFade

This fork disables percentual fading of the view covered by the panel before the anchor point is reached.

To use, make sure you have jitpack in your `root build.gradle`

```
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}
```

And then add this in your app `build.gradle`

```
implementation 'com.github.dariobanfi:AndroidSlidingUpPanelCustomFade:3.3.4'
```
