# \ChatAPI

All URIs are relative to *https://api.yggy.tech*

Method | HTTP request | Description
------------- | ------------- | -------------
[**Chat**](ChatAPI.md#Chat) | **Post** /api/v1/projects/{projectId}/chat | Chat with Knowledge Graph



## Chat

> Chat200Response Chat(ctx, projectId).ChatRequest(chatRequest).Execute()

Chat with Knowledge Graph



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
	chatRequest := *openapiclient.NewChatRequest("Message_example") // ChatRequest |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.ChatAPI.Chat(context.Background(), projectId).ChatRequest(chatRequest).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `ChatAPI.Chat``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `Chat`: Chat200Response
	fmt.Fprintf(os.Stdout, "Response from `ChatAPI.Chat`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiChatRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **chatRequest** | [**ChatRequest**](ChatRequest.md) |  | 

### Return type

[**Chat200Response**](Chat200Response.md)

### Authorization

[bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

