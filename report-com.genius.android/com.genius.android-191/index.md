title: com.genius.android

# com.genius.android

[Google Play Store](https://play.google.com/store/apps/details?id=com.genius.android)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Can not perform this action after onSaveInstanceState
// 	at android.support.v4.app.FragmentManagerImpl.checkStateLoss(FragmentManager.java:1842)
// 	at android.support.v4.app.FragmentManagerImpl.popBackStackImmediate(FragmentManager.java:775)
// 	at android.support.v4.app.FragmentActivity.onBackPressed(FragmentActivity.java:178)
// 	at com.genius.android.FullscreenVideoActivity.access$601(FullscreenVideoActivity.java:48)
// 	at com.genius.android.FullscreenVideoActivity$10.onAnimationEnd(FullscreenVideoActivity.java:220)
// 	at android.view.ViewPropertyAnimator$AnimatorEventListener.onAnimationEnd(ViewPropertyAnimator.java:1114)
// 	at android.animation.ValueAnimator.endAnimation(ValueAnimator.java:1239)
// 	at android.animation.ValueAnimator$AnimationHandler.doAnimationFrame(ValueAnimator.java:766)
// 	at android.animation.ValueAnimator$AnimationHandler$1.run(ValueAnimator.java:801)
// 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
// 	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
// 	at android.view.Choreographer.doFrame(Choreographer.java:603)
// 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



