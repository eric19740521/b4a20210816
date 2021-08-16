#Android安卓手機 寫入檔案權限設定 (B4A/B4X)


0.介紹APP操作流程
 
1. 


2.檔案位置
b4a.example

3.程式碼介紹/LIB使用


<uses-sdk android:minSdkVersion="5" android:targetSdkVersion="28"/>
設定 28,不要改29 /30 以上的數字

AddManifestText(<uses-permission
android:name="android.permission.WRITE_EXTERNAL_STORAGE"
android:maxSdkVersion="18" />
)
這個沒用處
