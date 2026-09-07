plugins {
    id 'com.android.library'
}

group 'io.paratoner.flutter_tesseract_ocr'
version '1.0'

repositories {
    google()
    mavenCentral()
}

android {
    namespace 'io.paratoner.flutter_tesseract_ocr'
    compileSdk 36

    defaultConfig {
        minSdk 21
        testInstrumentationRunner 'androidx.test.runner.AndroidJUnitRunner'
    }

    lint {
        disable 'InvalidPackage'
    }
}

dependencies {
    api files('libs/tesseract4android-release.aar')
}
