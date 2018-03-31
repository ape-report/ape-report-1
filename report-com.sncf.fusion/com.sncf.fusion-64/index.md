title: com.sncf.fusion

# com.sncf.fusion

[Google Play Store](https://play.google.com/store/apps/details?id=com.sncf.fusion)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Error receiving broadcast Intent { act=android.intent.action.DOWNLOAD_COMPLETE flg=0x10 pkg=com.sncf.fusion (has extras) } in com.sncf.fusion.business.LineMapsBusinessService$1@69e2113
// 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:891)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
// 	at android.content.ComponentName.<init>(ComponentName.java:128)
// 	at android.content.Intent.<init>(Intent.java:4449)
// 	at com.sncf.fusion.util.Intents.lineMap(Intents.java:606)
// 	at com.sncf.fusion.ui.linemap.LineMapsFragment.gotoLineMap(LineMapsFragment.java:96)
// 	at com.sncf.fusion.ui.linemap.LineMapsFragment.access$1(LineMapsFragment.java:94)
// 	at com.sncf.fusion.ui.linemap.LineMapsFragment$1.onDownloadFinished(LineMapsFragment.java:85)
// 	at com.sncf.fusion.business.LineMapsBusinessService$1.onReceive(LineMapsBusinessService.java:100)
// 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:881)
// 	... 7 more

```



