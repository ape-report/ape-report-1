title: ch.publisheria.bring

# ch.publisheria.bring

[Google Play Store](https://play.google.com/store/apps/details?id=ch.publisheria.bring)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{ch.publisheria.bring/ch.publisheria.bring.activities.BringSettingsActivity}: java.lang.IllegalStateException: Already managing a GoogleApiClient with id 0
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
// 	at android.app.ActivityThread.handleRelaunchActivity(ActivityThread.java:4077)
// 	at android.app.ActivityThread.-wrap15(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1350)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.IllegalStateException: Already managing a GoogleApiClient with id 0
// 	at com.google.android.gms.common.internal.zzaa.zza(Unknown Source)
// 	at com.google.android.gms.internal.zznr.zza(Unknown Source)
// 	at com.google.android.gms.common.api.GoogleApiClient$Builder.zze(Unknown Source)
// 	at com.google.android.gms.common.api.GoogleApiClient$Builder.build(Unknown Source)
// 	at ch.publisheria.bring.activities.BringMenuSettingsFragment.onCreate(BringMenuSettingsFragment.java:213)
// 	at android.app.Fragment.performCreate(Fragment.java:2198)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:942)
// 	at android.app.FragmentManagerImpl.moveToState(FragmentManager.java:1148)
// 	at android.app.BackStackRecord.run(BackStackRecord.java:793)
// 	at android.app.FragmentManagerImpl.execPendingActions(FragmentManager.java:1535)
// 	at android.app.FragmentController.execPendingActions(FragmentController.java:325)
// 	at android.app.Activity.performStart(Activity.java:6267)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2379)
// 	... 10 more

```



