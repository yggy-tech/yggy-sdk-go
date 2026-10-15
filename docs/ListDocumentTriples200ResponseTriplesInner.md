# ListDocumentTriples200ResponseTriplesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Subject** | **string** |  | 
**Predicate** | **string** |  | 
**Object** | **string** |  | 
**SubjectIdentity** | Pointer to [**ListDocumentTriples200ResponseTriplesInnerSubjectIdentity**](ListDocumentTriples200ResponseTriplesInnerSubjectIdentity.md) |  | [optional] 
**SubjectId** | Pointer to **string** |  | [optional] 
**SubjectType** | Pointer to **string** |  | [optional] 
**SubjectIdentityUri** | Pointer to **string** |  | [optional] 
**ObjectId** | Pointer to **string** |  | [optional] 
**ObjectType** | Pointer to **string** |  | [optional] 
**ObjectIdentityUri** | Pointer to **string** |  | [optional] 
**Qualifiers** | Pointer to [**ListDocumentTriples200ResponseTriplesInnerQualifiers**](ListDocumentTriples200ResponseTriplesInnerQualifiers.md) |  | [optional] 
**Source** | Pointer to **string** |  | [optional] 
**ExtractionMethod** | Pointer to **string** |  | [optional] 
**Evidence** | Pointer to **[]string** |  | [optional] 
**EvidenceRegionId** | Pointer to **string** |  | [optional] 
**Note** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 

## Methods

### NewListDocumentTriples200ResponseTriplesInner

`func NewListDocumentTriples200ResponseTriplesInner(subject string, predicate string, object string, ) *ListDocumentTriples200ResponseTriplesInner`

NewListDocumentTriples200ResponseTriplesInner instantiates a new ListDocumentTriples200ResponseTriplesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListDocumentTriples200ResponseTriplesInnerWithDefaults

`func NewListDocumentTriples200ResponseTriplesInnerWithDefaults() *ListDocumentTriples200ResponseTriplesInner`

NewListDocumentTriples200ResponseTriplesInnerWithDefaults instantiates a new ListDocumentTriples200ResponseTriplesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListDocumentTriples200ResponseTriplesInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListDocumentTriples200ResponseTriplesInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ListDocumentTriples200ResponseTriplesInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetSubject

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSubject() string`

GetSubject returns the Subject field if non-nil, zero value otherwise.

### GetSubjectOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSubjectOk() (*string, bool)`

GetSubjectOk returns a tuple with the Subject field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubject

`func (o *ListDocumentTriples200ResponseTriplesInner) SetSubject(v string)`

SetSubject sets Subject field to given value.


### GetPredicate

`func (o *ListDocumentTriples200ResponseTriplesInner) GetPredicate() string`

GetPredicate returns the Predicate field if non-nil, zero value otherwise.

### GetPredicateOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetPredicateOk() (*string, bool)`

GetPredicateOk returns a tuple with the Predicate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPredicate

`func (o *ListDocumentTriples200ResponseTriplesInner) SetPredicate(v string)`

SetPredicate sets Predicate field to given value.


### GetObject

`func (o *ListDocumentTriples200ResponseTriplesInner) GetObject() string`

GetObject returns the Object field if non-nil, zero value otherwise.

### GetObjectOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetObjectOk() (*string, bool)`

GetObjectOk returns a tuple with the Object field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObject

`func (o *ListDocumentTriples200ResponseTriplesInner) SetObject(v string)`

SetObject sets Object field to given value.


### GetSubjectIdentity

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSubjectIdentity() ListDocumentTriples200ResponseTriplesInnerSubjectIdentity`

GetSubjectIdentity returns the SubjectIdentity field if non-nil, zero value otherwise.

### GetSubjectIdentityOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSubjectIdentityOk() (*ListDocumentTriples200ResponseTriplesInnerSubjectIdentity, bool)`

GetSubjectIdentityOk returns a tuple with the SubjectIdentity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectIdentity

`func (o *ListDocumentTriples200ResponseTriplesInner) SetSubjectIdentity(v ListDocumentTriples200ResponseTriplesInnerSubjectIdentity)`

SetSubjectIdentity sets SubjectIdentity field to given value.

