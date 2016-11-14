# HellocontrollerApi

All URIs are relative to *https://localhost:8080/*

Method | HTTP request | Description
------------- | ------------- | -------------
[**getDateUsingGET**](HellocontrollerApi.md#getDateUsingGET) | **GET** /dateRange | getDate
[**getUserUsingGET**](HellocontrollerApi.md#getUserUsingGET) | **GET** /user | getUser
[**indexUsingGET**](HellocontrollerApi.md#indexUsingGET) | **GET** /hello | index
[**postDateUsingPOST**](HellocontrollerApi.md#postDateUsingPOST) | **POST** /dateRange | postDate


<a name="getDateUsingGET"></a>
# **getDateUsingGET**
> DateRange getDateUsingGET()

getDate

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.HellocontrollerApi;


HellocontrollerApi apiInstance = new HellocontrollerApi();
try {
    DateRange result = apiInstance.getDateUsingGET();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling HellocontrollerApi#getDateUsingGET");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**DateRange**](DateRange.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="getUserUsingGET"></a>
# **getUserUsingGET**
> User getUserUsingGET()

getUser

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.HellocontrollerApi;


HellocontrollerApi apiInstance = new HellocontrollerApi();
try {
    User result = apiInstance.getUserUsingGET();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling HellocontrollerApi#getUserUsingGET");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**User**](User.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="indexUsingGET"></a>
# **indexUsingGET**
> String indexUsingGET()

index

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.HellocontrollerApi;


HellocontrollerApi apiInstance = new HellocontrollerApi();
try {
    String result = apiInstance.indexUsingGET();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling HellocontrollerApi#indexUsingGET");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

<a name="postDateUsingPOST"></a>
# **postDateUsingPOST**
> DateRange postDateUsingPOST(newDateRange)

postDate

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.HellocontrollerApi;


HellocontrollerApi apiInstance = new HellocontrollerApi();
DateRange newDateRange = new DateRange(); // DateRange | newDateRange
try {
    DateRange result = apiInstance.postDateUsingPOST(newDateRange);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling HellocontrollerApi#postDateUsingPOST");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **newDateRange** | [**DateRange**](DateRange.md)| newDateRange |

### Return type

[**DateRange**](DateRange.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

