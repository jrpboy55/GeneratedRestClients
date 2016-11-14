# MetricsmvcendpointApi

All URIs are relative to *https://localhost:8080/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**invokeUsingGET20**](MetricsmvcendpointApi.md#invokeUsingGET20) | **GET** /metrics | invoke
[**invokeUsingGET21**](MetricsmvcendpointApi.md#invokeUsingGET21) | **GET** /metrics.json | invoke
[**valueUsingGET1**](MetricsmvcendpointApi.md#valueUsingGET1) | **GET** /metrics/{name} | value


<a name="invokeUsingGET20"></a>
# **invokeUsingGET20**
> Object invokeUsingGET20()

invoke

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.MetricsmvcendpointApi;


MetricsmvcendpointApi apiInstance = new MetricsmvcendpointApi();
try {
    Object result = apiInstance.invokeUsingGET20();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling MetricsmvcendpointApi#invokeUsingGET20");
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

<a name="invokeUsingGET21"></a>
# **invokeUsingGET21**
> Object invokeUsingGET21()

invoke

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.MetricsmvcendpointApi;


MetricsmvcendpointApi apiInstance = new MetricsmvcendpointApi();
try {
    Object result = apiInstance.invokeUsingGET21();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling MetricsmvcendpointApi#invokeUsingGET21");
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

<a name="valueUsingGET1"></a>
# **valueUsingGET1**
> Object valueUsingGET1(name)

value

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.MetricsmvcendpointApi;


MetricsmvcendpointApi apiInstance = new MetricsmvcendpointApi();
String name = "name_example"; // String | name
try {
    Object result = apiInstance.valueUsingGET1(name);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling MetricsmvcendpointApi#valueUsingGET1");
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

