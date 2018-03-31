title: com.cgollner.unclouded

# com.cgollner.unclouded

[Google Play Store](https://play.google.com/store/apps/details?id=com.cgollner.unclouded)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Fragment a{bbf4364} not attached to Activity
// 	at android.app.Fragment.startActivityForResult(Fragment.java:1110)
// 	at android.app.Fragment.startActivityForResult(Fragment.java:1101)
// 	at com.cgollner.unclouded.model.a.a(SourceFile:141)
// 	at com.cgollner.unclouded.ui.login.a$2.run(SourceFile:263)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



