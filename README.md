# java-gradle

Experiment about run grails with `gradlew`

## Run

```
$ docker run --rm -v paht/to/myapp:/app -v /path/to/depscache:/root/.gradle wingyplus:java-gradle bootRun
```

## Test

```
$ docker run --rm -v paht/to/myapp:/app -v /path/to/depscache:/root/.gradle wingyplus:java-gradle test
```