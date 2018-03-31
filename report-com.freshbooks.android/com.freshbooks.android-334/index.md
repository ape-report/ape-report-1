title: com.freshbooks.android

# com.freshbooks.android

[Google Play Store](https://play.google.com/store/apps/details?id=com.freshbooks.android)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalArgumentException: account must not be null
// 	at android.content.ContentResolver.isSyncActive(ContentResolver.java:2255)
// 	at com.freshbooks.android.g.z.d(SourceFile:25)
// 	at com.freshbooks.android.provider.FreshbooksProvider.insert(SourceFile:331)
// 	at android.content.ContentProviderOperation.apply(ContentProviderOperation.java:302)
// 	at com.freshbooks.android.provider.FreshbooksProvider.applyBatch(SourceFile:400)
// 	at android.content.ContentProvider$Transport.applyBatch(ContentProvider.java:315)
// 	at android.content.ContentProviderClient.applyBatch(ContentProviderClient.java:419)
// 	at android.content.ContentResolver.applyBatch(ContentResolver.java:1270)
// 	at com.freshbooks.android.model.q.a(SourceFile:356)
// 	at com.freshbooks.android.activity.ProjectCreateActivity.x(SourceFile:188)
// 	at com.freshbooks.android.activity.ProjectCreateActivity.a(SourceFile:112)
// 	at com.freshbooks.android.activity.aw.onClick(SourceFile:39)
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



