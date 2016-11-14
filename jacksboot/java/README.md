# jackboot_swagger_client

## Requirements

Building the API client library requires [Maven](https://maven.apache.org/) to be installed.

## Installation

To install the API client library to your local Maven repository, simply execute:

```shell
mvn install
```

To deploy it to a remote Maven repository instead, configure the settings of the repository and execute:

```shell
mvn deploy
```

Refer to the [official documentation](https://maven.apache.org/plugins/maven-deploy-plugin/usage.html) for more information.

### Maven users

Add this dependency to your project's POM:

```xml
<dependency>
    <groupId>io.swagger</groupId>
    <artifactId>jackboot_swagger_client</artifactId>
    <version>1.0.0</version>
    <scope>compile</scope>
</dependency>
```

### Gradle users

Add this dependency to your project's build file:

```groovy
compile "io.swagger:jackboot_swagger_client:1.0.0"
```

### Others

At first generate the JAR by executing:

    mvn package

Then manually install the following JARs:

* target/jackboot_swagger_client-1.0.0.jar
* target/lib/*.jar

## Getting Started

Please follow the [installation](#installation) instruction and execute the following Java code:

```java

import io.swagger.client.*;
import io.swagger.client.auth.*;
import io.swagger.client.model.*;
import io.swagger.client.api.BasicerrorcontrollerApi;

import java.io.File;
import java.util.*;

public class BasicerrorcontrollerApiExample {

    public static void main(String[] args) {
        
        BasicerrorcontrollerApi apiInstance = new BasicerrorcontrollerApi();
        try {
            Map<String, Object> result = apiInstance.errorUsingDELETE();
            System.out.println(result);
        } catch (ApiException e) {
            System.err.println("Exception when calling BasicerrorcontrollerApi#errorUsingDELETE");
            e.printStackTrace();
        }
    }
}

```

## Documentation for API Endpoints

All URIs are relative to *https://localhost:8080/*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*BasicerrorcontrollerApi* | [**errorUsingDELETE**](docs/BasicerrorcontrollerApi.md#errorUsingDELETE) | **DELETE** /error | error
*BasicerrorcontrollerApi* | [**errorUsingGET**](docs/BasicerrorcontrollerApi.md#errorUsingGET) | **GET** /error | error
*BasicerrorcontrollerApi* | [**errorUsingHEAD**](docs/BasicerrorcontrollerApi.md#errorUsingHEAD) | **HEAD** /error | error
*BasicerrorcontrollerApi* | [**errorUsingOPTIONS**](docs/BasicerrorcontrollerApi.md#errorUsingOPTIONS) | **OPTIONS** /error | error
*BasicerrorcontrollerApi* | [**errorUsingPATCH**](docs/BasicerrorcontrollerApi.md#errorUsingPATCH) | **PATCH** /error | error
*BasicerrorcontrollerApi* | [**errorUsingPOST**](docs/BasicerrorcontrollerApi.md#errorUsingPOST) | **POST** /error | error
*BasicerrorcontrollerApi* | [**errorUsingPUT**](docs/BasicerrorcontrollerApi.md#errorUsingPUT) | **PUT** /error | error
*EndpointmvcadapterApi* | [**invokeUsingGET**](docs/EndpointmvcadapterApi.md#invokeUsingGET) | **GET** /autoconfig | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET1**](docs/EndpointmvcadapterApi.md#invokeUsingGET1) | **GET** /autoconfig.json | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET10**](docs/EndpointmvcadapterApi.md#invokeUsingGET10) | **GET** /mappings | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET11**](docs/EndpointmvcadapterApi.md#invokeUsingGET11) | **GET** /mappings.json | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET12**](docs/EndpointmvcadapterApi.md#invokeUsingGET12) | **GET** /trace | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET13**](docs/EndpointmvcadapterApi.md#invokeUsingGET13) | **GET** /trace.json | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET2**](docs/EndpointmvcadapterApi.md#invokeUsingGET2) | **GET** /beans | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET3**](docs/EndpointmvcadapterApi.md#invokeUsingGET3) | **GET** /beans.json | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET4**](docs/EndpointmvcadapterApi.md#invokeUsingGET4) | **GET** /configprops | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET5**](docs/EndpointmvcadapterApi.md#invokeUsingGET5) | **GET** /configprops.json | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET6**](docs/EndpointmvcadapterApi.md#invokeUsingGET6) | **GET** /dump | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET7**](docs/EndpointmvcadapterApi.md#invokeUsingGET7) | **GET** /dump.json | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET8**](docs/EndpointmvcadapterApi.md#invokeUsingGET8) | **GET** /info | invoke
*EndpointmvcadapterApi* | [**invokeUsingGET9**](docs/EndpointmvcadapterApi.md#invokeUsingGET9) | **GET** /info.json | invoke
*EnvironmentmvcendpointApi* | [**invokeUsingGET14**](docs/EnvironmentmvcendpointApi.md#invokeUsingGET14) | **GET** /env | invoke
*EnvironmentmvcendpointApi* | [**invokeUsingGET15**](docs/EnvironmentmvcendpointApi.md#invokeUsingGET15) | **GET** /env.json | invoke
*EnvironmentmvcendpointApi* | [**valueUsingGET**](docs/EnvironmentmvcendpointApi.md#valueUsingGET) | **GET** /env/{name} | value
*HealthmvcendpointApi* | [**invokeUsingDELETE**](docs/HealthmvcendpointApi.md#invokeUsingDELETE) | **DELETE** /health | invoke
*HealthmvcendpointApi* | [**invokeUsingDELETE1**](docs/HealthmvcendpointApi.md#invokeUsingDELETE1) | **DELETE** /health.json | invoke
*HealthmvcendpointApi* | [**invokeUsingGET16**](docs/HealthmvcendpointApi.md#invokeUsingGET16) | **GET** /health | invoke
*HealthmvcendpointApi* | [**invokeUsingGET17**](docs/HealthmvcendpointApi.md#invokeUsingGET17) | **GET** /health.json | invoke
*HealthmvcendpointApi* | [**invokeUsingHEAD**](docs/HealthmvcendpointApi.md#invokeUsingHEAD) | **HEAD** /health | invoke
*HealthmvcendpointApi* | [**invokeUsingHEAD1**](docs/HealthmvcendpointApi.md#invokeUsingHEAD1) | **HEAD** /health.json | invoke
*HealthmvcendpointApi* | [**invokeUsingOPTIONS**](docs/HealthmvcendpointApi.md#invokeUsingOPTIONS) | **OPTIONS** /health | invoke
*HealthmvcendpointApi* | [**invokeUsingOPTIONS1**](docs/HealthmvcendpointApi.md#invokeUsingOPTIONS1) | **OPTIONS** /health.json | invoke
*HealthmvcendpointApi* | [**invokeUsingPATCH**](docs/HealthmvcendpointApi.md#invokeUsingPATCH) | **PATCH** /health | invoke
*HealthmvcendpointApi* | [**invokeUsingPATCH1**](docs/HealthmvcendpointApi.md#invokeUsingPATCH1) | **PATCH** /health.json | invoke
*HealthmvcendpointApi* | [**invokeUsingPOST**](docs/HealthmvcendpointApi.md#invokeUsingPOST) | **POST** /health | invoke
*HealthmvcendpointApi* | [**invokeUsingPOST1**](docs/HealthmvcendpointApi.md#invokeUsingPOST1) | **POST** /health.json | invoke
*HealthmvcendpointApi* | [**invokeUsingPUT**](docs/HealthmvcendpointApi.md#invokeUsingPUT) | **PUT** /health | invoke
*HealthmvcendpointApi* | [**invokeUsingPUT1**](docs/HealthmvcendpointApi.md#invokeUsingPUT1) | **PUT** /health.json | invoke
*HeapdumpmvcendpointApi* | [**invokeUsingGET18**](docs/HeapdumpmvcendpointApi.md#invokeUsingGET18) | **GET** /heapdump | invoke
*HeapdumpmvcendpointApi* | [**invokeUsingGET19**](docs/HeapdumpmvcendpointApi.md#invokeUsingGET19) | **GET** /heapdump.json | invoke
*HellocontrollerApi* | [**getUserUsingGET**](docs/HellocontrollerApi.md#getUserUsingGET) | **GET** /user | getUser
*HellocontrollerApi* | [**indexUsingDELETE**](docs/HellocontrollerApi.md#indexUsingDELETE) | **DELETE** /hello | index
*HellocontrollerApi* | [**indexUsingGET**](docs/HellocontrollerApi.md#indexUsingGET) | **GET** /hello | index
*HellocontrollerApi* | [**indexUsingHEAD**](docs/HellocontrollerApi.md#indexUsingHEAD) | **HEAD** /hello | index
*HellocontrollerApi* | [**indexUsingOPTIONS**](docs/HellocontrollerApi.md#indexUsingOPTIONS) | **OPTIONS** /hello | index
*HellocontrollerApi* | [**indexUsingPATCH**](docs/HellocontrollerApi.md#indexUsingPATCH) | **PATCH** /hello | index
*HellocontrollerApi* | [**indexUsingPOST**](docs/HellocontrollerApi.md#indexUsingPOST) | **POST** /hello | index
*HellocontrollerApi* | [**indexUsingPUT**](docs/HellocontrollerApi.md#indexUsingPUT) | **PUT** /hello | index
*MetricsmvcendpointApi* | [**invokeUsingGET20**](docs/MetricsmvcendpointApi.md#invokeUsingGET20) | **GET** /metrics | invoke
*MetricsmvcendpointApi* | [**invokeUsingGET21**](docs/MetricsmvcendpointApi.md#invokeUsingGET21) | **GET** /metrics.json | invoke
*MetricsmvcendpointApi* | [**valueUsingGET1**](docs/MetricsmvcendpointApi.md#valueUsingGET1) | **GET** /metrics/{name} | value


## Documentation for Models

 - [ModelAndView](docs/ModelAndView.md)
 - [User](docs/User.md)
 - [View](docs/View.md)


## Documentation for Authorization

All endpoints do not require authorization.
Authentication schemes defined for the API:

## Recommendation

It's recommended to create an instance of `ApiClient` per thread in a multithreaded environment to avoid any potential issue.

## Author



