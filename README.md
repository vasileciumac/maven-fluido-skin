# Maven Fluido Skin

This is the Git repository for the content of <https://maven.apache.org/>.


## Run Locally

You can run

$ mvn site:run

To run the build of the test cases
$ mvn verify -Prun-its

To run the build of a specific test case
$ mvn verify -Prun-its -Dinvoker.test=mskins-10
```
Test is located in <projectLocation>/maven-fluido-skin/target/it/mskins-10
Open index.html

to run locally and see the website on <http://localhost:8080/>.
