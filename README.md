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
  implementation 'com.autoid:autoidutils:1.0.6'
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
