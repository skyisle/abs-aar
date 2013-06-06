Usage
-----
BE CAREFUL. 
This aar has dependency with 'com.android.support:support-v4:13.0.0' instead of 'com.google.android:support-v4:r7' for personal purpose.

    buildscript {
        repositories {
            mavenCentral()
        }
        dependencies {
            classpath 'com.android.tools.build:gradle:0.4.2'
        }
    }
    
    apply plugin: 'android'
    
    repositories {
        mavenCentral()
            maven {
                url "https://github.com/skyisle/mvn-repo/raw/master"
            }
    }
    
    dependencies {
        compile 'com.actionbarsherlock:actionbarsherlock:4.3.2-SNAPSHOT'
    }


