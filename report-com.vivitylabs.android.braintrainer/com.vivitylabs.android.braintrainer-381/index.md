title: com.vivitylabs.android.braintrainer

# com.vivitylabs.android.braintrainer

[Google Play Store](https://play.google.com/store/apps/details?id=com.vivitylabs.android.braintrainer)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: android.view.WindowManager$BadTokenException: Unable to add window -- token android.os.BinderProxy@c8c50e is not valid; is your activity running?
// 	at com.loopj.android.http.AsyncHttpResponseHandler.onUserException(AsyncHttpResponseHandler.java:304)
// 	at com.loopj.android.http.AsyncHttpResponseHandler.handleMessage(AsyncHttpResponseHandler.java:395)
// 	at com.loopj.android.http.AsyncHttpResponseHandler$ResponderHandler.handleMessage(AsyncHttpResponseHandler.java:510)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: android.view.WindowManager$BadTokenException: Unable to add window -- token android.os.BinderProxy@c8c50e is not valid; is your activity running?
// 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:567)
// 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:310)
// 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:85)
// 	at android.app.Dialog.show(Dialog.java:319)
// 	at com.vivitylabs.android.braintrainer.widgets.CustomDialog.showCustomDialog(CustomDialog.java:55)
// 	at com.vivitylabs.android.braintrainer.dialogs.DialogManager.displayDialogError(DialogManager.java:19)
// 	at com.vivitylabs.android.braintrainer.activities.account.RegisterActivity$2$1.onSystemError(RegisterActivity.java:146)
// 	at com.vivitylabs.android.braintrainer.model.user.UserKnown$3$1.onSystemError(UserKnown.java:175)
// 	at com.vivitylabs.android.braintrainer.http.HttpConnectorImpl$1.onSuccess(HttpConnectorImpl.java:126)
// 	at com.loopj.android.http.AsyncHttpResponseHandler.handleMessage(AsyncHttpResponseHandler.java:351)
// 	... 7 more

```



