title: com.masteryconnect.NGSS

# com.masteryconnect.NGSS

[Google Play Store](https://play.google.com/store/apps/details?id=com.masteryconnect.NGSS)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.StringIndexOutOfBoundsException: length=0; index=-1
// 	at java.lang.String.charAt(Native Method)
// 	at com.masteryconnect.StandardsApp.helper.HTMLHelper.getRelatedStandardsHTML(HTMLHelper.java:85)
// 	at com.masteryconnect.StandardsApp.view.DetailContentPagerAdapter.updateNgssExpandingViews(DetailContentPagerAdapter.java:192)
// 	at com.masteryconnect.StandardsApp.view.DetailContentPagerAdapter.updateViewContent(DetailContentPagerAdapter.java:150)
// 	at com.masteryconnect.StandardsApp.view.DetailContentPagerAdapter.instantiateItem(DetailContentPagerAdapter.java:431)
// 	at android.support.v4.view.PagerAdapter.instantiateItem(PagerAdapter.java:110)
// 	at android.support.v4.view.ViewPager.addNewItem(ViewPager.java:832)
// 	at android.support.v4.view.ViewPager.populate(ViewPager.java:982)
// 	at android.support.v4.view.ViewPager.populate(ViewPager.java:914)
// 	at android.support.v4.view.ViewPager.onMeasure(ViewPager.java:1436)
// 	at android.view.View.measure(View.java:18794)
// 	at android.widget.RelativeLayout.measureChildHorizontal(RelativeLayout.java:715)
// 	at android.widget.RelativeLayout.onMeasure(RelativeLayout.java:461)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at android.view.View.measure(View.java:18794)
// 	at android.widget.RelativeLayout.measureChildHorizontal(RelativeLayout.java:715)
// 	at android.widget.RelativeLayout.onMeasure(RelativeLayout.java:461)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1465)
// 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:748)
// 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:630)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:5951)
// 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:194)
// 	at com.android.internal.policy.PhoneWindow$DecorView.onMeasure(PhoneWindow.java:2643)
// 	at android.view.View.measure(View.java:18794)
// 	at android.view.ViewRootImpl.performMeasure(ViewRootImpl.java:2100)
// 	at android.view.ViewRootImpl.measureHierarchy(ViewRootImpl.java:1216)
// 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1452)
// 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1107)
// 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6013)
// 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:858)
// 	at android.view.Choreographer.doCallbacks(Choreographer.java:670)
// 	at android.view.Choreographer.doFrame(Choreographer.java:606)
// 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:844)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



