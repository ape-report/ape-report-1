title: com.pose

# com.pose

```
// com.google.gson.JsonSyntaxException: com.google.gson.stream.MalformedJsonException: Use JsonReader.setLenient(true) to accept malformed JSON at line 1 column 12 path $
// 	at com.google.gson.JsonParser.parse(JsonParser.java:65)
// 	at com.google.gson.JsonParser.parse(JsonParser.java:45)
// 	at com.pose.processors.SignInProcessor$1.onResponse(SignInProcessor.java:136)
// 	at com.squareup.okhttp.Call$AsyncCall.execute(Call.java:150)
// 	at com.squareup.okhttp.internal.NamedRunnable.run(NamedRunnable.java:33)
// 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
// 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
// 	at java.lang.Thread.run(Thread.java:818)
// Caused by: com.google.gson.stream.MalformedJsonException: Use JsonReader.setLenient(true) to accept malformed JSON at line 1 column 12 path $
// 	at com.google.gson.stream.JsonReader.syntaxError(JsonReader.java:1573)
// 	at com.google.gson.stream.JsonReader.checkLenient(JsonReader.java:1423)
// 	at com.google.gson.stream.JsonReader.doPeek(JsonReader.java:546)
// 	at com.google.gson.stream.JsonReader.peek(JsonReader.java:429)
// 	at com.google.gson.JsonParser.parse(JsonParser.java:60)
// 	... 7 more

```



