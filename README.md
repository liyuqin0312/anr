crashReason: SIGBUS(BUS_ADRERR)
crashInfo1: 
crashInfo2: #00 pc 000000000000f050 /apex/com.android.runtime/lib64/bionic/libc.so [arm64-v8a::ddedea5a1d1071f97c5321841b6be985]
#01 pc 000000000002e63c /data/app/~~WkvFDzxAdr45ZDiiycxi6Q==/com.xiwang.zaixian-oWJBMKOY8VQV1zMvLuqK0w==/lib/arm64/libmmkv.so [arm64-v8a::1051e232057f0765b8e39437bade2b4a]
#02 pc 0000000000029910 /data/app/~~WkvFDzxAdr45ZDiiycxi6Q==/com.xiwang.zaixian-oWJBMKOY8VQV1zMvLuqK0w==/lib/arm64/libmmkv.so [arm64-v8a::1051e232057f0765b8e39437bade2b4a]
#03 pc 00000000000294c0 /data/app/~~WkvFDzxAdr45ZDiiycxi6Q==/com.xiwang.zaixian-oWJBMKOY8VQV1zMvLuqK0w==/lib/arm64/libmmkv.so [arm64-v8a::1051e232057f0765b8e39437bade2b4a]
#04 pc 0000000000028f90 /data/app/~~WkvFDzxAdr45ZDiiycxi6Q==/com.xiwang.zaixian-oWJBMKOY8VQV1zMvLuqK0w==/lib/arm64/libmmkv.so [arm64-v8a::1051e232057f0765b8e39437bade2b4a]
#05 pc 000000000001e0b8 /data/app/~~WkvFDzxAdr45ZDiiycxi6Q==/com.xiwang.zaixian-oWJBMKOY8VQV1zMvLuqK0w==/lib/arm64/libmmkv.so [arm64-v8a::1051e232057f0765b8e39437bade2b4a]
#06 pc 0000000000018430 /data/app/~~WkvFDzxAdr45ZDiiycxi6Q==/com.xiwang.zaixian-oWJBMKOY8VQV1zMvLuqK0w==/lib/arm64/libmmkv.so [arm64-v8a::1051e232057f0765b8e39437bade2b4a]
#07 pc 000000000000d9a8 /data/app/~~WkvFDzxAdr45ZDiiycxi6Q==/com.xiwang.zaixian-oWJBMKOY8VQV1zMvLuqK0w==/oat/arm64/base.odex (oatdata+51624) [arm64-v8a::6415efd98718564ab09d9fcd96cae3ca]
java:
com.tencent.mmkv.MMKV.putBoolean(MMKV.java:1060)
com.xueersi.lib.cache.sharePrefrence.SharePrefrenceCache.putBoolean(SharePrefrenceCache.java:136)
com.xueersi.common.sharedata.ShareDataManager.put(ShareDataManager.java:401)
com.xueersi.common.business.AppBll.getAppInitConfig(AppBll.java:1435)
com.xueersi.parentsmeeting.module.home.HomeV2Activity.businessControl(HomeV2Activity.java:1377)
com.xueersi.parentsmeeting.module.home.HomeV2Activity.init(HomeV2Activity.java:881)
com.xueersi.parentsmeeting.module.home.HomeV2Activity.onCreate(HomeV2Activity.java:378)
android.app.Activity.performCreate(Activity.java:8071)
android.app.Activity.performCreate(Activity.java:8054)
android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1309)
android.app.ActivityThread.performLaunchActivity(ActivityThread.java:3472)
android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:3680)
android.app.servertransaction.LaunchActivityItem.execute(LaunchActivityItem.java:85)
android.app.servertransaction.TransactionExecutor.executeCallbacks(TransactionExecutor.java:135)
android.app.servertransaction.TransactionExecutor.execute(TransactionExecutor.java:95)
android.app.ActivityThread$H.handleMessage(ActivityThread.java:2108)
com.xueersi.lib.framework.utils.LooperHook$XesHandlerCallback2.handleMessage(LooperHook.java:100)
android.os.Handler.dispatchMessage(Handler.java:102)
android.os.Looper.loop(Looper.java:223)
android.app.ActivityThread.main(ActivityThread.java:7945)
java.lang.reflect.Method.invoke(Native Method)
com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:603)
com.android.internal.os.ZygoteInit.main(ZygoteInit.java:947)
