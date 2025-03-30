# github-gradle-kotline-ci-sample



# サンプルコード

本リポジトリのコードは `$ gradle init` を以下のオプションで実行したものです

```bash
$ gradle init
Starting a Gradle Daemon (subsequent builds will be faster)

Found existing files in the project directory: '/Users/jsmith/quiver/github-gradle-kotline-ci-sample'.
Directory will be modified and existing files may be overwritten.  Continue? (default: no) [yes, no] yes

Select type of build to generate:
  1: Application
  2: Library
  3: Gradle plugin
  4: Basic (build structure only)
Enter selection (default: Application) [1..4] 1

Select implementation language:
  1: Java
  2: Kotlin
  3: Groovy
  4: Scala
  5: C++
  6: Swift
Enter selection (default: Java) [1..6] 2

Enter target Java version (min: 7, default: 21): 21

Project name (default: github-gradle-kotline-ci-sample):

Select application structure:
  1: Single application project
  2: Application and library project
Enter selection (default: Single application project) [1..2] 1

Select build script DSL:
  1: Kotlin
  2: Groovy
Enter selection (default: Kotlin) [1..2] 1

Select test framework:
  1: kotlin.test
  2: JUnit Jupiter
Enter selection (default: kotlin.test) [1..2] 1

Generate build using new APIs and behavior (some features may change in the next minor release)? (default: no) [yes, no] no


> Task :init
Learn more about Gradle by exploring our Samples at https://docs.gradle.org/8.13/samples/sample_building_kotlin_applications.html

BUILD SUCCESSFUL in 48s
1 actionable task: 1 executed
```

# gradle バージョン


```bash
$ gradle --version

------------------------------------------------------------
Gradle 8.13
------------------------------------------------------------

Build time:    2025-02-25 09:22:14 UTC
Revision:      073314332697ba45c16c0a0ce1891fa6794179ff

Kotlin:        2.0.21
Groovy:        3.0.22
Ant:           Apache Ant(TM) version 1.10.15 compiled on August 25 2024
Launcher JVM:  23.0.2 (Homebrew 23.0.2)
Daemon JVM:    /opt/homebrew/Cellar/openjdk/23.0.2/libexec/openjdk.jdk/Contents/Home (no JDK specified, using current Java home)
OS:            Mac OS X 14.7 aarch64
```