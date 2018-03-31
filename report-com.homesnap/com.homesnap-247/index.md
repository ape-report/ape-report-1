title: com.homesnap

# com.homesnap

[Google Play Store](https://play.google.com/store/apps/details?id=com.homesnap)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to invoke virtual method 'android.widget.Filter com.homesnap.mls.HsMlsItemAdapter.getFilter()' on a null object reference
// 	at com.homesnap.mls.MlsListAllFragment.onQueryTextChange(MlsListAllFragment.java:218)
// 	at android.support.v7.widget.SearchView.onTextChanged(SearchView.java:1118)
// 	at android.support.v7.widget.SearchView.access$2000(SearchView.java:103)
// 	at android.support.v7.widget.SearchView$12.onTextChanged(SearchView.java:1578)
// 	at android.widget.TextView.sendOnTextChanged(TextView.java:7988)
// 	at android.widget.TextView.setText(TextView.java:4350)
// 	at android.widget.TextView.setText(TextView.java:4204)
// 	at android.widget.EditText.setText(EditText.java:84)
// 	at android.widget.TextView.setText(TextView.java:4179)
// 	at android.support.v7.widget.SearchView.onActionViewExpanded(SearchView.java:1231)
// 	at android.support.v7.internal.view.menu.MenuItemWrapperICS$CollapsibleActionViewWrapper.onActionViewExpanded(MenuItemWrapperICS.java:449)
// 	at com.android.internal.widget.ActionBarView$ExpandedActionViewMenuPresenter.expandItemActionView(ActionBarView.java:1673)
// 	at com.android.internal.view.menu.MenuBuilder.expandItemActionView(MenuBuilder.java:1266)
// 	at com.android.internal.view.menu.MenuItemImpl.expandActionView(MenuItemImpl.java:625)
// 	at com.android.internal.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:909)
// 	at com.android.internal.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:894)
// 	at android.widget.ActionMenuView.invokeItem(ActionMenuView.java:616)
// 	at com.android.internal.view.menu.ActionMenuItemView.onClick(ActionMenuItemView.java:141)
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



