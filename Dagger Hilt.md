# Dagger Hilt
Hilt는 Dagger2 기반의 안드로이드 전용 의존성 주입 라이브러리이다.

## Gradle 설정
project-level의 build.gradle에 추가한다
``` kotlin
dependencies {
  // other plugins...
  classpath 'com.google.dagger:hilt-android-gradle-plugin:2.44.2'
}
```

app-level의 build.gradle 파일에 추가한다.
``` kotlin
apply plugin: 'com.android.application'
apply plugin: 'com.google.dagger.hilt.android'

dependencies {
  implementation 'com.google.dagger:hilt-android:2.44.2'
  kapt 'com.google.dagger:hilt-compiler:2.44.2'
}  
```


### 참고
https://hyperconnect.github.io/2020/07/28/android-dagger-hilt.html      
https://developer.android.com/training/dependency-injection/hilt-android     
https://www.charlezz.com/?p=44230    