# Chat200ResponseDataCitationsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DocumentId** | **string** | Document that grounded the answer | 
**Source** | Pointer to **string** | Caller-supplied source id when present | [optional] 
**Snippet** | Pointer to **string** | Evidence text when the tool returned it | [optional] 
**ExternalId** | Pointer to **string** | Your own id for the document, as sent on upload | [optional] 
**OriginSystem** | Pointer to **string** | Business system the data originates from | [optional] 
**WebUrl** | Pointer to **string** | Link to the document in your system | [optional] 
**Metadata** | Pointer to [**map[string]QueryProject200ResponseContextsInnerMetadataValue**](QueryProject200ResponseContextsInnerMetadataValue.md) | Your own key-value pairs, as sent on upload. Imported documents carry fields of their source here. | [optional] 

## Methods

### NewChat200ResponseDataCitationsInner

`func NewChat200ResponseDataCitationsInner(documentId string, ) *Chat200ResponseDataCitationsInner`

NewChat200ResponseDataCitationsInner instantiates a new Chat200ResponseDataCitationsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChat200ResponseDataCitationsInnerWithDefaults

`func NewChat200ResponseDataCitationsInnerWithDefaults() *Chat200ResponseDataCitationsInner`

NewChat200ResponseDataCitationsInnerWithDefaults instantiates a new Chat200ResponseDataCitationsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDocumentId

`func (o *Chat200ResponseDataCitationsInner) GetDocumentId() string`

GetDocumentId returns the DocumentId field if non-nil, zero value otherwise.

### GetDocumentIdOk

`func (o *Chat200ResponseDataCitationsInner) GetDocumentIdOk() (*string, bool)`

GetDocumentIdOk returns a tuple with the DocumentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentId

`func (o *Chat200ResponseDataCitationsInner) SetDocumentId(v string)`

SetDocumentId sets DocumentId field to given value.


### GetSource

`func (o *Chat200ResponseDataCitationsInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *Chat200ResponseDataCitationsInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *Chat200ResponseDataCitationsInner) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *Chat200ResponseDataCitationsInner) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetSnippet

`func (o *Chat200ResponseDataCitationsInner) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *Chat200ResponseDataCitationsInner) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *Chat200ResponseDataCitationsInner) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.

### HasSnippet

`func (o *Chat200ResponseDataCitationsInner) HasSnippet() bool`

HasSnippet returns a boolean if a field has been set.

### GetExternalId

`func (o *Chat200ResponseDataCitationsInner) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *Chat200ResponseDataCitationsInner) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *Chat200ResponseDataCitationsInner) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *Chat200ResponseDataCitationsInner) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### GetOriginSystem

`func (o *Chat200ResponseDataCitationsInner) GetOriginSystem() string`

GetOriginSystem returns the OriginSystem field if non-nil, zero value otherwise.

### GetOriginSystemOk

`func (o *Chat200ResponseDataCitationsInner) GetOriginSystemOk() (*string, bool)`

GetOriginSystemOk returns a tuple with the OriginSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginSystem

`func (o *Chat200ResponseDataCitationsInner) SetOriginSystem(v string)`

SetOriginSystem sets OriginSystem field to given value.

### HasOriginSystem

`func (o *Chat200ResponseDataCitationsInner) HasOriginSystem() bool`

HasOriginSystem returns a boolean if a field has been set.

### GetWebUrl

`func (o *Chat200ResponseDataCitationsInner) GetWebUrl() string`

GetWebUrl returns the WebUrl field if non-nil, zero value otherwise.

### GetWebUrlOk

`func (o *Chat200ResponseDataCitationsInner) GetWebUrlOk() (*string, bool)`

GetWebUrlOk returns a tuple with the WebUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWebUrl

`func (o *Chat200ResponseDataCitationsInner) SetWebUrl(v string)`

SetWebUrl sets WebUrl field to given value.

### HasWebUrl

`func (o *Chat200ResponseDataCitationsInner) HasWebUrl() bool`

HasWebUrl returns a boolean if a field has been set.

### GetMetadata

`func (o *Chat200ResponseDataCitationsInner) GetMetadata() map[string]QueryProject200ResponseContextsInnerMetadataValue`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Chat200ResponseDataCitationsInner) GetMetadataOk() (*map[string]QueryProject200ResponseContextsInnerMetadataValue, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Chat200ResponseDataCitationsInner) SetMetadata(v map[string]QueryProject200ResponseContextsInnerMetadataValue)`

SetMetadata sets Metadata field to given value.

### HasMetadata

`func (o *Chat200ResponseDataCitationsInner) HasMetadata() bool`

HasMetadata returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


