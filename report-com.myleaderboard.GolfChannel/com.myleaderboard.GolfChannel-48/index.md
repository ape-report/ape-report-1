title: com.myleaderboard.GolfChannel

# com.myleaderboard.GolfChannel

[Google Play Store](https://play.google.com/store/apps/details?id=com.myleaderboard.GolfChannel)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// android.view.WindowManager$BadTokenException: Unable to add window -- token android.view.ViewRootImpl$W@ebe20a7 is not valid; is your activity running?
// 	at android.view.ViewRootImpl.setView(ViewRootImpl.java:567)
// 	at android.view.WindowManagerGlobal.addView(WindowManagerGlobal.java:310)
// 	at android.view.WindowManagerImpl.addView(WindowManagerImpl.java:85)
// 	at android.widget.MediaController.show(MediaController.java:368)
// 	at com.myleaderboard.GolfChannel.ui.activities.VideoPlayerActivity$11.run(VideoPlayerActivity.java:423)
// 	at android.app.Activity.runOnUiThread(Activity.java:5524)
// 	at com.myleaderboard.GolfChannel.ui.activities.VideoPlayerActivity.playMainVideo(VideoPlayerActivity.java:420)
// 	at com.myleaderboard.GolfChannel.ui.activities.VideoPlayerActivity.playNextPreroll(VideoPlayerActivity.java:486)
// 	at com.myleaderboard.GolfChannel.ui.activities.VideoPlayerActivity.access$1500(VideoPlayerActivity.java:56)
// 	at com.myleaderboard.GolfChannel.ui.activities.VideoPlayerActivity$12.run(VideoPlayerActivity.java:456)
// 	at tv.freewheel.utils.events.EventDispatcher.dispatchEvent(EventDispatcher.java:74)
// 	at tv.freewheel.ad.AdContext.dispatchEvent(AdContext.java:962)
// 	at tv.freewheel.ad.slot.Slot.dispatchSlotEvent(Slot.java:396)
// 	at tv.freewheel.ad.slot.Slot.onComplete(Slot.java:389)
// 	at tv.freewheel.ad.slot.TemporalSlot.onComplete(TemporalSlot.java:142)
// 	at tv.freewheel.ad.state.SlotPlayingState.complete(SlotPlayingState.java:28)
// 	at tv.freewheel.ad.slot.Slot.notifyAdDone(Slot.java:475)
// 	at tv.freewheel.ad.state.AdPlayingState.fail(AdPlayingState.java:34)
// 	at tv.freewheel.ad.AdInstance.onRendererError(AdInstance.java:392)
// 	at tv.freewheel.ad.AdInstance.dispatchEvent(AdInstance.java:644)
// 	at tv.freewheel.ad.AdInstance.access$000(AdInstance.java:39)
// 	at tv.freewheel.ad.AdInstance$1.run(AdInstance.java:629)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



