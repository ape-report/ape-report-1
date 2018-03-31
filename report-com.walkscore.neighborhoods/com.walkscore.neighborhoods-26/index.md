title: com.walkscore.neighborhoods

# com.walkscore.neighborhoods

[Google Play Store](https://play.google.com/store/apps/details?id=com.walkscore.neighborhoods)

[Timeline](./vis-timeline.html)

<iframe src="./vis-timeline.html" width="100%" height="500px" style="border:none;"></iframe>

```
// *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
// Build fingerprint: 'google/hammerhead/hammerhead:6.0.1/M4B30Z/3437181:user/release-keys'
// Revision: '11'
// ABI: 'arm'
// pid: 14484, tid: 14858, name: Thread-949  >>> com.walkscore.neighborhoods <<<
// signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x8e4a1000
//     r0 9204fdcc  r1 00000000  r2 000003d4  r3 8e4a0c00
//     r4 00000100  r5 00000000  r6 9791da04  r7 b697835d
//     r8 9204fdcc  r9 9204fe34  sl 000003d4  fp 000000ff
//     ip b6941fb5  sp 9204f218  lr b69420cd  pc b697836e  cpsr 800b0030
// 
// backtrace:
//     #00 pc 0012036e  /system/lib/libskia.so (_ZN13SkColorShader18ColorShaderContext9shadeSpanEiiPji+17)
//     #01 pc 000ea0cb  /system/lib/libskia.so (_ZN23SkARGB32_Shader_Blitter9blitAntiHEiiPKhPKs+278)
//     #02 pc 0011d0b3  /system/lib/libskia.so (_ZN12SuperBlitter5flushEv+50)
//     #03 pc 0011d0f1  /system/lib/libskia.so (_ZN12SuperBlitter5blitHEiii+44)
//     #04 pc 0011f825  /system/lib/libskia.so
//     #05 pc 0011fd31  /system/lib/libskia.so (_Z12sk_fill_pathRK6SkPathPK7SkIRectP9SkBlitteriiiRK8SkRegion+316)
//     #06 pc 0011d669  /system/lib/libskia.so (_ZN6SkScan12AntiFillPathERK6SkPathRK8SkRegionP9SkBlitterb+640)
//     #07 pc 0011d7c9  /system/lib/libskia.so (_ZN6SkScan12AntiFillPathERK6SkPathRK12SkRasterClipP9SkBlitter+28)
//     #08 pc 000f771d  /system/lib/libskia.so (_ZNK6SkDraw8drawPathERK6SkPathRK7SkPaintPK8SkMatrixbbP9SkBlitter+604)
//     #09 pc 000e073d  /system/lib/libskia.so (_ZN14SkBitmapDevice8drawPathERK6SkDrawRK6SkPathRK7SkPaintPK8SkMatrixb+24)
//     #10 pc 000e08b5  /system/lib/libskia.so (_ZN14SkBitmapDevice8drawOvalERK6SkDrawRK6SkRectRK7SkPaint+54)
//     #11 pc 000f04af  /system/lib/libskia.so (_ZN8SkCanvas10onDrawOvalERK6SkRectRK7SkPaint+206)
//     #12 pc 000ef0a9  /system/lib/libskia.so (_ZN8SkCanvas10drawCircleEfffRK7SkPaint+140)
//     #13 pc 72ea26f7  /data/dalvik-cache/arm/system@framework@boot.oat (offset 0x1ed6000)

```



