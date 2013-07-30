Requirements
-----
* ensure to use the latest Android SDK Build Tools available (18 as this readme being written). 
* install Android Support Repository
* install Google Repository

If you're using support library use latest available version. It's easy:

    dependencies {
        compile 'com.android.support:support-v4:+'
    }


Example
-----
Here's a simple example of `build.gradle` with actionbarsherlock included:

    buildscript {
        repositories {
            mavenCentral()
        }
        dependencies {
            classpath 'com.android.tools.build:gradle:0.5+'
        }
    }
    
    apply plugin: 'android'
    
    repositories {
        mavenCentral()
            maven {
                url "https://github.com/skyisle/abs-aar/raw/master"
            }
    }
    
    dependencies {
        compile 'com.actionbarsherlock:actionbarsherlock:4.3.2-SNAPSHOT@aar'
    }
