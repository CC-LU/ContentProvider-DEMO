# ContentProvider_DEMO
使用ContentProvider 內容提供器
完成兩項通訊
1.程序內通訊
2.跨程序通訊

注意權限使用的問題
`<manifest>
    <permission
    android:name="scut.carson_ho.PERMISSION"
    android:label="provider read pomission"
    android:protectionLevel="normal" />
<provider
    android:name="MyProvider"
    android:authorities="scut.carson_ho.myprovider"
    android:permission = "scut.carson_ho.PERMISSION"
    android:exported="true"
/>`

參考<br>
https://github.com/Carson-Ho/ContentProvider  
https://github.com/Carson-Ho/ContentProvider2
