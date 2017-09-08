# wiremock-sample-simulator

## Build

```
mvn clean install
```

## Run

```
mvn jetty:run
```

## Test

Test with [http://localhost:8888/demo](http://localhost:8888/demo) GET request
And need to send header **Content Type: application/json**, ** Authorization: Bearer ... ** 
and ** sample-required-request-header: ... **
