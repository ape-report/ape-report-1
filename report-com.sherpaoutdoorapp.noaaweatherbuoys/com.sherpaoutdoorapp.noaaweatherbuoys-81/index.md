title: com.sherpaoutdoorapp.noaaweatherbuoys

# com.sherpaoutdoorapp.noaaweatherbuoys

[Google Play Store](https://play.google.com/store/apps/details?id=com.sherpaoutdoorapp.noaaweatherbuoys)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'android.content.res.Resources android.app.Activity.getResources()' on a null object reference
// 	at com.sherpaoutdoorapp.noaaweatherbuoys.FrgDetails.refresh(FrgDetails.java:153)
// 	at com.sherpaoutdoorapp.noaaweatherbuoys.FrgDetails.access$2(FrgDetails.java:147)
// 	at com.sherpaoutdoorapp.noaaweatherbuoys.FrgDetails$MyTask.onPostExecute(FrgDetails.java:250)
// 	at com.sherpaoutdoorapp.noaaweatherbuoys.FrgDetails$MyTask.onPostExecute(FrgDetails.java:1)
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



