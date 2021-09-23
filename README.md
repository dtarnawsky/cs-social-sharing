# Social Sharing Capacitor Example
Uses the social sharing plugin for a Capacitor project. Fix for Android is to include in your `androidmanifest.xml`:
```xml
<uses-permission android:name="android.permission.QUERY_ALL_PACKAGES" />
```