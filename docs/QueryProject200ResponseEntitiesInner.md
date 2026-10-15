# QueryProject200ResponseEntitiesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Uri** | Pointer to **string** | Public entity URI. Never a graph uid. | [optional] 
**Label** | **string** |  | 
**Type** | Pointer to **string** | Public class URI | [optional] 
**Score** | **float32** |  | 
**DocumentIds** | **[]string** | Ranked context document ids this entity matched | 
**Identity** | Pointer to [**QueryProject200ResponseEntitiesInnerIdentity**](QueryProject200ResponseEntitiesInnerIdentity.md) |  | [optional] 

## Methods

### NewQueryProject200ResponseEntitiesInner

`func NewQueryProject200ResponseEntitiesInner(label string, score float32, documentIds []string, ) *QueryProject200ResponseEntitiesInner`

NewQueryProject200ResponseEntitiesInner instantiates a new QueryProject200ResponseEntitiesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryProject200ResponseEntitiesInnerWithDefaults

`func NewQueryProject200ResponseEntitiesInnerWithDefaults() *QueryProject200ResponseEntitiesInner`

NewQueryProject200ResponseEntitiesInnerWithDefaults instantiates a new QueryProject200ResponseEntitiesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetUri

`func (o *QueryProject200ResponseEntitiesInner) GetUri() string`

GetUri returns the Uri field if non-nil, zero value otherwise.

### GetUriOk

`func (o *QueryProject200ResponseEntitiesInner) GetUriOk() (*string, bool)`

GetUriOk returns a tuple with the Uri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUri

`func (o *QueryProject200ResponseEntitiesInner) SetUri(v string)`

SetUri sets Uri field to given value.

### HasUri

`func (o *QueryProject200ResponseEntitiesInner) HasUri() bool`

HasUri returns a boolean if a field has been set.

### GetLabel

`func (o *QueryProject200ResponseEntitiesInner) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *QueryProject200ResponseEntitiesInner) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *QueryProject200ResponseEntitiesInner) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetType

`func (o *QueryProject200ResponseEntitiesInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *QueryProject200ResponseEntitiesInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *QueryProject200ResponseEntitiesInner) SetType(v string)`

SetType sets Type field to given value.

### HasType

`func (o *QueryProject200ResponseEntitiesInner) HasType() bool`

HasType returns a boolean if a field has been set.

### GetScore

`func (o *QueryProject200ResponseEntitiesInner) GetScore() float32`

GetScore returns the Score field if non-nil, zero value otherwise.

### GetScoreOk

`func (o *QueryProject200ResponseEntitiesInner) GetScoreOk() (*float32, bool)`

GetScoreOk returns a tuple with the Score field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScore

`func (o *QueryProject200ResponseEntitiesInner) SetScore(v float32)`

SetScore sets Score field to given value.


### GetDocumentIds

`func (o *QueryProject200ResponseEntitiesInner) GetDocumentIds() []string`

GetDocumentIds returns the DocumentIds field if non-nil, zero value otherwise.

### GetDocumentIdsOk

`func (o *QueryProject200ResponseEntitiesInner) GetDocumentIdsOk() (*[]string, bool)`

GetDocumentIdsOk returns a tuple with the DocumentIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentIds

`func (o *QueryProject200ResponseEntitiesInner) SetDocumentIds(v []string)`

SetDocumentIds sets DocumentIds field to given value.


### GetIdentity

`func (o *QueryProject200ResponseEntitiesInner) GetIdentity() QueryProject200ResponseEntitiesInnerIdentity`

GetIdentity returns the Identity field if non-nil, zero value otherwise.

### GetIdentityOk

`func (o *QueryProject200ResponseEntitiesInner) GetIdentityOk() (*QueryProject200ResponseEntitiesInnerIdentity, bool)`

GetIdentityOk returns a tuple with the Identity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentity

`func (o *QueryProject200ResponseEntitiesInner) SetIdentity(v QueryProject200ResponseEntitiesInnerIdentity)`

SetIdentity sets Identity field to given value.

### HasIdentity

`func (o *QueryProject200ResponseEntitiesInner) HasIdentity() bool`

HasIdentity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


