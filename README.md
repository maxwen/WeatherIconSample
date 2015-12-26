Condition icon packs support
add activity with action "org.omnirom.WeatherIconPack"
the name is used to defined the prefix for the image names
default should be .weather.

```xml
		<activity
			android:name=".weather_vclouds"
			android:label="LockClock (vclouds)" >
			<intent-filter>
				<action android:name="org.omnirom.WeatherIconPack" />

				<category android:name="android.intent.category.DEFAULT" />
			</intent-filter>
		</activity>
```
