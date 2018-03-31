title: com.sncf.fusion

# com.sncf.fusion

[Google Play Store](https://play.google.com/store/apps/details?id=com.sncf.fusion)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to read from field 'java.lang.String com.sncf.android.transporters.model.UrbanLine.transporterType' on a null object reference
// 	at com.sncf.fusion.business.linestatus.LineStatusBusinessService.generateVisualObjectList(LineStatusBusinessService.java:61)
// 	at com.sncf.fusion.ui.infotransilien.linestatus.LineStatusFragment.displayData(LineStatusFragment.java:229)
// 	at com.sncf.fusion.ui.infotransilien.linestatus.LineStatusFragment.access$2(LineStatusFragment.java:228)
// 	at com.sncf.fusion.ui.infotransilien.linestatus.LineStatusFragment$TransilienLoaderManager.onLoadFinished(LineStatusFragment.java:217)
// 	at com.sncf.fusion.ui.infotransilien.linestatus.LineStatusFragment$TransilienLoaderManager.onLoadFinished(LineStatusFragment.java:1)
// 	at android.support.v4.app.LoaderManagerImpl$LoaderInfo.callOnLoadFinished(LoaderManager.java:479)
// 	at android.support.v4.app.LoaderManagerImpl$LoaderInfo.onLoadComplete(LoaderManager.java:447)
// 	at android.support.v4.content.Loader.deliverResult(Loader.java:126)
// 	at com.sncf.fusion.loader.BaseLoader.deliverResult(BaseLoader.java:34)
// 	at android.support.v4.content.AsyncTaskLoader.dispatchOnLoadComplete(AsyncTaskLoader.java:249)
// 	at android.support.v4.content.AsyncTaskLoader$LoadTask.onPostExecute(AsyncTaskLoader.java:77)
// 	at android.support.v4.content.ModernAsyncTask.finish(ModernAsyncTask.java:466)
// 	at android.support.v4.content.ModernAsyncTask.access$400(ModernAsyncTask.java:48)
// 	at android.support.v4.content.ModernAsyncTask$InternalHandler.handleMessage(ModernAsyncTask.java:483)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



