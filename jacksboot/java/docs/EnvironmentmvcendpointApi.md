# EnvironmentmvcendpointApi

All URIs are relative to *https://localhost:8080/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**invokeUsingGET14**](EnvironmentmvcendpointApi.md#invokeUsingGET14) | **GET** /env | invoke
[**invokeUsingGET15**](EnvironmentmvcendpointApi.md#invokeUsingGET15) | **GET** /env.json | invoke
[**valueUsingGET**](EnvironmentmvcendpointApi.md#valueUsingGET) | **GET** /env/{name} | value


<a name="invokeUsingGET14"></a>
# **invokeUsingGET14**
> Object invokeUsingGET14()

invoke

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.EnvironmentmvcendpointApi;


EnvironmentmvcendpointApi apiInstance = new EnvironmentmvcendpointApi();
try {
    Object result = apiInstance.invokeUsingGET14();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling EnvironmentmvcendpointApi#invokeUsingGET14");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

**Object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="invokeUsingGET15"></a>
# **invokeUsingGET15**
> Object invokeUsingGET15()

invoke

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.EnvironmentmvcendpointApi;


EnvironmentmvcendpointApi apiInstance = new EnvironmentmvcendpointApi();
try {
    Object result = apiInstance.invokeUsingGET15();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling EnvironmentmvcendpointApi#invokeUsingGET15");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

**Object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="valueUsingGET"></a>
# **valueUsingGET**
> Object valueUsingGET(name)

value

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.EnvironmentmvcendpointApi;


EnvironmentmvcendpointApi apiInstance = new EnvironmentmvcendpointApi();
String name = "name_example"; // String | name
try {
    Object result = apiInstance.valueUsingGET(name);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling EnvironmentmvcendpointApi#valueUsingGET");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **String**| name |

### Return type

**Object**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

