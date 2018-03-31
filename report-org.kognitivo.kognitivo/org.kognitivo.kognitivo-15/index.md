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
// pid: 8762, tid: 8815, name: Thread-6946  >>> org.kognitivo.kognitivo:python <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x1
//     r0 00000020  r1 00000001  r2 00000054  r3 00000001
//     r4 00000000  r5 00000001  r6 a140cbe4  r7 00000001
//     r8 13543000  r9 a0ac2500  sl 1348e170  fp 00000008
//     ip b3bca030  sp a0cbf238  lr a12f9f88  pc a121f6f4  cpsr 200f0010
// 
// backtrace:
//     #00 pc 000996f4  /data/app/org.kognitivo.kognitivo-1/lib/arm/libpython2.7.so (PyObject_Malloc+148)
//     #01 pc 00173f84  /data/app/org.kognitivo.kognitivo-1/lib/arm/libpython2.7.so (_PyObject_GC_Malloc+48)
// 
*** INFO Try to clear package org.kognitivo.kognitivo
*** INFO Try to grant saved permission to org.kognitivo.kognitivo for clearing package... 
*** INFO Try to grant saved permission to org.kognitivo.kognitivo for generating activity events... 
Generate activity event for activity ComponentInfo{org.kognitivo.kognitivo/org.renpy.android.PythonActivity} from 0 of 1
*** INFO Let's wait for activity loading...
Encounter abort but we are in continuous mode.
Force to stop all activites and make a restart.
*** INFO Expected activity package [org.kognitivo.kognitivo] is loaded...
// CRASH: org.kognitivo.kognitivo:python (pid 8852) (elapsed nanos: 48144382316223)
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



