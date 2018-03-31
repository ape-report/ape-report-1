title: de.stefanpledl.drummersmetronome

# de.stefanpledl.drummersmetronome

[Google Play Store](https://play.google.com/store/apps/details?id=de.stefanpledl.drummersmetronome)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: An error occured while executing doInBackground()
// 	at de.stefanpledl.drummersmetronome.MyAsyncTask$3.done(MyAsyncTask.java:163)
// 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:354)
// 	at java.util.concurrent.FutureTask.setException(FutureTask.java:223)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
// 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
// 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
// 	at java.lang.Thread.run(Thread.java:818)
// Caused by: java.lang.ArrayIndexOutOfBoundsException: length=0; index=1
// 	at java.util.Vector.arrayIndexOutOfBoundsException(Vector.java:907)
// 	at java.util.Vector.elementAt(Vector.java:328)
// 	at de.stefanpledl.drummersmetronome.MainActivity$AsyncGetFullSample.doInBackground(MainActivity.java:229)
// 	at de.stefanpledl.drummersmetronome.MainActivity$AsyncGetFullSample.doInBackground(MainActivity.java:214)
// 	at de.stefanpledl.drummersmetronome.MyAsyncTask$2.call(MyAsyncTask.java:149)
// 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
// 	... 3 more

```



