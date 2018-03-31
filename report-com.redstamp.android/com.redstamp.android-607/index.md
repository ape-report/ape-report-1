title: com.redstamp.android

# com.redstamp.android

[Google Play Store](https://play.google.com/store/apps/details?id=com.redstamp.android)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to start activity ComponentInfo{com.redstamp.android/com.redstamp.android.activity.ProductListingActivity}: android.database.sqlite.SQLiteException: no such table: message_dictionary_nodes (code 1): , while compiling: SELECT DISTINCT messageDictionaryNodeId, key, value, position, occasionId, themeId, audienceId, nextChoiceDefaultText, isActive, parentId FROM message_dictionary_nodes WHERE (key = ? AND parentId IS NULL)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2416)
// 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2476)
// 	at android.app.ActivityThread.-wrap11(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: android.database.sqlite.SQLiteException: no such table: message_dictionary_nodes (code 1): , while compiling: SELECT DISTINCT messageDictionaryNodeId, key, value, position, occasionId, themeId, audienceId, nextChoiceDefaultText, isActive, parentId FROM message_dictionary_nodes WHERE (key = ? AND parentId IS NULL)
// 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
// 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:887)
// 	at android.database.sqlite.SQLiteConnection.prepare(SQLiteConnection.java:498)
// 	at android.database.sqlite.SQLiteSession.prepare(SQLiteSession.java:588)
// 	at android.database.sqlite.SQLiteProgram.<init>(SQLiteProgram.java:58)
// 	at android.database.sqlite.SQLiteQuery.<init>(SQLiteQuery.java:37)
// 	at android.database.sqlite.SQLiteDirectCursorDriver.query(SQLiteDirectCursorDriver.java:44)
// 	at android.database.sqlite.SQLiteDatabase.rawQueryWithFactory(SQLiteDatabase.java:1316)
// 	at android.database.sqlite.SQLiteQueryBuilder.query(SQLiteQueryBuilder.java:400)
// 	at android.database.sqlite.SQLiteQueryBuilder.query(SQLiteQueryBuilder.java:294)
// 	at com.redstamp.android.provider.Provider.query(Unknown Source)
// 	at android.content.ContentProvider.query(ContentProvider.java:1017)
// 	at android.content.ContentProvider$Transport.query(ContentProvider.java:238)
// 	at android.content.ContentResolver.query(ContentResolver.java:491)
// 	at android.content.ContentResolver.query(ContentResolver.java:434)
// 	at com.redstamp.android.activity.ProductListingActivity.onCreate(Unknown Source)
// 	at android.app.Activity.performCreate(Activity.java:6251)
// 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1107)
// 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2369)
// 	... 9 more

```



