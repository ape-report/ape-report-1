title: com.yummly.android

# com.yummly.android

[Google Play Store](https://play.google.com/store/apps/details?id=com.yummly.android)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'com.android.volley.RequestQueue com.yummly.android.YummlyApp.getRequestQueue()' on a null object reference
// 	at com.yummly.android.service.RequestIntentService.handleActionFetchRecommendations(RequestIntentService.java:661)
// 	at com.yummly.android.service.RequestIntentService.onHandleIntent(RequestIntentService.java:509)
// 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.os.HandlerThread.run(HandlerThread.java:61)

```



