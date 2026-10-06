# tower-java-sdk

> [!WARNING]
> **Deprecated.** This repository's GitHub Packages registry no longer receives new releases of `tower-java-sdk`.
> New versions are published to the Seqera Maven repository. Versions already published here remain available.

The SDK is generated and published from [seqeralabs/tower-sdk-gencode](https://github.com/seqeralabs/tower-sdk-gencode).

## Using the SDK

The coordinates are unchanged: `io.seqera.tower:tower-java-sdk:<version>`. Reading from the Seqera Maven repository
requires no credentials.

Repository URL: https://s3-eu-west-1.amazonaws.com/maven.seqera.io/releases

Gradle:

```groovy
repositories {
    mavenCentral()
    maven { url = 'https://s3-eu-west-1.amazonaws.com/maven.seqera.io/releases' }
}

dependencies {
    implementation 'io.seqera.tower:tower-java-sdk:<version>'
}
```

Maven:

```xml
<repositories>
    <repository>
        <id>seqera</id>
        <url>https://s3-eu-west-1.amazonaws.com/maven.seqera.io/releases</url>
    </repository>
</repositories>
```
