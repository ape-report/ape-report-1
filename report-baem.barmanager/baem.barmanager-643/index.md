title: baem.barmanager

# baem.barmanager

[Google Play Store](https://play.google.com/store/apps/details?id=baem.barmanager)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteQuery: SELECT ingredients._id AS ingredientId, ingredients.title AS title, recipesToIngredients.amount AS amount, units._id AS unitId, units.title AS unit, alcoholic, available FROM recipesToIngredients, ingredients, units WHERE recipesToIngredients.id_ingredient = ingredients._id AND recipesToIngredients.unit = units._id AND recipesToIngredients.id_recipe = ? ORDER BY alcoholic DESC, amount DESC, title ASC
// 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
// 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:58)
// 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:151)
// 	at android.database.sqlite.SQLiteCursor.onMove(SQLiteCursor.java:123)
// 	at android.database.AbstractCursor.moveToPosition(AbstractCursor.java:236)
// 	at android.database.AbstractCursor.moveToFirst(AbstractCursor.java:258)
// 	at baem.barmanager.view.recipes.RecipeDetailFragment.getMailText(RecipeDetailFragment.java:320)
// 	at baem.barmanager.view.recipes.RecipeDetailFragment.onOptionsItemSelected(RecipeDetailFragment.java:418)
// 	at android.support.v4.app.Watson.onMenuItemSelected(Watson.java:126)
// 	at com.actionbarsherlock.ActionBarSherlock.callbackOptionsItemSelected(ActionBarSherlock.java:604)
// 	at com.actionbarsherlock.internal.ActionBarSherlockNative.dispatchOptionsItemSelected(ActionBarSherlockNative.java:92)
// 	at com.actionbarsherlock.app.SherlockFragmentActivity.onMenuItemSelected(SherlockFragmentActivity.java:204)
// 	at com.android.internal.policy.PhoneWindow.onMenuItemSelected(PhoneWindow.java:1151)
// 	at com.android.internal.view.menu.MenuBuilder.dispatchMenuItemSelected(MenuBuilder.java:761)
// 	at com.android.internal.view.menu.MenuItemImpl.invoke(MenuItemImpl.java:152)
// 	at com.android.internal.view.menu.MenuBuilder.performItemAction(MenuBuilder.java:904)
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



