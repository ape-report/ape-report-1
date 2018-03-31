title: com.appsorama.bday

# com.appsorama.bday

[Google Play Store](https://play.google.com/store/apps/details?id=com.appsorama.bday)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
// 	at android.content.ComponentName.<init>(ComponentName.java:128)
// 	at android.content.Intent.<init>(Intent.java:4449)
// 	at com.appsorama.bday.fragments.FirstLaunchFragment.initializationComplete(FirstLaunchFragment.java:576)
// 	at com.appsorama.bday.fragments.FirstLaunchFragment.access$800(FirstLaunchFragment.java:57)
// 	at com.appsorama.bday.fragments.FirstLaunchFragment$2.onAnimationRepeat(FirstLaunchFragment.java:231)
// 	at android.animation.ValueAnimator.animationFrame(ValueAnimator.java:1365)
// 	at android.animation.ValueAnimator.doAnimationFrame(ValueAnimator.java:1427)
// 	at android.animation.ValueAnimator$AnimationHandler.doAnimationFrame(ValueAnimator.java:759)
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



