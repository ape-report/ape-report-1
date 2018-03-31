title: com.islickapp.pro

# com.islickapp.pro

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.islickapp.pro/com.islickapp.pro.activity.user.UserDetailActivity}: java.lang.NullPointerException: Attempt to read from field 'int com.islickapp.pro.model.b.followersCount' on a null object reference
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
// 	at android.app.ActivityThread.-wrap11(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: java.lang.NullPointerException: Attempt to read from field 'int com.islickapp.pro.model.b.followersCount' on a null object reference
// 	at com.islickapp.pro.fragment.user.a.a(SourceFile:108)
// 	at com.islickapp.pro.fragment.user.g.a(SourceFile:69)
// 	at com.islickapp.pro.fragment.user.a.onActivityCreated(SourceFile:75)
// 	at com.islickapp.pro.fragment.user.g.onActivityCreated(SourceFile:36)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(SourceFile:891)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(SourceFile:1080)
// 	at android.support.v4.app.FragmentManagerImpl.moveToState(SourceFile:1062)
// 	at android.support.v4.app.FragmentManagerImpl.dispatchActivityCreated(SourceFile:1810)
// 	at android.support.v4.app.FragmentActivity.onStart(SourceFile:501)
// 	at android.app.Instrumentation.callActivityOnStart(Instrumentation.java:1237)
// 	at android.app.Activity.performStart(Activity.java:6268)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2379)
// 	... 9 more

```