### HasSubjectIdentity

`func (o *ListDocumentTriples200ResponseTriplesInner) HasSubjectIdentity() bool`

HasSubjectIdentity returns a boolean if a field has been set.

### GetSubjectId

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSubjectId() string`

GetSubjectId returns the SubjectId field if non-nil, zero value otherwise.

### GetSubjectIdOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSubjectIdOk() (*string, bool)`

GetSubjectIdOk returns a tuple with the SubjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectId

`func (o *ListDocumentTriples200ResponseTriplesInner) SetSubjectId(v string)`

SetSubjectId sets SubjectId field to given value.

### HasSubjectId

`func (o *ListDocumentTriples200ResponseTriplesInner) HasSubjectId() bool`

HasSubjectId returns a boolean if a field has been set.

### GetSubjectType

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSubjectType() string`

GetSubjectType returns the SubjectType field if non-nil, zero value otherwise.

### GetSubjectTypeOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSubjectTypeOk() (*string, bool)`

GetSubjectTypeOk returns a tuple with the SubjectType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectType

`func (o *ListDocumentTriples200ResponseTriplesInner) SetSubjectType(v string)`

SetSubjectType sets SubjectType field to given value.

### HasSubjectType

`func (o *ListDocumentTriples200ResponseTriplesInner) HasSubjectType() bool`

HasSubjectType returns a boolean if a field has been set.

### GetSubjectIdentityUri

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSubjectIdentityUri() string`

GetSubjectIdentityUri returns the SubjectIdentityUri field if non-nil, zero value otherwise.

### GetSubjectIdentityUriOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSubjectIdentityUriOk() (*string, bool)`

GetSubjectIdentityUriOk returns a tuple with the SubjectIdentityUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubjectIdentityUri

`func (o *ListDocumentTriples200ResponseTriplesInner) SetSubjectIdentityUri(v string)`

SetSubjectIdentityUri sets SubjectIdentityUri field to given value.

### HasSubjectIdentityUri

`func (o *ListDocumentTriples200ResponseTriplesInner) HasSubjectIdentityUri() bool`

HasSubjectIdentityUri returns a boolean if a field has been set.

### GetObjectId

`func (o *ListDocumentTriples200ResponseTriplesInner) GetObjectId() string`

GetObjectId returns the ObjectId field if non-nil, zero value otherwise.

### GetObjectIdOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetObjectIdOk() (*string, bool)`

GetObjectIdOk returns a tuple with the ObjectId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectId

`func (o *ListDocumentTriples200ResponseTriplesInner) SetObjectId(v string)`

SetObjectId sets ObjectId field to given value.

### HasObjectId

`func (o *ListDocumentTriples200ResponseTriplesInner) HasObjectId() bool`

HasObjectId returns a boolean if a field has been set.

### GetObjectType

`func (o *ListDocumentTriples200ResponseTriplesInner) GetObjectType() string`

GetObjectType returns the ObjectType field if non-nil, zero value otherwise.

### GetObjectTypeOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetObjectTypeOk() (*string, bool)`

GetObjectTypeOk returns a tuple with the ObjectType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectType

`func (o *ListDocumentTriples200ResponseTriplesInner) SetObjectType(v string)`

SetObjectType sets ObjectType field to given value.

### HasObjectType

`func (o *ListDocumentTriples200ResponseTriplesInner) HasObjectType() bool`

HasObjectType returns a boolean if a field has been set.

### GetObjectIdentityUri

`func (o *ListDocumentTriples200ResponseTriplesInner) GetObjectIdentityUri() string`

GetObjectIdentityUri returns the ObjectIdentityUri field if non-nil, zero value otherwise.

### GetObjectIdentityUriOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetObjectIdentityUriOk() (*string, bool)`

GetObjectIdentityUriOk returns a tuple with the ObjectIdentityUri field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetObjectIdentityUri

`func (o *ListDocumentTriples200ResponseTriplesInner) SetObjectIdentityUri(v string)`

SetObjectIdentityUri sets ObjectIdentityUri field to given value.

### HasObjectIdentityUri

`func (o *ListDocumentTriples200ResponseTriplesInner) HasObjectIdentityUri() bool`

