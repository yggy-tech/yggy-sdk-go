# QueryProjectRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Question** | **string** | The question in plain language. yggy finds the documents that answer it. | 
**TopK** | Pointer to **int32** | How many documents to return, best first. | [optional] [default to 5]
**Mode** | Pointer to **string** | How documents are found and ranked. &#x60;hybrid&#x60; (default) uses the facts yggy extracted and the document text; &#x60;lexical&#x60; uses the document text only; &#x60;graph&#x60; returns only documents the extracted facts point to. | [optional] [default to "hybrid"]
**Include** | Pointer to **[]string** | Extra knowledge to attach to the answer. &#x60;facts&#x60; (also accepted as &#x60;triples&#x60;) adds the facts extracted from the returned documents; &#x60;entities&#x60; adds the people, organizations and things they mention; &#x60;identity&#x60; adds only entities with an approved identity, such as a register number. | [optional] 
**IncludeArchived** | Pointer to **bool** | Also search archived facts. They are returned in &#x60;archivedHits&#x60; and brought back into the live graph in the background. Project queries only. | [optional] [default to false]

## Methods

### NewQueryProjectRequest

`func NewQueryProjectRequest(question string, ) *QueryProjectRequest`

NewQueryProjectRequest instantiates a new QueryProjectRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryProjectRequestWithDefaults

`func NewQueryProjectRequestWithDefaults() *QueryProjectRequest`

NewQueryProjectRequestWithDefaults instantiates a new QueryProjectRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetQuestion

`func (o *QueryProjectRequest) GetQuestion() string`

GetQuestion returns the Question field if non-nil, zero value otherwise.

### GetQuestionOk

`func (o *QueryProjectRequest) GetQuestionOk() (*string, bool)`

GetQuestionOk returns a tuple with the Question field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQuestion

`func (o *QueryProjectRequest) SetQuestion(v string)`

SetQuestion sets Question field to given value.


### GetTopK

`func (o *QueryProjectRequest) GetTopK() int32`

GetTopK returns the TopK field if non-nil, zero value otherwise.

### GetTopKOk

`func (o *QueryProjectRequest) GetTopKOk() (*int32, bool)`

GetTopKOk returns a tuple with the TopK field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTopK

`func (o *QueryProjectRequest) SetTopK(v int32)`

SetTopK sets TopK field to given value.

### HasTopK

`func (o *QueryProjectRequest) HasTopK() bool`

HasTopK returns a boolean if a field has been set.

### GetMode

`func (o *QueryProjectRequest) GetMode() string`

GetMode returns the Mode field if non-nil, zero value otherwise.

### GetModeOk

`func (o *QueryProjectRequest) GetModeOk() (*string, bool)`

GetModeOk returns a tuple with the Mode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMode

`func (o *QueryProjectRequest) SetMode(v string)`

SetMode sets Mode field to given value.

### HasMode

`func (o *QueryProjectRequest) HasMode() bool`

HasMode returns a boolean if a field has been set.

### GetInclude

`func (o *QueryProjectRequest) GetInclude() []string`

GetInclude returns the Include field if non-nil, zero value otherwise.

### GetIncludeOk

`func (o *QueryProjectRequest) GetIncludeOk() (*[]string, bool)`

GetIncludeOk returns a tuple with the Include field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInclude

`func (o *QueryProjectRequest) SetInclude(v []string)`

SetInclude sets Include field to given value.

### HasInclude

`func (o *QueryProjectRequest) HasInclude() bool`

HasInclude returns a boolean if a field has been set.

### GetIncludeArchived

`func (o *QueryProjectRequest) GetIncludeArchived() bool`

GetIncludeArchived returns the IncludeArchived field if non-nil, zero value otherwise.

### GetIncludeArchivedOk

`func (o *QueryProjectRequest) GetIncludeArchivedOk() (*bool, bool)`

GetIncludeArchivedOk returns a tuple with the IncludeArchived field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIncludeArchived

`func (o *QueryProjectRequest) SetIncludeArchived(v bool)`

SetIncludeArchived sets IncludeArchived field to given value.

### HasIncludeArchived

`func (o *QueryProjectRequest) HasIncludeArchived() bool`

HasIncludeArchived returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


