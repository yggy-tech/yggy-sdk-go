# \GraphAPI

All URIs are relative to *https://api.yggy.tech*

Method | HTTP request | Description
------------- | ------------- | -------------
[**GetEntityByIdentity**](GraphAPI.md#GetEntityByIdentity) | **Get** /api/v1/projects/{projectId}/graph/entities/by-identity | Read an organization entity and this project&#39;s facts about it



## GetEntityByIdentity

> EntityRead GetEntityByIdentity(ctx, projectId).Uri(uri).Execute()

Read an organization entity and this project's facts about it

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
	uri := "uri_example" // string | Stable identity URI of the organization entity

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.GraphAPI.GetEntityByIdentity(context.Background(), projectId).Uri(uri).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `GraphAPI.GetEntityByIdentity``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetEntityByIdentity`: EntityRead
	fmt.Fprintf(os.Stdout, "Response from `GraphAPI.GetEntityByIdentity`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetEntityByIdentityRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **uri** | **string** | Stable identity URI of the organization entity | 

### Return type

[**EntityRead**](EntityRead.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

