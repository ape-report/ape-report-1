title: com.aetn.history.watch

# com.aetn.history.watch

[Google Play Store](https://play.google.com/store/apps/details?id=com.aetn.history.watch)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.aetn.history.watch/com.aetn.watch.activities.SeriesListActivity}: java.lang.IllegalArgumentException: Invalid context argument
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
// Caused by: java.lang.IllegalArgumentException: Invalid context argument
// 	at android.webkit.CookieSyncManager.createInstance(CookieSyncManager.java:95)
// 	at tv.freewheel.utils.cookie.AndroidCookieStore.initialize(AndroidCookieStore.java:15)
// 	at tv.freewheel.ad.AdManager.<init>(AdManager.java:34)
// 	at tv.freewheel.ad.AdManager.getInstance(AdManager.java:135)
// 	at com.aetn.libs.core.AEAdManager.createAdManager(AEAdManager.java:316)
// 	at com.aetn.libs.core.AEAdManager.loadDisplayAd(AEAdManager.java:234)
// 	at com.aetn.libs.core.AEAdManager.loadDisplayAd(AEAdManager.java:257)
// 	at com.aetn.watch.ui.ShowDetailFragment.loadDisplayAd(ShowDetailFragment.java:381)
// 	at com.aetn.watch.ui.ShowDetailFragment.onActivityCreated(ShowDetailFragment.java:591)
// 	at android.support.v4.app.Fragment.performActivityCreated(Fragment.java:1794)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:967)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1126)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(FragmentManager.java:1108)
// 	at android.support.v4.app.FragmentManagerImpl.dispatchActivityCreated(FragmentManager.java:1917)
// 	at android.support.v4.app.FragmentActivity.onStart(FragmentActivity.java:544)
// 	at com.aetn.watch.activities.BaseActivity.onStart(BaseActivity.java:478)
// 	at android.app.Instrumentation.callActivityOnStart(Instrumentation.java:1237)
// 	at android.app.Activity.performStart(Activity.java:6268)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2379)
// 	... 9 more

```



