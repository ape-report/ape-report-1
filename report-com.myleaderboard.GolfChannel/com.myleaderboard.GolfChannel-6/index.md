title: com.myleaderboard.GolfChannel

# com.myleaderboard.GolfChannel

[Google Play Store](https://play.google.com/store/apps/details?id=com.myleaderboard.GolfChannel)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IndexOutOfBoundsException: Invalid index 0, size is 0
// 	at java.util.ArrayList.throwIndexOutOfBoundsException(ArrayList.java:255)
// 	at java.util.ArrayList.get(ArrayList.java:308)
// 	at android.widget.ArrayAdapter.getItem(ArrayAdapter.java:344)
// 	at com.myleaderboard.GolfChannel.ui.activities.FeedViewFragment.onItemClick(FeedViewFragment.java:209)
// 	at android.widget.AdapterView.performItemClick(AdapterView.java:310)
// 	at android.widget.AbsListView.performItemClick(AbsListView.java:1145)
// 	at android.widget.AbsListView$PerformClick.run(AbsListView.java:3066)
// 	at android.widget.AbsListView$3.run(AbsListView.java:3903)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



