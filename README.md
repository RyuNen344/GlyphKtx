# GlyphKtx

[![Maven Central](https://img.shields.io/maven-central/v/io.github.ryunen344.glyph/glyph-ktx?style=plastic)](https://central.sonatype.com/search?q=io.github.ryunen344.glyph)
[![jitpack](https://jitpack.io/v/RyuNen344/GlyphKtx.svg)](https://jitpack.io/#RyuNen344/GlyphKtx)

## Setup

### MavenCentral

Set your `settings.gradle` like below

```groovy:settings.gradle
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
    }
}
```

Set your `build.gradle` like below

```groovy:settings.gradle
dependencies {
    // coroutine
    implementation 'io.github.ryunen344.glyph:glyph-ktx:${version}'
    
    // compose
    implementation 'io.github.ryunen344.glyph:glyph-compose:${version}'
}
```

### JitPack

Set your `settings.gradle` like below

```groovy:settings.gradle
dependencyResolutionManagement {
    repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
    repositories {
        google()
        mavenCentral()
        maven { url 'https://jitpack.io' }
    }
}
```

Set your `build.gradle` like below

```groovy:settings.gradle
dependencies {
    // moshi
    implementation 'com.github.RyuNen344.GlyphKtx:glyph-ktx:${version}'
    
    // compose
    implementation 'com.github.RyuNen344.GlyphKtx:glyph-compose:${version}'
}
```

## Usage

### ktx


### compose


# License

```
Copyright 2024 RyuNen344

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   https://www.apache.org/licenses/LICENSE-2.0.txt

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
