# super-spork
This is an application that uses quizez as a game based on cartoon.
The questions are 4 and are based on the activity taking place within a video.
The videos are within the raw folder. Also to add a little bit of flavour a SplashScreen is introduced at the beginning of the app.
It contains two activity.java files one for the animation which is SplashScreenActivity.java and the other is MainActivity.java.
Its also gives the user an ability to share his/her results on whatsapp.
There is an accuracy in marking meaning their cannot be redudndacy in answering. Also it prevents multiple answering.
Once the next button is clicked it assumes you have already answered the previous question.
There is also a toast that appears when the user goes through all questions

It contains :
4 TextViews
1 video View
5 Buttons
4 Checkboxes

I have included files that I dealt with during the making of the program

I uploaded the main files except only AndroidManifest.xml

Here is the code for it that I added.

<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.example.lawkeegabanna.helloandroid_">

    <application
        android:allowBackup="true"
        android:icon="@mipmap/ic_launcher"
        android:label="@string/app_name"
        android:roundIcon="@mipmap/ic_launcher_round"
        android:supportsRtl="true"
        android:theme="@style/AppTheme">
        <activity android:name=".MainActivity">
            <intent-filter>
                <action android:name="android.intent.action.MAIN" />

                <category android:name="android.intent.category.DEFAULT" />
            </intent-filter>
        </activity>

        <activity android:name=".SplashScreenActivity">
            <intent-filter>
                <action
                    android:name="android.intent.action.MAIN"/>
                <category
                    android:name="android.intent.category.LAUNCHER"/>
            </intent-filter>
        </activity>
    </application>

</manifest>

this is very necessary for the SplashScreen to work. 
https://drive.google.com/drive/folders/1sZNswH-bUz4PYocowWjBg6j_D2Eqf2d3?usp=sharing
