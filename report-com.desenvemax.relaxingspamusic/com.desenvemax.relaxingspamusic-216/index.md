title: com.desenvemax.relaxingspamusic

# com.desenvemax.relaxingspamusic

[Google Play Store](https://play.google.com/store/apps/details?id=com.desenvemax.relaxingspamusic)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.OutOfMemoryError: Failed to allocate a 38880012 byte allocation with 16769584 free bytes and 22MB until OOM
// 	at dalvik.system.VMRuntime.newNonMovableArray(Native Method)
// 	at android.graphics.BitmapFactory.nativeDecodeAsset(Native Method)
// 	at android.graphics.BitmapFactory.decodeStream(BitmapFactory.java:609)
// 	at android.graphics.BitmapFactory.decodeResourceStream(BitmapFactory.java:444)
// 	at android.graphics.drawable.Drawable.createFromResourceStream(Drawable.java:1080)
// 	at android.content.res.Resources.loadDrawableForCookie(Resources.java:2635)
// 	at android.content.res.Resources.loadDrawable(Resources.java:2540)
// 	at android.content.res.Resources.getDrawable(Resources.java:806)
// 	at android.content.Context.getDrawable(Context.java:458)
// 	at android.view.View.setBackgroundResource(View.java:17208)
// 	at com.desenvemax.relaxingspamusic.Som.trocaFundoApp(Som.java:527)
// 	at com.desenvemax.relaxingspamusic.Som.vaiParaFrente(Som.java:545)
// 	at com.desenvemax.relaxingspamusic.Som.onClick(Som.java:159)
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



