title: baem.barmanager

# baem.barmanager

[Google Play Store](https://play.google.com/store/apps/details?id=baem.barmanager)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: focus search returned a view that wasn't able to take focus!
// 	at android.widget.TextView.onKeyUp(TextView.java:6222)
// 	at android.view.KeyEvent.dispatch(KeyEvent.java:2664)
// 	at android.view.View.dispatchKeyEvent(View.java:9240)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.widget.ScrollView.dispatchKeyEvent(ScrollView.java:379)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at android.view.ViewGroup.dispatchKeyEvent(ViewGroup.java:1640)
// 	at com.android.internal.policy.PhoneWindow$DecorView.superDispatchKeyEvent(PhoneWindow.java:2395)
// 	at com.android.internal.policy.PhoneWindow.superDispatchKeyEvent(PhoneWindow.java:1727)
// 	at android.app.Activity.dispatchKeyEvent(Activity.java:2731)
// 	at com.actionbarsherlock.app.SherlockActivity.dispatchKeyEvent(SherlockActivity.java:116)
// 	at com.android.internal.policy.PhoneWindow$DecorView.dispatchKeyEvent(PhoneWindow.java:2310)
// 	at android.view.ViewRootImpl$ViewPostImeInputStage.processKeyEvent(ViewRootImpl.java:4127)
// 	at android.view.ViewRootImpl$ViewPostImeInputStage.onProcess(ViewRootImpl.java:4089)
// 	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
// 	at android.view.ViewRootImpl$InputStage.onDeliverToNext(ViewRootImpl.java:3695)
// 	at android.view.ViewRootImpl$InputStage.forward(ViewRootImpl.java:3661)
// 	at android.view.ViewRootImpl$AsyncInputStage.forward(ViewRootImpl.java:3787)
// 	at android.view.ViewRootImpl$InputStage.apply(ViewRootImpl.java:3669)
// 	at android.view.ViewRootImpl$AsyncInputStage.apply(ViewRootImpl.java:3844)
// 	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
// 	at android.view.ViewRootImpl$InputStage.onDeliverToNext(ViewRootImpl.java:3695)
// 	at android.view.ViewRootImpl$InputStage.forward(ViewRootImpl.java:3661)
// 	at android.view.ViewRootImpl$InputStage.apply(ViewRootImpl.java:3669)
// 	at android.view.ViewRootImpl$InputStage.deliver(ViewRootImpl.java:3642)
// 	at android.view.ViewRootImpl$InputStage.onDeliverToNext(ViewRootImpl.java:3695)
// 	at android.view.ViewRootImpl$InputStage.forward(ViewRootImpl.java:3661)
// 	at android.view.ViewRootImpl$AsyncInputStage.forward(ViewRootImpl.java:3820)
// 	at android.view.ViewRootImpl$ImeInputStage.onFinishedInputEvent(ViewRootImpl.java:3981)
// 	at android.view.inputmethod.InputMethodManager$PendingEvent.run(InputMethodManager.java:2253)
// 	at android.view.inputmethod.InputMethodManager.invokeFinishedInputEventCallback(InputMethodManager.java:1874)
// 	at android.view.inputmethod.InputMethodManager.finishedInputEvent(InputMethodManager.java:1865)
// 	at android.view.inputmethod.InputMethodManager$ImeInputEventSender.onInputEventFinished(InputMethodManager.java:2230)
// 	at android.view.InputEventSender.dispatchInputEventFinished(InputEventSender.java:141)
// 	at android.os.MessageQueue.nativePollOnce(Native Method)
// 	at android.os.MessageQueue.next(MessageQueue.java:323)
// 	at android.os.Looper.loop(Looper.java:135)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



