# CreateProject201ResponseProject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Slug** | **string** |  | 
**Name** | **string** |  | 
**Color** | **string** |  | 
**OrganizationId** | **string** |  | 
**ExternalId** | Pointer to **NullableString** |  | [optional] 
**Kind** | Pointer to **string** |  | [optional] 
**ExtractionPurpose** | Pointer to **NullableString** |  | [optional] 
**ExtractionInclude** | Pointer to **[]string** |  | [optional] 
**ExtractionSkip** | Pointer to **[]string** |  | [optional] 
**ExtractionGuidanceRevision** | Pointer to **int32** |  | [optional] 
**EntityMergeMode** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 

## Methods

### NewCreateProject201ResponseProject

`func NewCreateProject201ResponseProject(id string, slug string, name string, color string, organizationId string, ) *CreateProject201ResponseProject`

NewCreateProject201ResponseProject instantiates a new CreateProject201ResponseProject object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateProject201ResponseProjectWithDefaults

`func NewCreateProject201ResponseProjectWithDefaults() *CreateProject201ResponseProject`

NewCreateProject201ResponseProjectWithDefaults instantiates a new CreateProject201ResponseProject object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CreateProject201ResponseProject) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CreateProject201ResponseProject) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CreateProject201ResponseProject) SetId(v string)`

SetId sets Id field to given value.


### GetSlug

`func (o *CreateProject201ResponseProject) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *CreateProject201ResponseProject) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *CreateProject201ResponseProject) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetName

`func (o *CreateProject201ResponseProject) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CreateProject201ResponseProject) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CreateProject201ResponseProject) SetName(v string)`

SetName sets Name field to given value.


### GetColor

`func (o *CreateProject201ResponseProject) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *CreateProject201ResponseProject) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *CreateProject201ResponseProject) SetColor(v string)`

SetColor sets Color field to given value.


### GetOrganizationId

`func (o *CreateProject201ResponseProject) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *CreateProject201ResponseProject) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *CreateProject201ResponseProject) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetExternalId

`func (o *CreateProject201ResponseProject) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *CreateProject201ResponseProject) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *CreateProject201ResponseProject) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *CreateProject201ResponseProject) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### SetExternalIdNil

`func (o *CreateProject201ResponseProject) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *CreateProject201ResponseProject) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetKind

`func (o *CreateProject201ResponseProject) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *CreateProject201ResponseProject) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *CreateProject201ResponseProject) SetKind(v string)`

SetKind sets Kind field to given value.

### HasKind

`func (o *CreateProject201ResponseProject) HasKind() bool`

HasKind returns a boolean if a field has been set.

### GetExtractionPurpose

`func (o *CreateProject201ResponseProject) GetExtractionPurpose() string`

GetExtractionPurpose returns the ExtractionPurpose field if non-nil, zero value otherwise.

### GetExtractionPurposeOk

`func (o *CreateProject201ResponseProject) GetExtractionPurposeOk() (*string, bool)`

GetExtractionPurposeOk returns a tuple with the ExtractionPurpose field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionPurpose

`func (o *CreateProject201ResponseProject) SetExtractionPurpose(v string)`

SetExtractionPurpose sets ExtractionPurpose field to given value.

### HasExtractionPurpose

`func (o *CreateProject201ResponseProject) HasExtractionPurpose() bool`

HasExtractionPurpose returns a boolean if a field has been set.

### SetExtractionPurposeNil

`func (o *CreateProject201ResponseProject) SetExtractionPurposeNil(b bool)`

 SetExtractionPurposeNil sets the value for ExtractionPurpose to be an explicit nil

### UnsetExtractionPurpose
`func (o *CreateProject201ResponseProject) UnsetExtractionPurpose()`

UnsetExtractionPurpose ensures that no value is present for ExtractionPurpose, not even an explicit nil
### GetExtractionInclude

`func (o *CreateProject201ResponseProject) GetExtractionInclude() []string`

GetExtractionInclude returns the ExtractionInclude field if non-nil, zero value otherwise.

### GetExtractionIncludeOk

`func (o *CreateProject201ResponseProject) GetExtractionIncludeOk() (*[]string, bool)`

GetExtractionIncludeOk returns a tuple with the ExtractionInclude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionInclude

`func (o *CreateProject201ResponseProject) SetExtractionInclude(v []string)`

SetExtractionInclude sets ExtractionInclude field to given value.

### HasExtractionInclude

`func (o *CreateProject201ResponseProject) HasExtractionInclude() bool`

HasExtractionInclude returns a boolean if a field has been set.

### GetExtractionSkip

`func (o *CreateProject201ResponseProject) GetExtractionSkip() []string`

GetExtractionSkip returns the ExtractionSkip field if non-nil, zero value otherwise.

### GetExtractionSkipOk

`func (o *CreateProject201ResponseProject) GetExtractionSkipOk() (*[]string, bool)`

GetExtractionSkipOk returns a tuple with the ExtractionSkip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionSkip

`func (o *CreateProject201ResponseProject) SetExtractionSkip(v []string)`

SetExtractionSkip sets ExtractionSkip field to given value.

### HasExtractionSkip

`func (o *CreateProject201ResponseProject) HasExtractionSkip() bool`

HasExtractionSkip returns a boolean if a field has been set.

### GetExtractionGuidanceRevision

`func (o *CreateProject201ResponseProject) GetExtractionGuidanceRevision() int32`

GetExtractionGuidanceRevision returns the ExtractionGuidanceRevision field if non-nil, zero value otherwise.

### GetExtractionGuidanceRevisionOk

`func (o *CreateProject201ResponseProject) GetExtractionGuidanceRevisionOk() (*int32, bool)`

GetExtractionGuidanceRevisionOk returns a tuple with the ExtractionGuidanceRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionGuidanceRevision

`func (o *CreateProject201ResponseProject) SetExtractionGuidanceRevision(v int32)`

SetExtractionGuidanceRevision sets ExtractionGuidanceRevision field to given value.

### HasExtractionGuidanceRevision

`func (o *CreateProject201ResponseProject) HasExtractionGuidanceRevision() bool`

HasExtractionGuidanceRevision returns a boolean if a field has been set.

### GetEntityMergeMode

`func (o *CreateProject201ResponseProject) GetEntityMergeMode() string`

GetEntityMergeMode returns the EntityMergeMode field if non-nil, zero value otherwise.

### GetEntityMergeModeOk

`func (o *CreateProject201ResponseProject) GetEntityMergeModeOk() (*string, bool)`

GetEntityMergeModeOk returns a tuple with the EntityMergeMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityMergeMode

`func (o *CreateProject201ResponseProject) SetEntityMergeMode(v string)`

SetEntityMergeMode sets EntityMergeMode field to given value.

### HasEntityMergeMode

`func (o *CreateProject201ResponseProject) HasEntityMergeMode() bool`

HasEntityMergeMode returns a boolean if a field has been set.

### GetCreatedAt

`func (o *CreateProject201ResponseProject) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CreateProject201ResponseProject) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CreateProject201ResponseProject) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CreateProject201ResponseProject) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *CreateProject201ResponseProject) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *CreateProject201ResponseProject) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *CreateProject201ResponseProject) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *CreateProject201ResponseProject) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


