# lab
 testImplementation 'junit:junit:4.12'
    testImplementation "org.mockito:mockito-core:$mockitoVersion"
    testImplementation "org.assertj:assertj-core:$assertVersion"

    // For Resolve conflicts between main and test APK:
    androidTestImplementation 'com.android.support:support-annotations:28.0.0-alpha3'

    // For Android
    implementation 'com.android.support:appcompat-v7:28.0.0-alpha3'
    implementation 'com.android.support:cardview-v7:28.0.0-alpha3'
    implementation 'com.android.support:recyclerview-v7:28.0.0-alpha3'
    implementation 'com.android.support:design:28.0.0-alpha3'
    implementation 'com.android.support.constraint:constraint-layout:1.1.1'

    // For Kotlin
    implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk8:$kotlin_version"
