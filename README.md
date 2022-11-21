# AWS SDK Java 2.x S3 example

The reference for this code is from the tutorial:
https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/get-started.html

## Build

```
mvn package
```

## Run

```
mvn exec:java -Dexec.mainClass="com.example.myapp.App"
```

## To set AWS credentials

```
isengard creds
```
The above command outputs the AWS_ACCESS_ID, AWS_SECRET_ACCESS_KEY and AWS_SESSION_TOKEN.
You can set these env variables in the terminal.
