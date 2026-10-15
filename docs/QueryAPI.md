# \QueryAPI

All URIs are relative to *https://api.yggy.tech*

Method | HTTP request | Description
------------- | ------------- | -------------
[**QueryOrganization**](QueryAPI.md#QueryOrganization) | **Post** /api/v1/query | Retrieve ranked documents across the organization
[**QueryProject**](QueryAPI.md#QueryProject) | **Post** /api/v1/projects/{projectId}/query | Retrieve ranked documents for a project



## QueryOrganization

> QueryProject200Response QueryOrganization(ctx).XYggyOrganizationId(xYggyOrganizationId).QueryProjectRequest(queryProjectRequest).Execute()

Retrieve ranked documents across the organization



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/yggy-tech/yggy-sdk-go"
)

func main() {
	xYggyOrganizationId := "xYggyOrganizationId_example" // string |  (optional)
	queryProjectRequest := *openapiclient.NewQueryProjectRequest("Question_example") // QueryProjectRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QueryAPI.QueryOrganization(context.Background()).XYggyOrganizationId(xYggyOrganizationId).QueryProjectRequest(queryProjectRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QueryAPI.QueryOrganization``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `QueryOrganization`: QueryProject200Response
	fmt.Fprintf(os.Stdout, "Response from `QueryAPI.QueryOrganization`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiQueryOrganizationRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **xYggyOrganizationId** | **string** |  | 
 **queryProjectRequest** | [**QueryProjectRequest**](QueryProjectRequest.md) |  | 

### Return type

[**QueryProject200Response**](QueryProject200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## QueryProject

> QueryProject200Response QueryProject(ctx, projectId).XYggyOrganizationId(xYggyOrganizationId).QueryProjectRequest(queryProjectRequest).Execute()

Retrieve ranked documents for a project



### Example

```go
package main

import (
	"context"
	"fmt"
	"os"
	openapiclient "github.com/yggy-tech/yggy-sdk-go"
)

func main() {
	projectId := "projectId_example" // string | 
	xYggyOrganizationId := "xYggyOrganizationId_example" // string |  (optional)
	queryProjectRequest := *openapiclient.NewQueryProjectRequest("Question_example") // QueryProjectRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.QueryAPI.QueryProject(context.Background(), projectId).XYggyOrganizationId(xYggyOrganizationId).QueryProjectRequest(queryProjectRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `QueryAPI.QueryProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `QueryProject`: QueryProject200Response
	fmt.Fprintf(os.Stdout, "Response from `QueryAPI.QueryProject`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiQueryProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xYggyOrganizationId** | **string** |  | 
 **queryProjectRequest** | [**QueryProjectRequest**](QueryProjectRequest.md) |  | 

### Return type

[**QueryProject200Response**](QueryProject200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

