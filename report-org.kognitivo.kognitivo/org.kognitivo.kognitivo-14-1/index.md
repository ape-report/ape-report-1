title: org.kognitivo.kognitivo

# org.kognitivo.kognitivo

[Google Play Store](https://play.google.com/store/apps/details?id=org.kognitivo.kognitivo)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 8622, tid: 8662, name: Thread-6934  >>> org.kognitivo.kognitivo:python <<<
// signal 6 (SIGABRT), code -6 (SI_TKILL), fault addr --------
//     r0 00000000  r1 000021d6  r2 00000006  r3 9c040978
//     r4 9c040980  r5 9c040930  r6 00000002  r7 0000010c
//     r8 12c0fc00  r9 9c18a300  sl 12d4b4b0  fp 00000008
//     ip 00000006  sp 9c040298  lr b6cf5b61  pc b6cf7f50  cpsr 40070010
// 
// backtrace:
//     #00 pc 00041f50  /system/lib/libc.so (tgkill+12)
//     #01 pc 0003fb5d  /system/lib/libc.so (pthread_kill+32)
//     #02 pc 0001c30f  /system/lib/libc.so (raise+10)
//     #03 pc 000194c1  /system/lib/libc.so (__libc_android_abort+34)
//     #04 pc 000174ac  /system/lib/libc.so (abort+4)
//     #05 pc 0015c35c  /data/app/org.kognitivo.kognitivo-1/lib/arm/libpython2.7.so (Py_FatalError+68)
// 
*** INFO Try to clear package org.kognitivo.kognitivo
*** INFO Try to grant saved permission to org.kognitivo.kognitivo for clearing package... 
*** INFO Try to grant saved permission to org.kognitivo.kognitivo for generating activity events... 
Generate activity event for activity ComponentInfo{org.kognitivo.kognitivo/org.renpy.android.PythonActivity} from 0 of 1
*** INFO Let's wait for activity loading...
Encounter abort but we are in continuous mode.
Force to stop all activites and make a restart.
*** INFO Expected activity package [org.kognitivo.kognitivo] is loaded...
// CRASH: org.kognitivo.kognitivo:python (pid 8694) (elapsed nanos: 48120126663159)
// Short Msg: java.lang.UnsatisfiedLinkError
// Long Msg: java.lang.UnsatisfiedLinkError: dlopen failed: library "/data/user/0/org.kognitivo.kognitivo/files/lib/python2.7/lib-dynload/_io.so" not found
// Build Label: google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys
// Build Changelist: 3437181
// Build Time: 1478203422000
// java.lang.UnsatisfiedLinkError: dlopen failed: library "/data/user/0/org.kognitivo.kognitivo/files/lib/python2.7/lib-dynload/_io.so" not found
// 	at java.lang.Runtime.load(Runtime.java:332)
// 	at java.lang.System.load(System.java:1069)
// 	at org.renpy.android.PythonActivity.run(PythonActivity.java:258)
// 	at java.lang.Thread.run(Thread.java:818)

```



