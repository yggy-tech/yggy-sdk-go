# \DocumentsAPI

All URIs are relative to *https://api.yggy.tech*

Method | HTTP request | Description
------------- | ------------- | -------------
[**DeleteDocument**](DocumentsAPI.md#DeleteDocument) | **Delete** /api/v1/projects/{projectId}/documents/{id} | Delete a document and its extracted triples (project-scoped)
[**DownloadDocument**](DocumentsAPI.md#DownloadDocument) | **Get** /api/v1/projects/{projectId}/documents/{id}/download | Download original document (project-scoped)
[**GetDocument**](DocumentsAPI.md#GetDocument) | **Get** /api/v1/projects/{projectId}/documents/{id} | Get a document by ID (project-scoped)
[**GetDocumentStatus**](DocumentsAPI.md#GetDocumentStatus) | **Get** /api/v1/projects/{projectId}/documents/{id}/status | Get document processing status (project-scoped)
[**ListDocumentTriples**](DocumentsAPI.md#ListDocumentTriples) | **Get** /api/v1/projects/{projectId}/documents/{id}/triples | Get triples extracted from a document (project-scoped)
[**ListDocuments**](DocumentsAPI.md#ListDocuments) | **Get** /api/v1/projects/{projectId}/documents | List documents for a project
[**ReExtractDocument**](DocumentsAPI.md#ReExtractDocument) | **Post** /api/v1/projects/{projectId}/documents/{id}/re-extract | Re-extract triples from a document (project-scoped)
[**RetryDocument**](DocumentsAPI.md#RetryDocument) | **Post** /api/v1/projects/{projectId}/documents/{id}/retry | Retry document processing (project-scoped)
[**StreamDocumentStatus**](DocumentsAPI.md#StreamDocumentStatus) | **Get** /api/v1/projects/{projectId}/documents/{id}/status/stream | Stream document processing status (project-scoped)
[**UploadDocument**](DocumentsAPI.md#UploadDocument) | **Post** /api/v1/projects/{projectId}/documents/upload | Upload and queue a document for async processing (project-scoped)



## DeleteDocument

> DeleteDocument200Response DeleteDocument(ctx, projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()

Delete a document and its extracted triples (project-scoped)



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
	id := "id_example" // string | 
	xYggyOrganizationId := "xYggyOrganizationId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.DeleteDocument(context.Background(), projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.DeleteDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DeleteDocument`: DeleteDocument200Response
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.DeleteDocument`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDeleteDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xYggyOrganizationId** | **string** |  | 

### Return type

[**DeleteDocument200Response**](DeleteDocument200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## DownloadDocument

> string DownloadDocument(ctx, projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()

Download original document (project-scoped)



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
	id := "id_example" // string | 
	xYggyOrganizationId := "xYggyOrganizationId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.DownloadDocument(context.Background(), projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.DownloadDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `DownloadDocument`: string
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.DownloadDocument`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiDownloadDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xYggyOrganizationId** | **string** |  | 

### Return type

**string**

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/octet-stream, application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDocument

> ListDocuments200ResponseDocumentsInner GetDocument(ctx, projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()

Get a document by ID (project-scoped)



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
	id := "id_example" // string | 
	xYggyOrganizationId := "xYggyOrganizationId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.GetDocument(context.Background(), projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.GetDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDocument`: ListDocuments200ResponseDocumentsInner
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.GetDocument`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xYggyOrganizationId** | **string** |  | 

### Return type

[**ListDocuments200ResponseDocumentsInner**](ListDocuments200ResponseDocumentsInner.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## GetDocumentStatus

> GetDocumentStatus200Response GetDocumentStatus(ctx, projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()

Get document processing status (project-scoped)



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
	id := "id_example" // string | 
	xYggyOrganizationId := "xYggyOrganizationId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.GetDocumentStatus(context.Background(), projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.GetDocumentStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `GetDocumentStatus`: GetDocumentStatus200Response
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.GetDocumentStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiGetDocumentStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xYggyOrganizationId** | **string** |  | 

### Return type

[**GetDocumentStatus200Response**](GetDocumentStatus200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDocumentTriples

> ListDocumentTriples200Response ListDocumentTriples(ctx, projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()

Get triples extracted from a document (project-scoped)



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
	id := "id_example" // string | 
	xYggyOrganizationId := "xYggyOrganizationId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.ListDocumentTriples(context.Background(), projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.ListDocumentTriples``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDocumentTriples`: ListDocumentTriples200Response
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.ListDocumentTriples`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListDocumentTriplesRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xYggyOrganizationId** | **string** |  | 

### Return type

[**ListDocumentTriples200Response**](ListDocumentTriples200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ListDocuments

> ListDocuments200Response ListDocuments(ctx, projectId).ProjectId2(projectId2).Status(status).Archived(archived).Limit(limit).Offset(offset).SortBy(sortBy).SortDir(sortDir).Q(q).FolderId(folderId).NoteKind(noteKind).XYggyOrganizationId(xYggyOrganizationId).Execute()

List documents for a project



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
	projectId2 := "projectId_example" // string | Filter documents by project ID. When omitted, returns all of the organization's documents. (optional)
	status := "status_example" // string |  (optional)
	archived := "archived_example" // string | Filter by archive state: false (default) excludes archived, true includes all, only shows archived only (optional) (default to "false")
	limit := float32(8.14) // float32 |  (optional) (default to 20)
	offset := float32(8.14) // float32 |  (optional) (default to 0)
	sortBy := "sortBy_example" // string |  (optional) (default to "createdAt")
	sortDir := "sortDir_example" // string |  (optional) (default to "desc")
	q := "q_example" // string | Case-insensitive substring search over title and source filename/path. (optional)
	folderId := "folderId_example" // string | Browse documents in this folder (externalId). Use the literal value `root` for unfiled documents only. Omit to list all documents (legacy). (optional)
	noteKind := "noteKind_example" // string | When set, only documents of this note kind (capture, daily, or note). (optional)
	xYggyOrganizationId := "xYggyOrganizationId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.ListDocuments(context.Background(), projectId).ProjectId2(projectId2).Status(status).Archived(archived).Limit(limit).Offset(offset).SortBy(sortBy).SortDir(sortDir).Q(q).FolderId(folderId).NoteKind(noteKind).XYggyOrganizationId(xYggyOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.ListDocuments``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ListDocuments`: ListDocuments200Response
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.ListDocuments`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiListDocumentsRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **projectId2** | **string** | Filter documents by project ID. When omitted, returns all of the organization&#39;s documents. | 
 **status** | **string** |  | 
 **archived** | **string** | Filter by archive state: false (default) excludes archived, true includes all, only shows archived only | [default to &quot;false&quot;]
 **limit** | **float32** |  | [default to 20]
 **offset** | **float32** |  | [default to 0]
 **sortBy** | **string** |  | [default to &quot;createdAt&quot;]
 **sortDir** | **string** |  | [default to &quot;desc&quot;]
 **q** | **string** | Case-insensitive substring search over title and source filename/path. | 
 **folderId** | **string** | Browse documents in this folder (externalId). Use the literal value &#x60;root&#x60; for unfiled documents only. Omit to list all documents (legacy). | 
 **noteKind** | **string** | When set, only documents of this note kind (capture, daily, or note). | 
 **xYggyOrganizationId** | **string** |  | 

### Return type

[**ListDocuments200Response**](ListDocuments200Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## ReExtractDocument

> RetryDocument202Response ReExtractDocument(ctx, projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()

Re-extract triples from a document (project-scoped)



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
	id := "id_example" // string | 
	xYggyOrganizationId := "xYggyOrganizationId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.ReExtractDocument(context.Background(), projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.ReExtractDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `ReExtractDocument`: RetryDocument202Response
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.ReExtractDocument`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiReExtractDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xYggyOrganizationId** | **string** |  | 

### Return type

[**RetryDocument202Response**](RetryDocument202Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## RetryDocument

> RetryDocument202Response RetryDocument(ctx, projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()

Retry document processing (project-scoped)



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
	id := "id_example" // string | 
	xYggyOrganizationId := "xYggyOrganizationId_example" // string |  (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.RetryDocument(context.Background(), projectId, id).XYggyOrganizationId(xYggyOrganizationId).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.RetryDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `RetryDocument`: RetryDocument202Response
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.RetryDocument`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiRetryDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------


 **xYggyOrganizationId** | **string** |  | 

### Return type

[**RetryDocument202Response**](RetryDocument202Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## StreamDocumentStatus

> string StreamDocumentStatus(ctx, projectId, id).Execute()

Stream document processing status (project-scoped)



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
	id := "id_example" // string | 

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.StreamDocumentStatus(context.Background(), projectId, id).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.StreamDocumentStatus``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `StreamDocumentStatus`: string
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.StreamDocumentStatus`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 
**id** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiStreamDocumentStatusRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------



### Return type

**string**

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/event-stream

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)


## UploadDocument

> UploadDocument202Response UploadDocument(ctx, projectId).XYggyOrganizationId(xYggyOrganizationId).File(file).Text(text).NoteKind(noteKind).ParentNoteId(parentNoteId).ForLinkId(forLinkId).Title(title).Source(source).OriginSystem(originSystem).ExternalId(externalId).Metadata(metadata).ProjectId2(projectId2).DesiredTier(desiredTier).InferenceMode(inferenceMode).Onboarding(onboarding).Execute()

Upload and queue a document for async processing (project-scoped)



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
	file := os.NewFile(1234, "some_file") // *os.File | The document file to upload. Optional when text is set. (optional)
	text := "text_example" // string | Plain text or markdown body. Used when no file is uploaded: it is processed like an uploaded markdown file. With noteKind it becomes a yggy note instead. (optional)
	noteKind := "noteKind_example" // string | Note kind. When set, the upload is stored on the caller's personal organization. (optional)
	parentNoteId := "parentNoteId_example" // string | yggy notes: attach the file to this note. The file becomes a document of its own that belongs to the note, and needs a file. (optional)
	forLinkId := "forLinkId_example" // string | yggy Notes: the link attachment of the same note this file was uploaded for (its audio, for a transcript). Needs parentNoteId. (optional)
	title := "title_example" // string | Document title (optional)
	source := "source_example" // string | Source identifier (optional)
	originSystem := "originSystem_example" // string | Business system the data originates from (optional)
	externalId := "externalId_example" // string | Your own id for the document. Returned as externalId in query results and chat citations. (optional)
	metadata := "metadata_example" // string | JSON object of your own key-value pairs for the document, for example {\\\"region\\\":\\\"EU\\\",\\\"priority\\\":2}. Values are strings, numbers or booleans; at most 50 keys and 8192 bytes. Returned as metadata in query results and chat citations. (optional)
	projectId2 := "projectId_example" // string | Project ID to bind the document to at upload time (optional)
	desiredTier := "desiredTier_example" // string | Model tier for extraction. Defaults to auto. (optional)
	inferenceMode := "inferenceMode_example" // string | Inference routing for extraction. Defaults to org settings. (optional)
	onboarding := "onboarding_example" // string | First-run onboarding request; the server decides whether the free first batch applies. (optional)

	configuration := openapiclient.NewConfiguration()
	apiClient := openapiclient.NewAPIClient(configuration)
	resp, r, err := apiClient.DocumentsAPI.UploadDocument(context.Background(), projectId).XYggyOrganizationId(xYggyOrganizationId).File(file).Text(text).NoteKind(noteKind).ParentNoteId(parentNoteId).ForLinkId(forLinkId).Title(title).Source(source).OriginSystem(originSystem).ExternalId(externalId).Metadata(metadata).ProjectId2(projectId2).DesiredTier(desiredTier).InferenceMode(inferenceMode).Onboarding(onboarding).Execute()
	if err != nil {
		fmt.Fprintf(os.Stderr, "Error when calling `DocumentsAPI.UploadDocument``: %v\n", err)
		fmt.Fprintf(os.Stderr, "Full HTTP response: %v\n", r)
	}
	// response from `UploadDocument`: UploadDocument202Response
	fmt.Fprintf(os.Stdout, "Response from `DocumentsAPI.UploadDocument`: %v\n", resp)
}
```

### Path Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
**ctx** | **context.Context** | context for authentication, logging, cancellation, deadlines, tracing, etc.
**projectId** | **string** |  | 

### Other Parameters

Other parameters are passed through a pointer to a apiUploadDocumentRequest struct via the builder pattern


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------

 **xYggyOrganizationId** | **string** |  | 
 **file** | ***os.File** | The document file to upload. Optional when text is set. | 
 **text** | **string** | Plain text or markdown body. Used when no file is uploaded: it is processed like an uploaded markdown file. With noteKind it becomes a yggy note instead. | 
 **noteKind** | **string** | Note kind. When set, the upload is stored on the caller&#39;s personal organization. | 
 **parentNoteId** | **string** | yggy notes: attach the file to this note. The file becomes a document of its own that belongs to the note, and needs a file. | 
 **forLinkId** | **string** | yggy Notes: the link attachment of the same note this file was uploaded for (its audio, for a transcript). Needs parentNoteId. | 
 **title** | **string** | Document title | 
 **source** | **string** | Source identifier | 
 **originSystem** | **string** | Business system the data originates from | 
 **externalId** | **string** | Your own id for the document. Returned as externalId in query results and chat citations. | 
 **metadata** | **string** | JSON object of your own key-value pairs for the document, for example {\\\&quot;region\\\&quot;:\\\&quot;EU\\\&quot;,\\\&quot;priority\\\&quot;:2}. Values are strings, numbers or booleans; at most 50 keys and 8192 bytes. Returned as metadata in query results and chat citations. | 
 **projectId2** | **string** | Project ID to bind the document to at upload time | 
 **desiredTier** | **string** | Model tier for extraction. Defaults to auto. | 
 **inferenceMode** | **string** | Inference routing for extraction. Defaults to org settings. | 
 **onboarding** | **string** | First-run onboarding request; the server decides whether the free first batch applies. | 

### Return type

[**UploadDocument202Response**](UploadDocument202Response.md)

### Authorization

[apiKeyAuth](../README.md#apiKeyAuth), [bearerAuth](../README.md#bearerAuth)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints)
[[Back to Model list]](../README.md#documentation-for-models)
[[Back to README]](../README.md)

