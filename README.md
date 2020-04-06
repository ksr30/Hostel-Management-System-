
# Hostel Mangement System

![DAML-Use-Case-Page-1](https://user-images.githubusercontent.com/40355376/78546533-35c87080-781b-11ea-9a3c-e4b82e12d637.jpg)

# Overview



## Compile
Create dar file using
```bash
daml build
```
Generate scala code of templates using
```bash
daml codegen scala
```
Finally start the sandbox with the dar file created at first step
```bash
daml sandbox ./.daml/dist/quickstart-0.0.1.dar
```
Open another terminal and run the application using
```bash
sbt “application/runMain com.knoldus.Operation localhost 6865”
```

## Scenario execution
Run test scenarios using 
```bash
daml damlc -- test --files MainTest.daml
```

