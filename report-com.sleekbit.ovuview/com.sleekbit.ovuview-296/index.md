title: com.sleekbit.ovuview

# com.sleekbit.ovuview

[Google Play Store](https://play.google.com/store/apps/details?id=com.sleekbit.ovuview)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Canvas: trying to use a recycled bitmap android.graphics.Bitmap@5e9a60e
// 	at android.graphics.Canvas.throwIfCannotDraw(Canvas.java:1270)
// 	at android.graphics.Canvas.drawBitmap(Canvas.java:1404)
// 	at android.graphics.drawable.BitmapDrawable.draw(BitmapDrawable.java:544)
// 	at android.graphics.drawable.DrawableContainer.draw(DrawableContainer.java:81)
// 	at android.widget.TextView.onDraw(TextView.java:5617)
// 	at android.view.View.draw(View.java:16184)
// 	at android.view.View.updateDisplayListIfDirty(View.java:15180)
// 	at android.view.View.draw(View.java:15954)
// 	at android.view.ViewGroup.drawChild(ViewGroup.java:3609)
// 	at android.view.ViewGroup.dispatchDraw(ViewGroup.java:3399)
// 	at android.view.View.updateDisplayListIfDirty(View.java:15175)
// 	at android.view.View.draw(View.java:15954)
// 	at android.view.ViewGroup.drawChild(ViewGroup.java:3609)
// 	at android.view.ViewGroup.dispatchDraw(ViewGroup.java:3399)
// 	at android.view.View.updateDisplayListIfDirty(View.java:15175)
// 	at android.view.View.draw(View.java:15954)
// 	at android.view.ViewGroup.drawChild(ViewGroup.java:3609)
// 	at android.view.ViewGroup.dispatchDraw(ViewGroup.java:3399)
// 	at android.view.View.draw(View.java:16187)
// 	at android.view.View.updateDisplayListIfDirty(View.java:15180)
// 	at android.view.View.draw(View.java:15954)
// 	at android.view.ViewGroup.drawChild(ViewGroup.java:3609)
// 	at android.view.ViewGroup.dispatchDraw(ViewGroup.java:3399)
// 	at android.view.View.draw(View.java:16187)
// 	at android.view.View.updateDisplayListIfDirty(View.java:15180)
// 	at android.view.View.draw(View.java:15954)
// 	at android.view.ViewGroup.drawChild(ViewGroup.java:3609)
// 	at android.view.ViewGroup.dispatchDraw(ViewGroup.java:3399)
// 	at android.view.View.updateDisplayListIfDirty(View.java:15175)
// 	at android.view.View.draw(View.java:15954)
// 	at android.view.ViewGroup.drawChild(ViewGroup.java:3609)
// 	at android.view.ViewGroup.dispatchDraw(ViewGroup.java:3399)
// 	at android.view.View.draw(View.java:16187)
// 	at com.android.internal.policy.PhoneWindow$DecorView.draw(PhoneWindow.java:2690)
// 	at android.view.View.updateDisplayListIfDirty(View.java:15180)
// 	at android.view.ThreadedRenderer.updateViewTreeDisplayList(ThreadedRenderer.java:281)
// 	at android.view.ThreadedRenderer.updateRootDisplayList(ThreadedRenderer.java:287)
// 	at android.view.ThreadedRenderer.draw(ThreadedRenderer.java:322)
// 	at android.view.ViewRootImpl.draw(ViewRootImpl.java:2615)
// 	at android.view.ViewRootImpl.performDraw(ViewRootImpl.java:2434)
// 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:2067)
// 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1107)
// 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6013)
// 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
// 	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
// 	at android.view.Choreographer.doFrame(Choreographer.java:606)
// 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



