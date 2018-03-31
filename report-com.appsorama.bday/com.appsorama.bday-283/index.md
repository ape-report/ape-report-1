title: com.appsorama.bday

# com.appsorama.bday

[Google Play Store](https://play.google.com/store/apps/details?id=com.appsorama.bday)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to destroy activity {com.appsorama.bday/com.appsorama.bday.activities.ContainerActivity}: java.lang.IllegalArgumentException: Receiver not registered: com.appsorama.billing.utils.IabBroadcastReceiver@341a9eb
// 	at android.app.ActivityThread.performDestroyActivity(ActivityThread.java:3831)
// 	at android.app.ActivityThread.handleDestroyActivity(ActivityThread.java:3849)
// 	at android.app.ActivityThread.-wrap5(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1398)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.IllegalArgumentException: Receiver not registered: com.appsorama.billing.utils.IabBroadcastReceiver@341a9eb
// 	at android.app.LoadedApk.forgetReceiverDispatcher(LoadedApk.java:780)
// 	at android.app.ContextImpl.unregisterReceiver(ContextImpl.java:1195)
// 	at android.content.ContextWrapper.unregisterReceiver(ContextWrapper.java:576)
// 	at com.appsorama.bday.utils.InAppPurchase.dispose(InAppPurchase.java:579)
// 	at com.appsorama.bday.activities.BaseActivity.onDestroy(BaseActivity.java:585)
// 	at android.app.Activity.performDestroy(Activity.java:6422)
// 	at android.app.Instrumentation.callActivityOnDestroy(Instrumentation.java:1142)
// 	at android.app.ActivityThread.performDestroyActivity(ActivityThread.java:3818)
// 	... 9 more

```



