title: com.mydiabetes

# com.mydiabetes

[Google Play Store](https://play.google.com/store/apps/details?id=com.mydiabetes)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalArgumentException: width and height must be > 0
// 	at android.graphics.Bitmap.createBitmap(Bitmap.java:829)
// 	at android.graphics.Bitmap.createBitmap(Bitmap.java:808)
// 	at android.graphics.Bitmap.createBitmap(Bitmap.java:775)
// 	at com.mydiabetes.utils.c.a(SourceFile:120)
// 	at com.mydiabetes.utils.c.a(SourceFile:88)
// 	at com.mydiabetes.fragments.PieChartFragment.a(SourceFile:82)
// 	at com.mydiabetes.activities.ReportsActivity.a(SourceFile:703)
// 	at com.mydiabetes.activities.ReportsActivity$14.run(SourceFile:648)
// 	at java.lang.Thread.run(Thread.java:818)

```



