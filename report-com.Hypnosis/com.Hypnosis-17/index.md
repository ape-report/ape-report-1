title: com.Hypnosis

# com.Hypnosis

[Google Play Store](https://play.google.com/store/apps/details?id=com.Hypnosis)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.Hypnosis/com.Hypnosis.MainActivity}: java.lang.IllegalStateException: IAB helper is not set up. Can't perform operation: queryInventory
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
// 	at android.app.ActivityThread.-wrap11(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.IllegalStateException: IAB helper is not set up. Can't perform operation: queryInventory
// 	at com.Hypnosis.util.IabHelper.checkSetupDone(IabHelper.java:783)
// 	at com.Hypnosis.util.IabHelper.queryInventoryAsync(IabHelper.java:612)
// 	at com.Hypnosis.LibraryFragment.populateListView(LibraryFragment.java:337)
// 	at com.Hypnosis.LibraryFragment.onActivityCreated(LibraryFragment.java:170)
// 	at android.support.v4.app.Fragment.performActivityCreated(Fragment.java:1983)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1092)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1252)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1234)
// 	at android.support.v4.app.FragmentManagerImpl.dispatchActivityCreated(FragmentManager.java:2046)
// 	at android.support.v4.app.Fragment.performActivityCreated(Fragment.java:1989)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1092)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1252)
// 	at android.support.v4.app.BackStackRecord.run(BackStackRecord.java:738)
// 	at android.support.v4.app.FragmentManagerImpl.execPendingActions(FragmentManager.java:1617)
// 	at android.support.v4.app.FragmentController.execPendingActions(FragmentController.java:339)
// 	at android.support.v4.app.FragmentActivity.onStart(FragmentActivity.java:602)
// 	at com.Hypnosis.MainActivity.onStart(MainActivity.java:535)
// 	at android.app.Instrumentation.callActivityOnStart(Instrumentation.java:1237)
// 	at android.app.Activity.performStart(Activity.java:6268)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2379)
// 	... 9 more

```



