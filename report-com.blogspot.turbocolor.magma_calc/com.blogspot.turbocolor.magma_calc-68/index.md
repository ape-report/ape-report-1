title: com.blogspot.turbocolor.magma_calc

# com.blogspot.turbocolor.magma_calc

[Google Play Store](https://play.google.com/store/apps/details?id=com.blogspot.turbocolor.magma_calc)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to resume activity {com.blogspot.turbocolor.magma_calc/com.blogspot.turbocolor.magma_calc.Activity_Magma_Calc}: java.lang.NumberFormatException: Invalid double: ""
// 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3103)
// 	at android.app.ActivityThread.handleResumeActivity(ActivityThread.java:3134)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1388)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.NumberFormatException: Invalid double: ""
// 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
// 	at java.lang.StringToReal.parseDouble(StringToReal.java:267)
// 	at java.lang.Double.parseDouble(Double.java:301)
// 	at com.blogspot.turbocolor.magma_calc.Activity_Magma_Calc.myGetResultFromMemory(Activity_Magma_Calc.java:2463)
// 	at com.blogspot.turbocolor.magma_calc.Activity_Magma_Calc.onResume(Activity_Magma_Calc.java:2410)
// 	at android.app.Instrumentation.callActivityOnResume(Instrumentation.java:1258)
// 	at android.app.Activity.performResume(Activity.java:6327)
// 	at android.app.ActivityThread.performResumeActivity(ActivityThread.java:3092)
// 	... 8 more

```



