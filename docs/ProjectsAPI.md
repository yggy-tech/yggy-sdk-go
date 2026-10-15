# \ProjectsAPI

All URIs are relative to *https://api.yggy.tech*

Method | HTTP request | Description
------------- | ------------- | -------------
[**CreateProject**](ProjectsAPI.md#CreateProject) | **Post** /api/v1/projects | Create a new project
[**ListProjects**](ProjectsAPI.md#ListProjects) | **Get** /api/v1/projects | List organization projects



## CreateProject

> CreateProject201Response CreateProject(ctx).CreateProjectRequest(createProjectRequest).Execute()

Create a new project



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
	createProjectRequest := *openapiclient.NewCreateProjectRequest("Name_example", "Slug_example") // CreateProjectRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.CreateProject(context.Background()).CreateProjectRequest(createProjectRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.CreateProject``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `CreateProject`: CreateProject201Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.CreateProject`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiCreateProjectRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **createProjectRequest** | [**CreateProjectRequest**](CreateProjectRequest.md) |  | 

### Return type

[**CreateProject201Response**](CreateProject201Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListProjects

> ListProjects200Response ListProjects(ctx).Limit(limit).Offset(offset).Q(q).SortBy(sortBy).SortDir(sortDir).Execute()

List organization projects



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
	limit := int32(56) // int32 | Page size, from 1 to 100. (optional) (default to 20)
	offset := int32(56) // int32 | Zero-based offset for pagination. (optional) (default to 0)
	q := "q_example" // string | Case-insensitive substring search over project name and slug. Omit or leave blank to list every project. (optional)
	sortBy := "sortBy_example" // string | recentlyViewed orders by the caller's last-viewed timestamp (falls back to createdAt desc when no views exist), createdAt orders by creation time, name orders by project name (case-insensitive). (optional) (default to "recentlyViewed")
	sortDir := "sortDir_example" // string |  (optional) (default to "desc")

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ProjectsAPI.ListProjects(context.Background()).Limit(limit).Offset(offset).Q(q).SortBy(sortBy).SortDir(sortDir).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ProjectsAPI.ListProjects``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListProjects`: ListProjects200Response
	fmt.Fprintf(os.Stdout, "Response from `ProjectsAPI.ListProjects`: %v\n", resp)
}
```

### Path Parameters



### Other Parameters

Other parameters are passed through a pointer to a apiListProjectsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **limit** | **int32** | Page size, from 1 to 100. | [default to 20]
 **offset** | **int32** | Zero-based offset for pagination. | [default to 0]
 **q** | **string** | Case-insensitive substring search over project name and slug. Omit or leave blank to list every project. | 
 **sortBy** | **string** | recentlyViewed orders by the caller&#39;s last-viewed timestamp (falls back to createdAt desc when no views exist), createdAt orders by creation time, name orders by project name (case-insensitive). | [default to &quot;recentlyViewed&quot;]
 **sortDir** | **string** |  | [default to &quot;desc&quot;]

### Return type

[**ListProjects200Response**](ListProjects200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

