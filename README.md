# jdk-microbenches
OpenJDK Microbenches from latest [OpenJDK repo](https://github.com/openjdk/jdk/commits/master/test/micro) to test your JVM performance.

Change your JMH settings in `build.gradle`. If you are using Java 16, you may copy files from `jmh16/` to `jmh/` to enable Java 16-specific benchmarks.

## Run

**Requires Java 15+**

Simply execute `gradlew jmh`. Result can be found in `build/results/jmh` which can be uploaded to <http://deepoove.com/jmh-visual-chart/> to visualize.


## License

<https://openjdk.java.net/legal/gplv2+ce.html>
