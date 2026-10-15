# EntityReadDocumentsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DocumentId** | **NullableString** |  | 
**Title** | **NullableString** |  | 
**Facts** | [**[]EntityReadDocumentsInnerFactsInner**](EntityReadDocumentsInnerFactsInner.md) |  | 
**Literals** | [**[]EntityReadDocumentsInnerLiteralsInner**](EntityReadDocumentsInnerLiteralsInner.md) |  | 

## Methods

### NewEntityReadDocumentsInner

`func NewEntityReadDocumentsInner(documentId NullableString, title NullableString, facts []EntityReadDocumentsInnerFactsInner, literals []EntityReadDocumentsInnerLiteralsInner, ) *EntityReadDocumentsInner`

NewEntityReadDocumentsInner instantiates a new EntityReadDocumentsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntityReadDocumentsInnerWithDefaults

`func NewEntityReadDocumentsInnerWithDefaults() *EntityReadDocumentsInner`

NewEntityReadDocumentsInnerWithDefaults instantiates a new EntityReadDocumentsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDocumentId

`func (o *EntityReadDocumentsInner) GetDocumentId() string`

GetDocumentId returns the DocumentId field if non-nil, zero value otherwise.

### GetDocumentIdOk

`func (o *EntityReadDocumentsInner) GetDocumentIdOk() (*string, bool)`

GetDocumentIdOk returns a tuple with the DocumentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentId

`func (o *EntityReadDocumentsInner) SetDocumentId(v string)`

SetDocumentId sets DocumentId field to given value.


### SetDocumentIdNil

`func (o *EntityReadDocumentsInner) SetDocumentIdNil(b bool)`

 SetDocumentIdNil sets the value for DocumentId to be an explicit nil

### UnsetDocumentId
`func (o *EntityReadDocumentsInner) UnsetDocumentId()`

UnsetDocumentId ensures that no value is present for DocumentId, not even an explicit nil
### GetTitle

`func (o *EntityReadDocumentsInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *EntityReadDocumentsInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *EntityReadDocumentsInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### SetTitleNil

`func (o *EntityReadDocumentsInner) SetTitleNil(b bool)`

 SetTitleNil sets the value for Title to be an explicit nil

### UnsetTitle
`func (o *EntityReadDocumentsInner) UnsetTitle()`

UnsetTitle ensures that no value is present for Title, not even an explicit nil
### GetFacts

`func (o *EntityReadDocumentsInner) GetFacts() []EntityReadDocumentsInnerFactsInner`

GetFacts returns the Facts field if non-nil, zero value otherwise.

### GetFactsOk

`func (o *EntityReadDocumentsInner) GetFactsOk() (*[]EntityReadDocumentsInnerFactsInner, bool)`

GetFactsOk returns a tuple with the Facts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFacts

`func (o *EntityReadDocumentsInner) SetFacts(v []EntityReadDocumentsInnerFactsInner)`

SetFacts sets Facts field to given value.


### GetLiterals

`func (o *EntityReadDocumentsInner) GetLiterals() []EntityReadDocumentsInnerLiteralsInner`

GetLiterals returns the Literals field if non-nil, zero value otherwise.

### GetLiteralsOk

`func (o *EntityReadDocumentsInner) GetLiteralsOk() (*[]EntityReadDocumentsInnerLiteralsInner, bool)`

GetLiteralsOk returns a tuple with the Literals field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLiterals

`func (o *EntityReadDocumentsInner) SetLiterals(v []EntityReadDocumentsInnerLiteralsInner)`

SetLiterals sets Literals field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


