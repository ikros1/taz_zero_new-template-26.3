# taz_zero_new

## Setup

For setup instructions, please see the [Fabric Documentation page](https://docs.fabricmc.net/develop/getting-started/creating-a-project#setting-up) related to the IDE that you are using.

## License

This template is available under the CC0 license. Feel free to learn from it and incorporate it in your own projects.

## Local toolchain (optional)

To keep builds independent of the machine's global Java / Gradle setup, this checkout can carry its own toolchain:

- `tools/jdk` — a JDK 26 installation used to run Gradle and javac (the project compiles with `--release 25`)
- `.gradle-user` — a project-local Gradle user home (wrapper distribution + dependency caches)

`gradlew` and `gradlew.bat` automatically use these when present and fall back to the normal system-wide setup otherwise. Both directories are git-ignored; a fresh clone simply needs a JDK 25+ (`JAVA_HOME`) and network access for the first build.
