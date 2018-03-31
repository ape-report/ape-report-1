title: com.cgollner.unclouded

# com.cgollner.unclouded

[Google Play Store](https://play.google.com/store/apps/details?id=com.cgollner.unclouded)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to read from field 'int com.cgollner.unclouded.c.d.g' on a null object reference
// 	at com.cgollner.unclouded.model.l.a(SourceFile:168)
// 	at com.cgollner.unclouded.ui.e.<init>(SourceFile:140)
// 	at com.cgollner.unclouded.ui.details.d.a(SourceFile:107)
// 	at com.cgollner.unclouded.ui.details.d.a(SourceFile:96)
// 	at com.cgollner.unclouded.ui.g.b.a(SourceFile:39)
// 	at com.cgollner.unclouded.ui.d.b.onCreateView(SourceFile:52)
// 	at android.app.Fragment.performCreateView(Fragment.java:2220)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:973)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1148)
// 	at android.app.BackStackRecord.run(BackStackRecord.java:793)
// 	at android.app.FragmentManagerImpl.execPendingActions(FragmentManager.java:1535)
// 	at android.app.FragmentManagerImpl$1.run(FragmentManager.java:482)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



