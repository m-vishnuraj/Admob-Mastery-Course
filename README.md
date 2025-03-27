# Admob-Mastery-Course

#### android/app/src/main/AndroidManifest.xml

    <!-- Add internet permission - essential for ad loading -->
    <uses-permission android:name="android.permission.INTERNET" />
    <!-- Add network state permission - helps with ad loading optimization -->
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />


    <meta-data
            android:name="com.google.android.gms.ads.APPLICATION_ID"
            android:value="ca-app-pub-xxxxxxxxxxxxxxxx~yyyyyyyyyy"/>


#### ios/Runner/Info.plist

    <key>GADApplicationIdentifier</key>
    <string>ca-app-pub-2489147968860162~3865941430</string>
    <key>NSUserTrackingUsageDescription</key>
    <string>This identifier will be used to deliver personalized ads to you and helps keep this app free.</string>

#### ios/Podfile

    platform :ios, '10.0'
