# Service84.IO External Services

## Usage
This is a collection of service definitions for external services.

## Publishing
The OpenAPI specification is published as a jar that only contains the service.yaml file.  The reason I packaged the service.yaml file in a jar is because MavenCentral will only publish things that are in jars, I admit this might be a misuse of MavenCentral, but it is free for OSS.

### Publishing the service.yaml JAR
There is a directory for each service with a build.gradle file and service yaml file. So, from that direcotry just run the gradle publish command, for your local maven repository run the following

    gradle publishToMavenLocal

Note that the provided build files will publish io.service84.openapi.external

Publishing works best with Gradle 6.3.

## Versioning
This project uses the versioning specified by the API.
