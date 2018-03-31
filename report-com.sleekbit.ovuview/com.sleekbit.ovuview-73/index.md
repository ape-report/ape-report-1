title: com.sleekbit.ovuview

# com.sleekbit.ovuview

[Google Play Store](https://play.google.com/store/apps/details?id=com.sleekbit.ovuview)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 31771, tid: 31771, name: leekbit.ovuview  >>> com.sleekbit.ovuview <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
// Abort message: 'Error, cannot access an invalid/free'd bitmap here!'
//     r0 00000000  r1 00007c1b  r2 00000006  r3 b6fcfb7c
//     r4 b6fcfb84  r5 b6fcfb34  r6 0000000b  r7 0000010c
//     r8 134da100  r9 b4db6500  sl 700d37d0  fp 700d37d0
//     ip 00000006  sp befb9878  lr b6d3eb61  pc b6d40f50  cpsr 400f0010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 0000864b  /system/lib/libcutils.so (__android_log_assert+86)
//     #06 pc 0008d5b7  /system/lib/libandroid_runtime.so (_ZNK7android6Bitmap11assertValidEv+18)
//     #07 pc 0008d633  /system/lib/libandroid_runtime.so (_ZN7android6Bitmap11getSkBitmapEP8SkBitmap+6)
//     #08 pc 000965c7  /system/lib/libandroid_runtime.so
//     #09 pc 7286daef  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)

```



