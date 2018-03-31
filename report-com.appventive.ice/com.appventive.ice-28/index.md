title: com.appventive.ice

# com.appventive.ice

[Google Play Store](https://play.google.com/store/apps/details?id=com.appventive.ice)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
// 	at android.content.ComponentName.<init>(ComponentName.java:128)
// 	at android.content.Intent.<init>(Intent.java:4449)
// 	at com.appventive.ice.InstructionsSection$InstructionDetailsFragment$1$1.onClick(InstructionsSection.java:93)
// 	at com.android.internal.app.AlertController$AlertParams$3.onItemClick(AlertController.java:1108)
// 	at android.widget.AdapterView.performItemClick(AdapterView.java:310)
// 	at android.widget.AbsListView.performItemClick(AbsListView.java:1145)
// 	at android.widget.AbsListView$PerformClick.run(AbsListView.java:3066)
// 	at android.widget.AbsListView$3.run(AbsListView.java:3903)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



