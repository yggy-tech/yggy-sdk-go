# QueryProject200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Answer** | **string** | Short extractive answer from the top context. Empty when nothing was retrieved. | 
**Contexts** | [**[]QueryProject200ResponseContextsInner**](QueryProject200ResponseContextsInner.md) |  | 
**Entities** | Pointer to [**[]QueryProject200ResponseEntitiesInner**](QueryProject200ResponseEntitiesInner.md) | Present when include asks for entities or identity | [optional] 
**Triples** | Pointer to [**[]QueryProject200ResponseTriplesInner**](QueryProject200ResponseTriplesInner.md) | Present when include asks for triples | [optional] 
**ArchivedHits** | Pointer to [**[]QueryProject200ResponseArchivedHitsInner**](QueryProject200ResponseArchivedHitsInner.md) | Present when includeArchived was requested on a single project | [optional] 

## Methods

### NewQueryProject200Response

`func NewQueryProject200Response(answer string, contexts []QueryProject200ResponseContextsInner, ) *QueryProject200Response`

NewQueryProject200Response instantiates a new QueryProject200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryProject200ResponseWithDefaults

`func NewQueryProject200ResponseWithDefaults() *QueryProject200Response`

NewQueryProject200ResponseWithDefaults instantiates a new QueryProject200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAnswer

`func (o *QueryProject200Response) GetAnswer() string`

GetAnswer returns the Answer field if non-nil, zero value otherwise.

### GetAnswerOk

`func (o *QueryProject200Response) GetAnswerOk() (*string, bool)`

GetAnswerOk returns a tuple with the Answer field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAnswer

`func (o *QueryProject200Response) SetAnswer(v string)`

SetAnswer sets Answer field to given value.


### GetContexts

`func (o *QueryProject200Response) GetContexts() []QueryProject200ResponseContextsInner`

GetContexts returns the Contexts field if non-nil, zero value otherwise.

### GetContextsOk

`func (o *QueryProject200Response) GetContextsOk() (*[]QueryProject200ResponseContextsInner, bool)`

GetContextsOk returns a tuple with the Contexts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContexts

`func (o *QueryProject200Response) SetContexts(v []QueryProject200ResponseContextsInner)`

SetContexts sets Contexts field to given value.


### GetEntities

`func (o *QueryProject200Response) GetEntities() []QueryProject200ResponseEntitiesInner`

GetEntities returns the Entities field if non-nil, zero value otherwise.

### GetEntitiesOk

`func (o *QueryProject200Response) GetEntitiesOk() (*[]QueryProject200ResponseEntitiesInner, bool)`

GetEntitiesOk returns a tuple with the Entities field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntities

`func (o *QueryProject200Response) SetEntities(v []QueryProject200ResponseEntitiesInner)`

SetEntities sets Entities field to given value.

### HasEntities

`func (o *QueryProject200Response) HasEntities() bool`

HasEntities returns a boolean if a field has been set.

### GetTriples

`func (o *QueryProject200Response) GetTriples() []QueryProject200ResponseTriplesInner`

GetTriples returns the Triples field if non-nil, zero value otherwise.

### GetTriplesOk

`func (o *QueryProject200Response) GetTriplesOk() (*[]QueryProject200ResponseTriplesInner, bool)`

GetTriplesOk returns a tuple with the Triples field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriples

`func (o *QueryProject200Response) SetTriples(v []QueryProject200ResponseTriplesInner)`

SetTriples sets Triples field to given value.

### HasTriples

`func (o *QueryProject200Response) HasTriples() bool`

HasTriples returns a boolean if a field has been set.

### GetArchivedHits

`func (o *QueryProject200Response) GetArchivedHits() []QueryProject200ResponseArchivedHitsInner`

GetArchivedHits returns the ArchivedHits field if non-nil, zero value otherwise.

### GetArchivedHitsOk

`func (o *QueryProject200Response) GetArchivedHitsOk() (*[]QueryProject200ResponseArchivedHitsInner, bool)`

GetArchivedHitsOk returns a tuple with the ArchivedHits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetArchivedHits

`func (o *QueryProject200Response) SetArchivedHits(v []QueryProject200ResponseArchivedHitsInner)`

SetArchivedHits sets ArchivedHits field to given value.

### HasArchivedHits

`func (o *QueryProject200Response) HasArchivedHits() bool`

HasArchivedHits returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


