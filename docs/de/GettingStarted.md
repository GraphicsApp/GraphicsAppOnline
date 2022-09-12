# Hello GraphicsApp

Die GraphicsApp-API kann direkt via Gradle eingebunden werden. 

```groovy
repositories {
    mavenCentral()
    maven {
        url = uri("https://maven.pkg.github.com/GraphicsApp/GraphicsApp")
        credentials {
            username = "graphicsapp-dev"
            password = "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"
        }
    }
}

dependencies {
    implementation 'de.ur.mi.oop:graphicsapp:1.4.11'
    testImplementation 'org.junit.jupiter:junit-jupiter-api:5.9.0'
    testRuntimeOnly 'org.junit.jupiter:junit-jupiter-engine:5.9.0'
}
```