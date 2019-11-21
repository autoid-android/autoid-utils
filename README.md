# autoid-utils
## Usage:
### project.gradle:

```java
  allprojects {
      repositories {
          maven { url "https://raw.githubusercontent.com/autoid-android/autoid-utils/master" }
      }
  }
```

### app.gradle

```java
  implementation 'com.autoid:autoidutils:1.0.9'
```

## Tree:

```
    .
    ├── activities
    │   ├── BaseActivity.java
    │   ├── BaseSettingsActivity.java
    │   └── BaseSignInActivity.java
    ├── adapters
    │   └── BaseAdapter.java
    ├── models
    │   └── BaseRequestResult.java
    ├── net
    │   └── BaseRequestManager.java
    ├── utils
    │   ├── CommonUtil.java
    │   ├── LogUtil.java
    │   └── ThreadPool.java
    ├── views
    │    ├── ScrollingTextView.java
    │    └── TopBar.java
    ├── Application.java
```

### Current Dependency

```java
    api 'androidx.appcompat:appcompat:1.1.0-beta01'
    api 'androidx.recyclerview:recyclerview:1.0.0'
    api 'androidx.cardview:cardview:1.0.0'
    api 'com.google.android.material:material:1.1.0-alpha07'
    api 'androidx.constraintlayout:constraintlayout:2.0.0-beta1'
    //异步任务
    api 'io.reactivex.rxjava2:rxandroid:2.0.1'
    api 'io.reactivex.rxjava2:rxjava:2.1.0'
    //网络加载
    api 'com.squareup.retrofit2:retrofit:2.3.0'
    api 'com.squareup.retrofit2:converter-gson:2.3.0'
    api 'com.squareup.retrofit2:adapter-rxjava2:2.3.0'
    //异常捕获
    api 'cat.ereza:customactivityoncrash:2.2.0'
    api files('libs/register-release.aar')
```
