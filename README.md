# android-library-opencv

A Maven repository source of the Android Opencv library.

In Android Studio's build.gradle project file, add the following elements to your existing list of repositories and compile dependencies. Your project may have the repositories listed in a different build script than the dependencies, so add these where appropriate.

```
  repositories {
    maven { url 'https://raw.github.com/iParse/android-library-opencv/master/releases' }
  }
  
  dependencies {
    compile 'com.iparse.android:opencv:2.4.13.1'
  }
```
