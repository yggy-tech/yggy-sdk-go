# EntityRead

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Entity** | [**EntityReadEntity**](EntityReadEntity.md) |  | 
**Projects** | **[]string** | Projects the caller can see that hold a fact or literal about the entity (also on the project route) | 
**Documents** | [**[]EntityReadDocumentsInner**](EntityReadDocumentsInner.md) |  | 
**Truncated** | **bool** | True when a fact or literal list hit the read cap; the read is partial | 

## Methods

### NewEntityRead

`func NewEntityRead(entity EntityReadEntity, projects []string, documents []EntityReadDocumentsInner, truncated bool, ) *EntityRead`

NewEntityRead instantiates a new EntityRead object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntityReadWithDefaults

`func NewEntityReadWithDefaults() *EntityRead`

NewEntityReadWithDefaults instantiates a new EntityRead object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetEntity

`func (o *EntityRead) GetEntity() EntityReadEntity`

GetEntity returns the Entity field if non-nil, zero value otherwise.

### GetEntityOk

`func (o *EntityRead) GetEntityOk() (*EntityReadEntity, bool)`

GetEntityOk returns a tuple with the Entity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntity

`func (o *EntityRead) SetEntity(v EntityReadEntity)`

SetEntity sets Entity field to given value.


### GetProjects

`func (o *EntityRead) GetProjects() []string`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *EntityRead) GetProjectsOk() (*[]string, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *EntityRead) SetProjects(v []string)`

SetProjects sets Projects field to given value.


### GetDocuments

`func (o *EntityRead) GetDocuments() []EntityReadDocumentsInner`

GetDocuments returns the Documents field if non-nil, zero value otherwise.

### GetDocumentsOk

`func (o *EntityRead) GetDocumentsOk() (*[]EntityReadDocumentsInner, bool)`

GetDocumentsOk returns a tuple with the Documents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocuments

`func (o *EntityRead) SetDocuments(v []EntityReadDocumentsInner)`

SetDocuments sets Documents field to given value.


### GetTruncated

`func (o *EntityRead) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *EntityRead) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *EntityRead) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


