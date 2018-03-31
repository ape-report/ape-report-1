title: com.Hypnosis

# com.Hypnosis

[Google Play Store](https://play.google.com/store/apps/details?id=com.Hypnosis)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'void com.Hypnosis.LibraryFragment.inAppPurchaseSetupFinished(boolean)' on a null object reference
// 	at com.Hypnosis.TabFragment.inAppPurchaseSetupFinished(TabFragment.java:83)
// 	at com.Hypnosis.MainActivity$2.onIabSetupFinished(MainActivity.java:229)
// 	at com.Hypnosis.util.IabHelper$1.onServiceConnected(IabHelper.java:261)
// 	at android.app.LoadedApk$ServiceDispatcher.doConnected(LoadedApk.java:1223)
// 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1240)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



