Use system's package manager or manually install JDK.

After installation, determine the path to the Java binaries.
**Homebrew on macOS:** `/usr/local/opt/openjdk/libexec/openjdk.jdk/Contents/Home`

Update environment variables:
```
export JAVA_HOME="/path/to/java"
export PATH="$JAVA_HOME/bin:$PATH"
```

Reload configuration:
```
source ~/.zshrc
```

Checks:
```
java -version
echo $JAVA_HOME
```
