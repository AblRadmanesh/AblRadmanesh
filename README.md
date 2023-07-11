# صحبت اولیه
سلام من **ابوالفضل رادمنش** هستم .

دانشجوی رشته نرم افزار و علاقه مند به برنامه نویسی اندروید ، همچنین من عاشق تدریسم که برای آشنا شدن با نحوه تدریسم میتوانید داخل یوتیوب یا حتی خود همین برنامه نمونه تدریسم رو مشاهده کنید. پس کافیه روی آیکون یوتیوب کلیک کنی تا من بهت پیشنهادمو بدم!

در ضمن من دوست دارم برنامه نویسی باشم که خلاقه در عین حال به بهینه و تمیز بودن کدش اهمیت میده و سعی میکنه یه محیط نسبتا ساده اما زیبا رو به کاربرش هدیه بده بدون شک کاربرای من لایق بهترین ها هستن.

# دانشگاه ها :

[خوارزمی شهرضا](https://p-shahreza.tvu.ac.ir/)

[شمسی پور تهران](https://shamsipour.tvu.ac.ir/)

[باهنر شیراز](https://bahonarshiraz.tvu.ac.ir/)



# مدارک :

[Graphic Designer](http://learndotroid.com/Radmanesh/Me/Fa/image/Computer%20Graphic%20Designer.png)

[Computer Operator](http://learndotroid.com/Radmanesh/Me/Fa/image/Computer%20Operator.png)

[CorelDraw Operator](http://learndotroid.com/Radmanesh/Me/Fa/image/CorelDraw%20Operator.png)

[E-Citizen](http://learndotroid.com/Radmanesh/Me/Fa/image/E-Citizen.png)

[Flash Mx Operator](http://learndotroid.com/Radmanesh/Me/Fa/image/Flash%20Mx%20Operator.png)

[Freehand Operator](http://learndotroid.com/Radmanesh/Me/Fa/image/Freehand%20Operator.png)

[Office Software Operator](http://learndotroid.com/Radmanesh/Me/Fa/image/Office%20Software%20Operator.png)

# من به تفسیر اندروید :
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
