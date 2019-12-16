## Version

```bash
brew tap AdoptOpenJDK/homebrew-openjdkbrew cask install adoptopenjdk8
brew cask install adoptopenjdk8

/usr/libexec/java_home -V

export JAVA_HOME=(/usr/libexec/java_home -v 1.8.0_232)
java -version

export JAVA_HOME=(/usr/libexec/java_home -v 13.0.1)
java -version
```

## Resource

- [Switching Java Versions on macOS](https://www.kevinhooke.com/2017/10/05/switching-java-versions-on-mac-os)