# super_ijkplayer

[![](https://jitpack.io/v/iamdennisme/super_ijkplayer.svg)](https://jitpack.io/#iamdennisme/super_ijkplayer)

custom ijkplayer support more format and https

## Download

- Add it in your root build.gradle at the end of repositories:

```
allprojects {
    repositories {
        maven { url 'https://jitpack.io' }
    }
}
```

- Add the dependency

```
dependencies {
    implementation 'com.github.iamdennisme.super_ijkplayer:ijkplayer-arm64:1.0'
    implementation 'com.github.iamdennisme.super_ijkplayer:ijkplayer-armv5:1.0'
    implementation 'com.github.iamdennisme.super_ijkplayer:ijkplayer-armv7a:1.0'
    implementation 'com.github.iamdennisme.super_ijkplayer:ijkplayer-exo:1.0'
    implementation 'com.github.iamdennisme.super_ijkplayer:ijkplayer-java:1.0'
    implementation 'com.github.iamdennisme.super_ijkplayer:ijkplayer-x86:1.0'
    implementation 'com.github.iamdennisme.super_ijkplayer:ijkplayer-x86_64:1.0'

}
```

## Usage

same as ijkplayer

### proguard-rules
```
-keep class tv.danmaku.ijk.media.player.** {*;}
-keep class tv.danmaku.ijk.media.player.IjkMediaPlayer{*;}
-keep class tv.danmaku.ijk.media.player.ffmpeg.FFmpegApi{*;}
```

