```xml 
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:tools="http://schemas.android.com/tools">

    <application
        android:name=".Birth"
        android:icon="@mipmap/ic_launcher"
        android:label="Abolfazl Radmanesh"
        android:supportsRtl="true"
        tools:targetApi="23">
        <activity
            android:name=".Life"
            android:exported="true">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>
    </application>

</manifest> 
```

```kotlin 
import android.app.Application

class Birth : Application() {
    override fun onCreate() {
        super.onCreate()

        while (true) {
            println("Learning Android......")
        }
    }
}
```

```kotlin 
import androidx.appcompat.app.AppCompatActivity
import android.os.Bundle

class Life : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.life_view)


        while (!this.isFinishing) {
            for (totalHours in 0..24) {
                println("Coding for Android...")
            }
        }
        println("It went beautifully...")

    }
}
```
