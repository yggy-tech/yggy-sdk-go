# QueryProject200ResponseTriplesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Subject** | [**QueryProject200ResponseTriplesInnerSubject**](QueryProject200ResponseTriplesInnerSubject.md) |  | 
**Predicate** | [**QueryProject200ResponseTriplesInnerPredicate**](QueryProject200ResponseTriplesInnerPredicate.md) |  | 
**Object** | [**QueryProject200ResponseTriplesInnerObject**](QueryProject200ResponseTriplesInnerObject.md) |  | 
**Evidence** | Pointer to **string** | Source text for the fact, when yggy stored it | [optional] 
**DocumentId** | Pointer to **string** | The returned document the fact was extracted from | [optional] 

## Methods

### NewQueryProject200ResponseTriplesInner

`func NewQueryProject200ResponseTriplesInner(subject QueryProject200ResponseTriplesInnerSubject, predicate QueryProject200ResponseTriplesInnerPredicate, object QueryProject200ResponseTriplesInnerObject, ) *QueryProject200ResponseTriplesInner`

NewQueryProject200ResponseTriplesInner instantiates a new QueryProject200ResponseTriplesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryProject200ResponseTriplesInnerWithDefaults

`func NewQueryProject200ResponseTriplesInnerWithDefaults() *QueryProject200ResponseTriplesInner`

NewQueryProject200ResponseTriplesInnerWithDefaults instantiates a new QueryProject200ResponseTriplesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSubject

`func (o *QueryProject200ResponseTriplesInner) GetSubject() QueryProject200ResponseTriplesInnerSubject`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *QueryProject200ResponseTriplesInner) GetSubjectOk() (*QueryProject200ResponseTriplesInnerSubject, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *QueryProject200ResponseTriplesInner) SetSubject(v QueryProject200ResponseTriplesInnerSubject)`

SetSubject sets Subject field to given value.


### GetPredicate

`func (o *QueryProject200ResponseTriplesInner) GetPredicate() QueryProject200ResponseTriplesInnerPredicate`

GetPredicate returns the Predicate field if non-nil, zero value otherwise.

### GetPredicateOk

`func (o *QueryProject200ResponseTriplesInner) GetPredicateOk() (*QueryProject200ResponseTriplesInnerPredicate, bool)`

GetPredicateOk returns a tuple with the Predicate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPredicate

`func (o *QueryProject200ResponseTriplesInner) SetPredicate(v QueryProject200ResponseTriplesInnerPredicate)`

SetPredicate sets Predicate field to given value.


### GetObject

`func (o *QueryProject200ResponseTriplesInner) GetObject() QueryProject200ResponseTriplesInnerObject`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *QueryProject200ResponseTriplesInner) GetObjectOk() (*QueryProject200ResponseTriplesInnerObject, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *QueryProject200ResponseTriplesInner) SetObject(v QueryProject200ResponseTriplesInnerObject)`

SetObject sets Object field to given value.


### GetEvidence

`func (o *QueryProject200ResponseTriplesInner) GetEvidence() string`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *QueryProject200ResponseTriplesInner) GetEvidenceOk() (*string, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *QueryProject200ResponseTriplesInner) SetEvidence(v string)`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *QueryProject200ResponseTriplesInner) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### GetDocumentId

`func (o *QueryProject200ResponseTriplesInner) GetDocumentId() string`

GetDocumentId returns the DocumentId field if non-nil, zero value otherwise.

### GetDocumentIdOk

`func (o *QueryProject200ResponseTriplesInner) GetDocumentIdOk() (*string, bool)`

GetDocumentIdOk returns a tuple with the DocumentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentId

`func (o *QueryProject200ResponseTriplesInner) SetDocumentId(v string)`

SetDocumentId sets DocumentId field to given value.

### HasDocumentId

`func (o *QueryProject200ResponseTriplesInner) HasDocumentId() bool`

HasDocumentId returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


