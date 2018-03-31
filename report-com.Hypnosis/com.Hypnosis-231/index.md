title: com.Hypnosis

# com.Hypnosis

[Google Play Store](https://play.google.com/store/apps/details?id=com.Hypnosis)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: The specified child already has a parent. You must call removeView() on the child's parent first.
// 	at android.view.ViewGroup.addViewInner(ViewGroup.java:4309)
// 	at android.view.ViewGroup.addView(ViewGroup.java:4145)
// 	at android.view.ViewGroup.addView(ViewGroup.java:4086)
// 	at android.view.ViewGroup.addView(ViewGroup.java:4059)
// 	at android.support.v7.widget.Toolbar.addChildrenForExpandedActionView(Toolbar.java:1797)
// 	at android.support.v7.widget.Toolbar$ExpandedActionViewMenuPresenter.collapseItemActionView(Toolbar.java:2039)
// 	at android.support.v7.view.menu.MenuBuilder.collapseItemActionView(MenuBuilder.java:1345)
// 	at android.support.v7.view.menu.MenuItemImpl.collapseActionView(MenuItemImpl.java:705)
// 	at android.support.v7.widget.Toolbar.collapseActionView(Toolbar.java:558)
// 	at android.support.v7.widget.Toolbar$3.onClick(Toolbar.java:1053)
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



