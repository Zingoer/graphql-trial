# GraphQL?!

## Setup
Following the [tutorial](https://medium.com/@aronbalog/spring-boot-kotlin-graphql-mongo-e73f25df6ab9)

Use the docker based mongodb, so start it first!
`docker run --name mongodb --rm -p 27017:27017 -d mongo:latest`

Then start the server with gradle wrapper:
`./gradlew bootRun`
You may notice that the build progress stop at around 80%, that's normal, the server is actually up.