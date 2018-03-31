title: com.urbanoutfitters.android

# com.urbanoutfitters.android

[Google Play Store](https://play.google.com/store/apps/details?id=com.urbanoutfitters.android)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// java.lang.NullPointerException: Attempt to read from field 'int com.urbn.android.data.model.UrbnSiteConfiguration$Site.backorderPaddingDays' on a null object reference
// 	at com.urbn.android.data.model.UrbnSkuInfo$Slice$SliceItem$IncludedSku.getAvailabilityDateForDisplay(UrbnSkuInfo.java:114)
// 	at com.urbn.android.view.fragment.ProductDetailsFragment.updateSelectedSizeIndex(ProductDetailsFragment.java:307)
// 	at com.urbn.android.view.fragment.ProductDetailsFragment.access$2000(ProductDetailsFragment.java:110)
// 	at com.urbn.android.view.fragment.ProductDetailsFragment$13.onItemSelected(ProductDetailsFragment.java:1146)
// 	at com.urbn.android.view.widget.SpinnerForAnalytics.onItemSelected(SpinnerForAnalytics.java:60)
// 	at android.widget.AdapterView.fireOnSelected(AdapterView.java:931)
// 	at android.widget.AdapterView.dispatchOnItemSelected(AdapterView.java:920)
// 	at android.widget.AdapterView.-wrap1(AdapterView.java)
// 	at android.widget.AdapterView$SelectionNotifier.run(AdapterView.java:890)
// 	at android.os.Handler.handleCallback(Handler.java:739)
// 	at android.os.Handler.dispatchMessage(Handler.java:95)
// 	at android.os.Looper.loop(Looper.java:148)
// 	at android.app.ActivityThread.main(ActivityThread.java:5417)
// 	at java.lang.reflect.Method.invoke(Native Method)
// 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
// 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)

```



