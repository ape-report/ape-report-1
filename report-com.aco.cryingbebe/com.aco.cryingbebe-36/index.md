title: com.aco.cryingbebe

# com.aco.cryingbebe

[Google Play Store](https://play.google.com/store/apps/details?id=com.aco.cryingbebe)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{986a85c V.ED..... R....... 0,0-274,274} not attached to window manager
// 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
// 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
// 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
// 	at android.app.Dialog.dismissDialog(Dialog.java:362)
// 	at android.app.Dialog.dismiss(Dialog.java:345)
// 	at com.aco.cryingbebe.ActivityNewRegister$1.onFinished(ActivityNewRegister.java:193)
// 	at com.aco.cryingbebe.module.ExtraWebViewClient.onPageFinished(ExtraWebViewClient.java:66)
// 	at com.android.webview.chromium.WebViewContentsClientAdapter.onPageFinished(WebViewContentsClientAdapter.java:224)
// 	at org.chromium.android_webview.AwContentsClientCallbackHelper$MyHandler.handleMessage(AwContentsClientCallbackHelper.java:72)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