HasObjectIdentityUri returns a boolean if a field has been set.

### GetQualifiers

`func (o *ListDocumentTriples200ResponseTriplesInner) GetQualifiers() ListDocumentTriples200ResponseTriplesInnerQualifiers`

GetQualifiers returns the Qualifiers field if non-nil, zero value otherwise.

### GetQualifiersOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetQualifiersOk() (*ListDocumentTriples200ResponseTriplesInnerQualifiers, bool)`

GetQualifiersOk returns a tuple with the Qualifiers field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQualifiers

`func (o *ListDocumentTriples200ResponseTriplesInner) SetQualifiers(v ListDocumentTriples200ResponseTriplesInnerQualifiers)`

SetQualifiers sets Qualifiers field to given value.

### HasQualifiers

`func (o *ListDocumentTriples200ResponseTriplesInner) HasQualifiers() bool`

HasQualifiers returns a boolean if a field has been set.

### GetSource

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ListDocumentTriples200ResponseTriplesInner) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *ListDocumentTriples200ResponseTriplesInner) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetExtractionMethod

`func (o *ListDocumentTriples200ResponseTriplesInner) GetExtractionMethod() string`

GetExtractionMethod returns the ExtractionMethod field if non-nil, zero value otherwise.

### GetExtractionMethodOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetExtractionMethodOk() (*string, bool)`

GetExtractionMethodOk returns a tuple with the ExtractionMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionMethod

`func (o *ListDocumentTriples200ResponseTriplesInner) SetExtractionMethod(v string)`

SetExtractionMethod sets ExtractionMethod field to given value.

### HasExtractionMethod

`func (o *ListDocumentTriples200ResponseTriplesInner) HasExtractionMethod() bool`

HasExtractionMethod returns a boolean if a field has been set.

### GetEvidence

`func (o *ListDocumentTriples200ResponseTriplesInner) GetEvidence() []string`

GetEvidence returns the Evidence field if non-nil, zero value otherwise.

### GetEvidenceOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetEvidenceOk() (*[]string, bool)`

GetEvidenceOk returns a tuple with the Evidence field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidence

`func (o *ListDocumentTriples200ResponseTriplesInner) SetEvidence(v []string)`

SetEvidence sets Evidence field to given value.

### HasEvidence

`func (o *ListDocumentTriples200ResponseTriplesInner) HasEvidence() bool`

HasEvidence returns a boolean if a field has been set.

### GetEvidenceRegionId

`func (o *ListDocumentTriples200ResponseTriplesInner) GetEvidenceRegionId() string`

GetEvidenceRegionId returns the EvidenceRegionId field if non-nil, zero value otherwise.

### GetEvidenceRegionIdOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetEvidenceRegionIdOk() (*string, bool)`

GetEvidenceRegionIdOk returns a tuple with the EvidenceRegionId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEvidenceRegionId

`func (o *ListDocumentTriples200ResponseTriplesInner) SetEvidenceRegionId(v string)`

SetEvidenceRegionId sets EvidenceRegionId field to given value.

### HasEvidenceRegionId

`func (o *ListDocumentTriples200ResponseTriplesInner) HasEvidenceRegionId() bool`

HasEvidenceRegionId returns a boolean if a field has been set.

### GetNote

`func (o *ListDocumentTriples200ResponseTriplesInner) GetNote() string`

GetNote returns the Note field if non-nil, zero value otherwise.

### GetNoteOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetNoteOk() (*string, bool)`

GetNoteOk returns a tuple with the Note field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNote

`func (o *ListDocumentTriples200ResponseTriplesInner) SetNote(v string)`

SetNote sets Note field to given value.

### HasNote

`func (o *ListDocumentTriples200ResponseTriplesInner) HasNote() bool`

HasNote returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ListDocumentTriples200ResponseTriplesInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListDocumentTriples200ResponseTriplesInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ListDocumentTriples200ResponseTriplesInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetStatus

`func (o *ListDocumentTriples200ResponseTriplesInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ListDocumentTriples200ResponseTriplesInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ListDocumentTriples200ResponseTriplesInner) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ListDocumentTriples200ResponseTriplesInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


