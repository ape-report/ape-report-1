title: com.aetn.history.watch

# com.aetn.history.watch

[Google Play Store](https://play.google.com/store/apps/details?id=com.aetn.history.watch)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// com.localytics.android.Localytics$LocalyticsNotInitializedException: You must first initialize Localytics
// 	at com.localytics.android.Localytics.getAnalyticsHandler(Localytics.java:1193)
// 	at com.localytics.android.Localytics.tagEvent(Localytics.java:207)
// 	at com.localytics.android.Localytics.tagEvent(Localytics.java:175)
// 	at com.aetn.libs.core.AEAnalyticsManager.trackLocalyticsStart(AEAnalyticsManager.java:346)
// 	at com.aetn.libs.core.AEAnalyticsManager.initAnalyticsManager(AEAnalyticsManager.java:80)
// 	at com.aetn.AECoreLib.initServices(AECoreLib.java:33)
// 	at com.aetn.watch.app.WatchApplication.initCoreLibrary(WatchApplication.java:386)
// 	at com.aetn.watch.app.WatchApplication.onConfigLoaded(WatchApplication.java:344)
// 	at com.aetn.libs.core.AEConfigManager.dispatchConfigLoaded(AEConfigManager.java:416)
// 	at com.aetn.libs.core.AEConfigManager.access$100(AEConfigManager.java:32)
// 	at com.aetn.libs.core.AEConfigManager$1$1.onFileRetrieved(AEConfigManager.java:167)
// 	at com.aetn.utils.FileFetcher$FileWorker.onPostExecute(FileFetcher.java:92)
// 	at com.aetn.utils.FileFetcher$FileWorker.onPostExecute(FileFetcher.java:65)
// 	at android.os.AsyncTask.finish(AsyncTask.java:651)
// 	at android.os.AsyncTask.-wrap1(AsyncTask.java)
// 	at android.os.AsyncTask$InternalHandler.handleMessage(AsyncTask.java:668)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



