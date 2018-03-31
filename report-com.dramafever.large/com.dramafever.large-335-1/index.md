title: com.dramafever.large

# com.dramafever.large

[Google Play Store](https://play.google.com/store/apps/details?id=com.dramafever.large)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.RuntimeException: Unable to create application com.dramafever.large.DFApplication: android.database.sqlite.SQLiteException: Failed to change locale for db '/data/user/0/com.dramafever.large/databases/__hs__db' to 'en_US'.
// 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4710)
// 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
// 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
// 	at android.os.Handler.dispatchMessage(Handler.java:102)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
// Caused by: android.database.sqlite.SQLiteException: Failed to change locale for db '/data/user/0/com.dramafever.large/databases/__hs__db' to 'en_US'.
// 	at android.database.sqlite.SQLiteConnection.setLocaleFromConfiguration(SQLiteConnection.java:391)
// 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:216)
// 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
// 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
// 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
// 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
// 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
// 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
// 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
// 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
// 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
// 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
// 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
// 	at com.helpshift.HelpshiftDb.getWritableDatabase(HelpshiftDb.java:32)
// 	at com.helpshift.HelpshiftDb.<init>(HelpshiftDb.java:19)
// 	at com.helpshift.HelpshiftDb.getInstance(HelpshiftDb.java:24)
// 	at com.helpshift.HSSectionDb.<init>(HSSectionDb.java:26)
// 	at com.helpshift.HSSectionDataSource.<init>(HSSectionDataSource.java:32)
// 	at com.helpshift.HSApiData.<init>(HSApiData.java:75)
// 	at com.helpshift.Helpshift.initialize(Helpshift.java:138)
// 	at com.helpshift.Helpshift.init(Helpshift.java:129)
// 	at com.helpshift.Helpshift.install(Helpshift.java:237)
// 	at com.helpshift.Helpshift.install(Helpshift.java:197)
// 	at com.dramafever.large.DFApplication.onCreate(DFApplication.java:71)
// 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
// 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
// 	... 8 more
// Caused by: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 1032)
// 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
// 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
// 	at android.database.sqlite.SQLiteConnection.setLocaleFromConfiguration(SQLiteConnection.java:382)
// 	... 33 more

```



