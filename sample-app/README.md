# Sample application

This is a super simple JAX-RS RESTEasy Spring Boot application just to exercise RESTEasy Spring Boot starter.<br>

## Starting the application

Run class `com.test.SampleAppApplication` from your IDE, or run the command bellow from the command line.

`mvn spring-boot:run`

## Testing it

Send a **GET** request to the endpoint below.

[http://localhost:8080/sample-app/echo/echo](http://localhost:8080/sample-app/echo/echo)

You should receive a response message with this payload as result:

    {
        "wordId": 1,
        "wordString": "Lua"
    }
