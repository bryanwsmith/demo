## Micronaut 4.2.0 Documentation

- [User Guide](https://docs.micronaut.io/4.2.0/guide/index.html)
- [API Reference](https://docs.micronaut.io/4.2.0/api/index.html)
- [Configuration Reference](https://docs.micronaut.io/4.2.0/guide/configurationreference.html)
- [Micronaut Guides](https://guides.micronaut.io/index.html)
---

## Handler

Handler: io.micronaut.function.aws.proxy.payload1.ApiGatewayProxyRequestEventFunction

[AWS Lambda Handler](https://docs.aws.amazon.com/lambda/latest/dg/java-handler.html)

## Requisites

- [AWS Account](https://aws.amazon.com/free/)
- [CDK CLI](https://docs.aws.amazon.com/cdk/v2/guide/cli.html)
- [AWS CLI](https://aws.amazon.com/cli/)

## How to deploy

### Generate the deployable artifact

```
./gradlew :app:optimizedJitJarAll
./gradlew test
```

### Deploy

The `infra/cdk.json` file tells the CDK Toolkit how to execute your app.

`cd infra`
`cdk synth` - emits the synthesized CloudFormation template
`cdk deploy` - deploy this stack to your default AWS account/region
`cd ..`

Other useful commands:

`cdk diff` - compare deployed stack with current state
`cdk docs`- open CDK documentation

### Cleanup

```
cd infra
cdk destroy
cd ..
```


- [Shadow Gradle Plugin](https://plugins.gradle.org/plugin/com.github.johnrengelman.shadow)
- [Micronaut Gradle Plugin documentation](https://micronaut-projects.github.io/micronaut-gradle-plugin/latest/)
- [GraalVM Gradle Plugin documentation](https://graalvm.github.io/native-build-tools/latest/gradle-plugin.html)
## Feature lombok documentation

- [Micronaut Project Lombok documentation](https://docs.micronaut.io/latest/guide/index.html#lombok)

- [https://projectlombok.org/features/all](https://projectlombok.org/features/all)


## Feature assertj documentation

- [https://assertj.github.io/doc/](https://assertj.github.io/doc/)


## Feature dynamodb documentation

- [Micronaut Amazon DynamoDB documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/#dynamodb)

- [https://aws.amazon.com/dynamodb/](https://aws.amazon.com/dynamodb/)


## Feature aws-secrets-manager documentation

- [Micronaut AWS Secrets Manager documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/#distributedconfigurationsecretsmanager)

- [https://aws.amazon.com/secrets-manager/](https://aws.amazon.com/secrets-manager/)


## Feature micronaut-aot documentation

- [Micronaut AOT documentation](https://micronaut-projects.github.io/micronaut-aot/latest/guide/)


## Feature aws-lambda-events-serde documentation

- [Micronaut AWS Lambda Events Serde documentation](https://micronaut-projects.github.io/micronaut-aws/snapshot/guide/#eventsLambdaSerde)

- [https://github.com/aws/aws-lambda-java-libs/tree/main/aws-lambda-java-events](https://github.com/aws/aws-lambda-java-libs/tree/main/aws-lambda-java-events)


## Feature swagger-ui documentation

- [Micronaut Swagger UI documentation](https://micronaut-projects.github.io/micronaut-openapi/latest/guide/index.html)

- [https://swagger.io/tools/swagger-ui/](https://swagger.io/tools/swagger-ui/)


## Feature aws-cdk documentation

- [https://docs.aws.amazon.com/cdk/v2/guide/home.html](https://docs.aws.amazon.com/cdk/v2/guide/home.html)


## Feature mockito documentation

- [https://site.mockito.org](https://site.mockito.org)


## Feature serialization-jackson documentation

- [Micronaut Serialization Jackson Core documentation](https://micronaut-projects.github.io/micronaut-serialization/latest/guide/)


## Feature snapstart documentation

- [https://docs.aws.amazon.com/lambda/latest/dg/snapstart.html](https://docs.aws.amazon.com/lambda/latest/dg/snapstart.html)


## Feature openapi documentation

- [Micronaut OpenAPI Support documentation](https://micronaut-projects.github.io/micronaut-openapi/latest/guide/index.html)

- [https://www.openapis.org](https://www.openapis.org)


## Feature validation documentation

- [Micronaut Validation documentation](https://micronaut-projects.github.io/micronaut-validation/latest/guide/)


## Feature aws-parameter-store documentation

- [Micronaut AWS Parameter Store Distributed Configuration documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/index.html#parametersStore)

- [https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html)


## Feature mockserver-client-java documentation

- [https://www.mock-server.com/mock_server/mockserver_clients.html#java-mockserver-client](https://www.mock-server.com/mock_server/mockserver_clients.html#java-mockserver-client)


## Feature amazon-api-gateway documentation

- [Micronaut Amazon API Gateway REST API documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/index.html#amazonApiGateway)

- [https://docs.aws.amazon.com/apigateway/](https://docs.aws.amazon.com/apigateway/)


## Feature aws-lambda documentation

- [Micronaut AWS Lambda Function documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/index.html#lambda)


## Feature aws-v2-sdk documentation

- [Micronaut AWS SDK 2.x documentation](https://micronaut-projects.github.io/micronaut-aws/latest/guide/)

- [https://docs.aws.amazon.com/sdk-for-java/v2/developer-guide/welcome.html](https://docs.aws.amazon.com/sdk-for-java/v2/developer-guide/welcome.html)


## Feature hamcrest documentation

- [https://hamcrest.org/JavaHamcrest/](https://hamcrest.org/JavaHamcrest/)


