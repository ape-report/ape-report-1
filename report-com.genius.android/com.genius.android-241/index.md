title: com.genius.android

# com.genius.android

[Google Play Store](https://play.google.com/store/apps/details?id=com.genius.android)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: An error occurred while executing doInBackground()
// 	at android.os.AsyncTask$3.done(AsyncTask.java:309)
// 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
// 	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
// 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:234)
// 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
// 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
// 	at java.lang.Thread.run(Thread.java:818)
// Caused by: java.lang.IllegalStateException: Fragment MetadataFragment{ecb1c38} not attached to Activity
// 	at android.support.v4.app.Fragment.getResources(Fragment.java:646)
// 	at android.support.v4.app.Fragment.getString(Fragment.java:668)
// 	at com.genius.android.view.MetadataFragment.makeInitialListContent(MetadataFragment.java:62)
// 	at com.genius.android.view.ContentFragment$4.doInBackground(ContentFragment.java:440)
// 	at com.genius.android.view.ContentFragment$ContentAsyncTask.doInBackground(ContentFragment.java:791)
// 	at android.os.AsyncTask$2.call(AsyncTask.java:295)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
// 	... 4 more

```



