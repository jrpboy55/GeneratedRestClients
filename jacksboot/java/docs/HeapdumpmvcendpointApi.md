# HeapdumpmvcendpointApi

All URIs are relative to *https://localhost:8080/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**invokeUsingGET18**](HeapdumpmvcendpointApi.md#invokeUsingGET18) | **GET** /heapdump | invoke
[**invokeUsingGET19**](HeapdumpmvcendpointApi.md#invokeUsingGET19) | **GET** /heapdump.json | invoke


<a name="invokeUsingGET18"></a>
# **invokeUsingGET18**
> invokeUsingGET18(live)

invoke

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.HeapdumpmvcendpointApi;


HeapdumpmvcendpointApi apiInstance = new HeapdumpmvcendpointApi();
Boolean live = true; // Boolean | live
try {
    apiInstance.invokeUsingGET18(live);
} catch (ApiException e) {
    System.err.println("Exception when calling HeapdumpmvcendpointApi#invokeUsingGET18");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **live** | **Boolean**| live | [optional] [default to true]

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/octet-stream

<a name="invokeUsingGET19"></a>
# **invokeUsingGET19**
> invokeUsingGET19(live)

invoke

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.HeapdumpmvcendpointApi;


HeapdumpmvcendpointApi apiInstance = new HeapdumpmvcendpointApi();
Boolean live = true; // Boolean | live
try {
    apiInstance.invokeUsingGET19(live);
} catch (ApiException e) {
    System.err.println("Exception when calling HeapdumpmvcendpointApi#invokeUsingGET19");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **live** | **Boolean**| live | [optional] [default to true]

### Return type

null (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/octet-stream

