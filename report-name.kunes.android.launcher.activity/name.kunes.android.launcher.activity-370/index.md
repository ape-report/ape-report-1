title: name.kunes.android.launcher.activity

# name.kunes.android.launcher.activity

[Google Play Store](https://play.google.com/store/apps/details?id=name.kunes.android.launcher.activity)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IndexOutOfBoundsException: Invalid index 7, size is 0
// 	at java.util.ArrayList.throwIndexOutOfBoundsException(ArrayList.java:255)
// 	at java.util.ArrayList.get(ArrayList.java:308)
// 	at android.widget.HeaderViewListAdapter.getView(HeaderViewListAdapter.java:225)
// 	at android.widget.AbsListView.obtainView(AbsListView.java:2346)
// 	at android.widget.ListView.makeAndAddView(ListView.java:1876)
// 	at android.widget.ListView.fillUp(ListView.java:736)
// 	at android.widget.ListView.fillGap(ListView.java:675)
// 	at android.widget.AbsListView.trackMotionScroll(AbsListView.java:5053)
// 	at android.widget.AbsListView.scrollIfNeeded(AbsListView.java:3448)
// 	at android.widget.AbsListView.startScrollIfNeeded(AbsListView.java:3376)
// 	at android.widget.AbsListView.onInterceptTouchEvent(AbsListView.java:4321)
// 	at android.view.ViewGroup.dispatchTouchEvent(ViewGroup.java:2108)
// 	at android.view.ViewGroup.dispatchTransformedTouchEvent(ViewGroup.java:2553)
// 	at android.view.ViewGroup.dispatchTouchEvent(ViewGroup.java:2254)
// 	at android.view.ViewGroup.dispatchTransformedTouchEvent(ViewGroup.java:2553)
// 	at android.view.ViewGroup.dispatchTouchEvent(ViewGroup.java:2254)
// 	at android.view.ViewGroup.dispatchTransformedTouchEvent(ViewGroup.java:2553)
// 	at android.view.ViewGroup.dispatchTouchEvent(ViewGroup.java:2254)
// 	at android.view.ViewGroup.dispatchTransformedTouchEvent(ViewGroup.java:2553)
// 	at android.view.ViewGroup.dispatchTouchEvent(ViewGroup.java:2254)
// 	at com.android.internal.policy.PhoneWindow$DecorView.superDispatchTouchEvent(PhoneWindow.java:2403)
// 	at com.android.internal.policy.PhoneWindow.superDispatchTouchEvent(PhoneWindow.java:1737)
// 	at android.app.Activity.dispatchTouchEvent(Activity.java:2771)
// 	at com.android.internal.policy.PhoneWindow$DecorView.dispatchTouchEvent(PhoneWindow.java:2364)
// 	at android.view.View.dispatchPointerEvent(View.java:9520)
// 	at android.view.ViewRootImpl$ViewPostImeInputStage.processPointerEvent(ViewRootImpl.java:4230)
// 	at android.view.ViewRootImpl$ViewPostImeInputStage.onProcess(ViewRootImpl.java:4096)
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
// 	at android.view.ViewRootImpl.deliverInputEvent(ViewRootImpl.java:5922)
// 	at android.view.ViewRootImpl.doProcessInputEvents(ViewRootImpl.java:5896)
// 	at android.view.ViewRootImpl.enqueueInputEvent(ViewRootImpl.java:5857)
// 	at android.view.ViewRootImpl$WindowInputEventReceiver.onInputEvent(ViewRootImpl.java:6025)
// 	at android.view.InputEventReceiver.dispatchInputEvent(InputEventReceiver.java:185)
// 	at android.view.InputEventReceiver.nativeConsumeBatchedInputEvents(Native Method)
// 	at android.view.InputEventReceiver.consumeBatchedInputEvents(InputEventReceiver.java:176)
// 	at android.view.ViewRootImpl.doConsumeBatchedInput(ViewRootImpl.java:5996)
// 	at android.view.ViewRootImpl$ConsumeBatchedInputRunnable.run(ViewRootImpl.java:6048)
// 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
// 	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
// 	at android.view.Choreographer.doFrame(Choreographer.java:600)
// 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



