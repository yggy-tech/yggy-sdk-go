# QueryProject200ResponseContextsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** | Stable context id: source slug when present, otherwise the document id | 
**DocumentId** | **string** | Document id | 
**Source** | Pointer to **string** | Caller-supplied source id when the document has one | [optional] 
**Title** | **string** | Document title | 
**Snippet** | **string** | Short passage used for ranking | 
**Score** | **float32** | Relative rank from 0 to 1 inside this result set | 

## Methods

### NewQueryProject200ResponseContextsInner

`func NewQueryProject200ResponseContextsInner(id string, documentId string, title string, snippet string, score float32, ) *QueryProject200ResponseContextsInner`

NewQueryProject200ResponseContextsInner instantiates a new QueryProject200ResponseContextsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryProject200ResponseContextsInnerWithDefaults

`func NewQueryProject200ResponseContextsInnerWithDefaults() *QueryProject200ResponseContextsInner`

NewQueryProject200ResponseContextsInnerWithDefaults instantiates a new QueryProject200ResponseContextsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *QueryProject200ResponseContextsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *QueryProject200ResponseContextsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *QueryProject200ResponseContextsInner) SetId(v string)`

SetId sets Id field to given value.


### GetDocumentId

`func (o *QueryProject200ResponseContextsInner) GetDocumentId() string`

GetDocumentId returns the DocumentId field if non-nil, zero value otherwise.

### GetDocumentIdOk

`func (o *QueryProject200ResponseContextsInner) GetDocumentIdOk() (*string, bool)`

GetDocumentIdOk returns a tuple with the DocumentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentId

`func (o *QueryProject200ResponseContextsInner) SetDocumentId(v string)`

SetDocumentId sets DocumentId field to given value.


### GetSource

`func (o *QueryProject200ResponseContextsInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *QueryProject200ResponseContextsInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *QueryProject200ResponseContextsInner) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *QueryProject200ResponseContextsInner) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetTitle

`func (o *QueryProject200ResponseContextsInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *QueryProject200ResponseContextsInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *QueryProject200ResponseContextsInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetSnippet

`func (o *QueryProject200ResponseContextsInner) GetSnippet() string`

GetSnippet returns the Snippet field if non-nil, zero value otherwise.

### GetSnippetOk

`func (o *QueryProject200ResponseContextsInner) GetSnippetOk() (*string, bool)`

GetSnippetOk returns a tuple with the Snippet field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSnippet

`func (o *QueryProject200ResponseContextsInner) SetSnippet(v string)`

SetSnippet sets Snippet field to given value.


### GetScore

`func (o *QueryProject200ResponseContextsInner) GetScore() float32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *QueryProject200ResponseContextsInner) GetScoreOk() (*float32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *QueryProject200ResponseContextsInner) SetScore(v float32)`

SetScore sets Score field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


