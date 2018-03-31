title: com.eatstreet.android

# com.eatstreet.android

[Google Play Store](https://play.google.com/store/apps/details?id=com.eatstreet.android)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Failure delivering result ResultInfo{who=null, request=22, result=0, data=null} to activity {com.eatstreet.android/com.eatstreet.android.AuthenticationActivity}: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean com.facebook.Session.onActivityResult(android.app.Activity, int, int, android.content.Intent)' on a null object reference
// 	at android.app.ActivityThread.deliverResults(ActivityThread.java:3699)
// 	at android.app.ActivityThread.handleSendResult(ActivityThread.java:3742)
// 	at android.app.ActivityThread.-wrap16(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1393)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean com.facebook.Session.onActivityResult(android.app.Activity, int, int, android.content.Intent)' on a null object reference
// 	at com.eatstreet.android.AuthenticationActivity.onActivityResult(AuthenticationActivity.java:218)
// 	at android.app.Activity.dispatchActivityResult(Activity.java:6456)
// 	at android.app.ActivityThread.deliverResults(ActivityThread.java:3695)
// 	... 9 more

```



