## Gradle - Learning the Basics

Every Gradle project should have the `.gradle`, `gradle` and `build` directories, and also must have a Gradle wrapper for both 
UNIX based OS and Windows (e.g. `gradlew` and `gradlew.bat` respectively, where `gradlew` stands for `Gradle Wrapper` which is just 
the executable Gradle bin, but in the specific version that the project needs to run, I should always use the wrapper because of that).

### The `.gradle`, `gradle` and `build` directories

The `.gradle` directory is used by Gradle to store the project cache versions and stuff, it's used to store Project results to 
Incremental Builds and Cache Builds.

The `gradle` directory stores the Wrapper JAR and other configs about the Wrapper, all Wrapper needs to run is in this directory

Last but not least, the `build` directory is used to save the last build artifacts (like JARs, bins, etc.).
