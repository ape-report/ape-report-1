title: com.sinyee.babybus.behaviour

# com.sinyee.babybus.behaviour

[Google Play Store](https://play.google.com/store/apps/details?id=com.sinyee.babybus.behaviour)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalArgumentException: Receiver not registered: org.chromium.content.browser.accessibility.LollipopWebContentsAccessibility$1@537c26c
// 	at android.app.LoadedApk.forgetReceiverDispatcher(LoadedApk.java:780)
// 	at android.app.ContextImpl.unregisterReceiver(ContextImpl.java:1195)
// 	at android.content.ContextWrapper.unregisterReceiver(ContextWrapper.java:576)
// 	at android.content.ContextWrapper.unregisterReceiver(ContextWrapper.java:576)
// 	at org.chromium.content.browser.accessibility.LollipopWebContentsAccessibility.onDetachedFromWindow(LollipopWebContentsAccessibility.java:42)
// 	at org.chromium.content.browser.ContentViewCoreImpl.onDetachedFromWindow(ContentViewCoreImpl.java:321)
// 	at org.chromium.android_webview.AwContents$AwViewMethodsImpl.onDetachedFromWindow(AwContents.java:361)
// 	at org.chromium.android_webview.AwContents.onDetachedFromWindow(AwContents.java:608)
// 	at com.android.webview.chromium.WebViewChromium.onDetachedFromWindow(WebViewChromium.java:802)
// 	at android.webkit.WebView.onDetachedFromWindowInternal(WebView.java:2317)
// 	at android.view.View.dispatchDetachedFromWindow(View.java:14562)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3071)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
// 	at android.view.ViewGroup.dispatchDetachedFromWindow(ViewGroup.java:3063)
// 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3068)
// 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5606)
// 	at android.view.ViewRootImpl.die(ViewRootImpl.java:5583)
// 	at android.view.WindowManagerGlobal.removeViewLocked(WindowManagerGlobal.java:397)
// 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:352)
// 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
// 	at android.app.ActivityThread.handleDestroyActivity(ActivityThread.java:3867)
// 	at android.app.ActivityThread.-wrap5(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1398)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



