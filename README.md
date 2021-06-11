# Disable white screen before splash on Android devices

1. Go to _android/app/src/main/res/values/styles.xml_
2. Disable the app's preview as follows:

`<style name="AppTheme" parent="Theme.AppCompat.DayNight.NoActionBar">
<!-- Customize your theme here. -->
 <item name="android:windowDisablePreview">true</item><!-- Add this line -->
 <item name="android:textColor">#000000</item>
</style>`
