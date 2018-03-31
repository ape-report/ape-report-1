title: com.yummly.android

# com.yummly.android

[Google Play Store](https://play.google.com/store/apps/details?id=com.yummly.android)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'int java.lang.String.length()' on a null object reference
// 	at com.yummly.android.util.Util.changeImageRequestSize(Util.java:41)
// 	at com.yummly.android.adapters.CustomCursorGridViewImagePreloader.preloadItem(CustomCursorGridViewImagePreloader.java:153)
// 	at com.yummly.android.adapters.CustomCursorGridViewImagePreloader.preload(CustomCursorGridViewImagePreloader.java:137)
// 	at com.yummly.android.adapters.CustomCursorGridViewImagePreloader.preload(CustomCursorGridViewImagePreloader.java:106)
// 	at com.yummly.android.adapters.CustomCursorGridViewImagePreloader.onScroll(CustomCursorGridViewImagePreloader.java:93)
// 	at com.yummly.android.activities.HomeActivity$11.onGlobalLayout(HomeActivity.java:715)
// 	at android.view.ViewTreeObserver.dispatchOnGlobalLayout(ViewTreeObserver.java:912)
// 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1969)
// 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1107)
// 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6013)
// 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
// 	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
// 	at android.view.Choreographer.doFrame(Choreographer.java:606)
// 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



