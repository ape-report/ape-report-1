title: com.tinymission.dailyyogafree

# com.tinymission.dailyyogafree

[Google Play Store](https://play.google.com/store/apps/details?id=com.tinymission.dailyyogafree)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to pause activity {com.tinymission.dailyyogafree/com.tinymission.dailyyogafree.Settings_Activity}: java.lang.NumberFormatException: Invalid int: "72417275815"
// 	at android.app.ActivityThread.performPauseActivity(ActivityThread.java:3381)
// 	at android.app.ActivityThread.performPauseActivity(ActivityThread.java:3340)
// 	at android.app.ActivityThread.handlePauseActivity(ActivityThread.java:3315)
// 	at android.app.ActivityThread.-wrap13(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1362)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.NumberFormatException: Invalid int: "72417275815"
// 	at java.lang.Integer.invalidInt(Integer.java:138)
// 	at java.lang.Integer.parse(Integer.java:413)
// 	at java.lang.Integer.parseInt(Integer.java:367)
// 	at java.lang.Integer.parseInt(Integer.java:334)
// 	at com.tinymission.dailyyogafree.Settings_Activity.d(Unknown Source)
// 	at com.tinymission.dailyyogafree.Settings_Activity.onPause(Unknown Source)
// 	at android.app.Activity.performPause(Activity.java:6363)
// 	at android.app.Instrumentation.callActivityOnPause(Instrumentation.java:1311)
// 	at android.app.ActivityThread.performPauseActivity(ActivityThread.java:3367)
// 	... 10 more

```



