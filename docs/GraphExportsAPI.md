# \GraphExportsAPI

All URIs are relative to *https://api.yggy.tech*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateGraphExport**](GraphExportsAPI.md#CreateGraphExport) | **Post** /api/v1/projects/{projectId}/graph-exports | Start a project graph export
[**DownloadGraphExport**](GraphExportsAPI.md#DownloadGraphExport) | **Get** /api/v1/projects/{projectId}/graph-exports/{exportId}/download | Download a ready project graph export
[**ListGraphExports**](GraphExportsAPI.md#ListGraphExports) | **Get** /api/v1/projects/{projectId}/graph-exports | List project graph exports from the last 7 days



## CreateGraphExport

> ListGraphExports200ResponseExportsInner CreateGraphExport(ctx, projectId).CreateGraphExportRequest(createGraphExportRequest).Execute()

Start a project graph export

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
	createGraphExportRequest := *openapiclient.NewCreateGraphExportRequest("Format_example") // CreateGraphExportRequest | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GraphExportsAPI.CreateGraphExport(context.Background(), projectId).CreateGraphExportRequest(createGraphExportRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GraphExportsAPI.CreateGraphExport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateGraphExport`: ListGraphExports200ResponseExportsInner
	fmt.Fprintf(os.Stdout, "Response from `GraphExportsAPI.CreateGraphExport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiCreateGraphExportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **createGraphExportRequest** | [**CreateGraphExportRequest**](CreateGraphExportRequest.md) |  | 

### Return type

[**ListGraphExports200ResponseExportsInner**](ListGraphExports200ResponseExportsInner.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DownloadGraphExport

> string DownloadGraphExport(ctx, projectId, exportId).Execute()

Download a ready project graph export

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
	exportId := "exportId_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GraphExportsAPI.DownloadGraphExport(context.Background(), projectId, exportId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GraphExportsAPI.DownloadGraphExport``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadGraphExport`: string
	fmt.Fprintf(os.Stdout, "Response from `GraphExportsAPI.DownloadGraphExport`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**exportId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadGraphExportRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

**string**

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/zip, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListGraphExports

> ListGraphExports200Response ListGraphExports(ctx, projectId).Execute()

List project graph exports from the last 7 days

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

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GraphExportsAPI.ListGraphExports(context.Background(), projectId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GraphExportsAPI.ListGraphExports``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListGraphExports`: ListGraphExports200Response
	fmt.Fprintf(os.Stdout, "Response from `GraphExportsAPI.ListGraphExports`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListGraphExportsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


### Return type

[**ListGraphExports200Response**](ListGraphExports200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

