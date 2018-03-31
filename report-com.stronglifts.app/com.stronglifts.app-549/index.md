title: com.stronglifts.app

# com.stronglifts.app

[Google Play Store](https://play.google.com/store/apps/details?id=com.stronglifts.app)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'void com.stronglifts.app.activity.MainActivity.a_(android.support.v4.app.Fragment)' on a null object reference
// 	at com.stronglifts.app.preference.export.ExportFragment.b(ExportFragment.java:83)
// 	at android.support.v4.app.Fragment.d(Fragment.java:2474)
// 	at android.support.v4.app.n.a(FragmentManager.java:3307)
// 	at android.support.v4.app.k.a(FragmentController.java:344)
// 	at android.support.v4.app.i.onMenuItemSelected(FragmentActivity.java:367)
// 	at android.support.v7.app.c.onMenuItemSelected(AppCompatActivity.java:195)
// 	at android.support.v7.view.i.onMenuItemSelected(WindowCallbackWrapper.java:108)
// 	at android.support.v7.view.i.onMenuItemSelected(WindowCallbackWrapper.java:108)
// 	at android.support.v7.app.o$2.a(ToolbarActionBar.java:65)
// 	at android.support.v7.widget.Toolbar$1.a(Toolbar.java:202)
// 	at android.support.v7.widget.ActionMenuView$d.a(ActionMenuView.java:780)
// 	at android.support.v7.view.menu.h.a(MenuBuilder.java:822)
// 	at android.support.v7.view.menu.j.b(MenuItemImpl.java:171)
// 	at android.support.v7.view.menu.h.a(MenuBuilder.java:973)
// 	at android.support.v7.view.menu.h.a(MenuBuilder.java:963)
// 	at android.support.v7.widget.ActionMenuView.a(ActionMenuView.java:624)
// 	at android.support.v7.view.menu.ActionMenuItemView.onClick(ActionMenuItemView.java:150)
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



