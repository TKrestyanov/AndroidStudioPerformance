# AndroidStudioPerformance


# VM options
-server
-Xms1024m
-Xmx4096m
-XX:MetaspaceSize=512m
-XX:MaxPermSize=1024m
-XX:ReservedCodeCacheSize=256m
-XX:+UseCompressedOops




# gradle.properties

org.gradle.jvmargs=-Xmx2048m -XX:MaxPermSize=512m -XX:+HeapDumpOnOutOfMemoryError -Dfile.encoding=UTF-8 -XX:+UseParallelGC 
android.useAndroidX=true
kotlin.code.style=official
org.gradle.daemon=true
org.gradle.parallel=true
org.gradle.configureondemand=true
org.gradle.caching=true
kapt.use.worker.api=true
room.incremental=true
org.gradle.unsafe.watch-fs=true





# Now, disable or Check Off all the plugins which not usable for you. I have disabled following:

Android APK Support
Android Games
Android NDK
App Links Assistant
Copyright
Coverage
CVS Integeration
Editor Config
Fabric for Android Studio
Firebase (App Indexing, Services, Testing)
Github
Google (Cloud Tools Core, Cloud Tools for Android, Developer Samples, Login, Services)
Markdown Support
Mercurial integration
hg4idea
Settings repository
Subversion integration
Task management
Test recorder
TestNG-J
YAML
