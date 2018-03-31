title: com.flynx

# com.flynx

[Google Play Store](https://play.google.com/store/apps/details?id=com.flynx)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Adding window failed
// 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:543)
// 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:310)
// 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:85)
// 	at android.widget.Toast$TN.handleShow(Toast.java:425)
// 	at android.widget.Toast$TN$1.run(Toast.java:331)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
// 	at android.os.BinderProxy.transactNative(Native Method)
// 	at android.os.BinderProxy.transact(Binder.java:503)
// 	at android.view.IWindowSession$Stub$Proxy.addToDisplay(IWindowSession.java:746)
// 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:531)
// 	... 11 more

```



