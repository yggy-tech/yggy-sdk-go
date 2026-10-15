# Chat200ResponseDataCitationsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DocumentId** | **string** | Document that grounded the answer | 
**Source** | Pointer to **string** | Caller-supplied source id when present | [optional] 
**Snippet** | Pointer to **string** | Evidence text when the tool returned it | [optional] 

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


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


