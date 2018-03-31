title: com.urbanoutfitters.android

# com.urbanoutfitters.android

[Google Play Store](https://play.google.com/store/apps/details?id=com.urbanoutfitters.android)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: Can't compress a recycled bitmap
// 	at android.graphics.Bitmap.checkRecycled(Bitmap.java:351)
// 	at android.graphics.Bitmap.compress(Bitmap.java:1018)
// 	at com.android.slyce.utils.Utils.uploadBitmapToSlyce(Utils.java:164)
// 	at com.android.slyce.socket.WSConnection$10.run(WSConnection.java:778)
// 	at java.lang.Thread.run(Thread.java:818)

```



