title: com.stronglifts.app

# com.stronglifts.app

[Google Play Store](https://play.google.com/store/apps/details?id=com.stronglifts.app)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NumberFormatException: Invalid double: ""
// 	at java.lang.StringToReal.invalidReal(StringToReal.java:63)
// 	at java.lang.StringToReal.parseDouble(StringToReal.java:267)
// 	at java.lang.Double.parseDouble(Double.java:301)
// 	at com.stronglifts.app.platecalculator.AddPlateDialog$AddPlateView.a(AddPlateDialog.java:109)
// 	at com.stronglifts.app.platecalculator.AddPlateDialog.a(AddPlateDialog.java:36)
// 	at com.stronglifts.app.platecalculator.a.onClick(Unknown Source)
// 	at com.stronglifts.app.dialogs.CustomAlertDialog.positiveClicked(CustomAlertDialog.java:185)
// 	at com.stronglifts.app.dialogs.CustomAlertDialog_ViewBinding$1.a(CustomAlertDialog_ViewBinding.java:52)
// 	at butterknife.a.a.onClick(DebouncingOnClickListener.java:22)
// 	at android.view.View.performClick(View.java:5204)
// 	at android.view.View$PerformClick.run(View.java:21153)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



