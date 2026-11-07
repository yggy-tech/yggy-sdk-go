# ListProjects200ResponseProjectsInner

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
**Visibility** | **string** | Who in the organization can see that this project exists. &#x60;private&#x60; (the default): only project members and organization owners and admins. &#x60;public&#x60;: every organization member sees its name in the project list, but only members can open it. A personal project (My files) is always &#x60;private&#x60;. | 
**ExtractionPurpose** | Pointer to **NullableString** |  | [optional] 
**ExtractionInclude** | Pointer to **[]string** |  | [optional] 
**ExtractionSkip** | Pointer to **[]string** |  | [optional] 
**ExtractionGuidanceRevision** | Pointer to **int32** |  | [optional] 
**EntityMergeMode** | Pointer to **string** |  | [optional] 
**CreatedAt** | Pointer to **string** |  | [optional] 
**UpdatedAt** | Pointer to **string** |  | [optional] 
**DocumentCount** | **NullableInt32** | Documents in the project. Null when &#x60;isMember&#x60; is false: a public project&#39;s numbers are for its members only. | 
**TripleCount** | **NullableInt32** | Relations (triples) in the project. Null when &#x60;isMember&#x60; is false: a public project&#39;s numbers are for its members only. | 
**EntityCount** | **NullableInt32** | Entities in the project. Null when &#x60;isMember&#x60; is false: a public project&#39;s numbers are for its members only. | 
**IsMember** | **bool** | True when the caller can open the project: a project member, an organization owner or admin, or an organization API key. False for a public project the caller is not a member of. | 

## Methods

### NewListProjects200ResponseProjectsInner

`func NewListProjects200ResponseProjectsInner(id string, slug string, name string, color string, organizationId string, visibility string, documentCount NullableInt32, tripleCount NullableInt32, entityCount NullableInt32, isMember bool, ) *ListProjects200ResponseProjectsInner`

NewListProjects200ResponseProjectsInner instantiates a new ListProjects200ResponseProjectsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListProjects200ResponseProjectsInnerWithDefaults

`func NewListProjects200ResponseProjectsInnerWithDefaults() *ListProjects200ResponseProjectsInner`

NewListProjects200ResponseProjectsInnerWithDefaults instantiates a new ListProjects200ResponseProjectsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListProjects200ResponseProjectsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListProjects200ResponseProjectsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListProjects200ResponseProjectsInner) SetId(v string)`

SetId sets Id field to given value.


### GetSlug

`func (o *ListProjects200ResponseProjectsInner) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *ListProjects200ResponseProjectsInner) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *ListProjects200ResponseProjectsInner) SetSlug(v string)`

SetSlug sets Slug field to given value.


### GetName

`func (o *ListProjects200ResponseProjectsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ListProjects200ResponseProjectsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ListProjects200ResponseProjectsInner) SetName(v string)`

SetName sets Name field to given value.


### GetColor

`func (o *ListProjects200ResponseProjectsInner) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *ListProjects200ResponseProjectsInner) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *ListProjects200ResponseProjectsInner) SetColor(v string)`

SetColor sets Color field to given value.


### GetOrganizationId

`func (o *ListProjects200ResponseProjectsInner) GetOrganizationId() string`

GetOrganizationId returns the OrganizationId field if non-nil, zero value otherwise.

### GetOrganizationIdOk

`func (o *ListProjects200ResponseProjectsInner) GetOrganizationIdOk() (*string, bool)`

GetOrganizationIdOk returns a tuple with the OrganizationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOrganizationId

`func (o *ListProjects200ResponseProjectsInner) SetOrganizationId(v string)`

SetOrganizationId sets OrganizationId field to given value.


### GetExternalId

`func (o *ListProjects200ResponseProjectsInner) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *ListProjects200ResponseProjectsInner) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *ListProjects200ResponseProjectsInner) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *ListProjects200ResponseProjectsInner) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### SetExternalIdNil

`func (o *ListProjects200ResponseProjectsInner) SetExternalIdNil(b bool)`

 SetExternalIdNil sets the value for ExternalId to be an explicit nil

### UnsetExternalId
`func (o *ListProjects200ResponseProjectsInner) UnsetExternalId()`

UnsetExternalId ensures that no value is present for ExternalId, not even an explicit nil
### GetKind

`func (o *ListProjects200ResponseProjectsInner) GetKind() string`

GetKind returns the Kind field if non-nil, zero value otherwise.

### GetKindOk

`func (o *ListProjects200ResponseProjectsInner) GetKindOk() (*string, bool)`

GetKindOk returns a tuple with the Kind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKind

`func (o *ListProjects200ResponseProjectsInner) SetKind(v string)`

SetKind sets Kind field to given value.

### HasKind

`func (o *ListProjects200ResponseProjectsInner) HasKind() bool`

HasKind returns a boolean if a field has been set.

### GetVisibility

`func (o *ListProjects200ResponseProjectsInner) GetVisibility() string`

GetVisibility returns the Visibility field if non-nil, zero value otherwise.

### GetVisibilityOk

`func (o *ListProjects200ResponseProjectsInner) GetVisibilityOk() (*string, bool)`

GetVisibilityOk returns a tuple with the Visibility field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVisibility

`func (o *ListProjects200ResponseProjectsInner) SetVisibility(v string)`

SetVisibility sets Visibility field to given value.


### GetExtractionPurpose

`func (o *ListProjects200ResponseProjectsInner) GetExtractionPurpose() string`

GetExtractionPurpose returns the ExtractionPurpose field if non-nil, zero value otherwise.

### GetExtractionPurposeOk

`func (o *ListProjects200ResponseProjectsInner) GetExtractionPurposeOk() (*string, bool)`

GetExtractionPurposeOk returns a tuple with the ExtractionPurpose field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionPurpose

`func (o *ListProjects200ResponseProjectsInner) SetExtractionPurpose(v string)`

SetExtractionPurpose sets ExtractionPurpose field to given value.

### HasExtractionPurpose

`func (o *ListProjects200ResponseProjectsInner) HasExtractionPurpose() bool`

HasExtractionPurpose returns a boolean if a field has been set.

### SetExtractionPurposeNil

`func (o *ListProjects200ResponseProjectsInner) SetExtractionPurposeNil(b bool)`

 SetExtractionPurposeNil sets the value for ExtractionPurpose to be an explicit nil

### UnsetExtractionPurpose
`func (o *ListProjects200ResponseProjectsInner) UnsetExtractionPurpose()`

UnsetExtractionPurpose ensures that no value is present for ExtractionPurpose, not even an explicit nil
### GetExtractionInclude

`func (o *ListProjects200ResponseProjectsInner) GetExtractionInclude() []string`

GetExtractionInclude returns the ExtractionInclude field if non-nil, zero value otherwise.

### GetExtractionIncludeOk

`func (o *ListProjects200ResponseProjectsInner) GetExtractionIncludeOk() (*[]string, bool)`

GetExtractionIncludeOk returns a tuple with the ExtractionInclude field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionInclude

`func (o *ListProjects200ResponseProjectsInner) SetExtractionInclude(v []string)`

SetExtractionInclude sets ExtractionInclude field to given value.

### HasExtractionInclude

`func (o *ListProjects200ResponseProjectsInner) HasExtractionInclude() bool`

HasExtractionInclude returns a boolean if a field has been set.

### GetExtractionSkip

`func (o *ListProjects200ResponseProjectsInner) GetExtractionSkip() []string`

GetExtractionSkip returns the ExtractionSkip field if non-nil, zero value otherwise.

### GetExtractionSkipOk

`func (o *ListProjects200ResponseProjectsInner) GetExtractionSkipOk() (*[]string, bool)`

GetExtractionSkipOk returns a tuple with the ExtractionSkip field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionSkip

`func (o *ListProjects200ResponseProjectsInner) SetExtractionSkip(v []string)`

SetExtractionSkip sets ExtractionSkip field to given value.

### HasExtractionSkip

`func (o *ListProjects200ResponseProjectsInner) HasExtractionSkip() bool`

HasExtractionSkip returns a boolean if a field has been set.

### GetExtractionGuidanceRevision

`func (o *ListProjects200ResponseProjectsInner) GetExtractionGuidanceRevision() int32`

GetExtractionGuidanceRevision returns the ExtractionGuidanceRevision field if non-nil, zero value otherwise.

### GetExtractionGuidanceRevisionOk

`func (o *ListProjects200ResponseProjectsInner) GetExtractionGuidanceRevisionOk() (*int32, bool)`

GetExtractionGuidanceRevisionOk returns a tuple with the ExtractionGuidanceRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionGuidanceRevision

`func (o *ListProjects200ResponseProjectsInner) SetExtractionGuidanceRevision(v int32)`

SetExtractionGuidanceRevision sets ExtractionGuidanceRevision field to given value.

### HasExtractionGuidanceRevision

`func (o *ListProjects200ResponseProjectsInner) HasExtractionGuidanceRevision() bool`

HasExtractionGuidanceRevision returns a boolean if a field has been set.

### GetEntityMergeMode

`func (o *ListProjects200ResponseProjectsInner) GetEntityMergeMode() string`

GetEntityMergeMode returns the EntityMergeMode field if non-nil, zero value otherwise.

### GetEntityMergeModeOk

`func (o *ListProjects200ResponseProjectsInner) GetEntityMergeModeOk() (*string, bool)`

GetEntityMergeModeOk returns a tuple with the EntityMergeMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityMergeMode

`func (o *ListProjects200ResponseProjectsInner) SetEntityMergeMode(v string)`

SetEntityMergeMode sets EntityMergeMode field to given value.

### HasEntityMergeMode

`func (o *ListProjects200ResponseProjectsInner) HasEntityMergeMode() bool`

HasEntityMergeMode returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ListProjects200ResponseProjectsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListProjects200ResponseProjectsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListProjects200ResponseProjectsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ListProjects200ResponseProjectsInner) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *ListProjects200ResponseProjectsInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListProjects200ResponseProjectsInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListProjects200ResponseProjectsInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.

### HasUpdatedAt

`func (o *ListProjects200ResponseProjectsInner) HasUpdatedAt() bool`

HasUpdatedAt returns a boolean if a field has been set.

### GetDocumentCount

`func (o *ListProjects200ResponseProjectsInner) GetDocumentCount() int32`

GetDocumentCount returns the DocumentCount field if non-nil, zero value otherwise.

### GetDocumentCountOk

`func (o *ListProjects200ResponseProjectsInner) GetDocumentCountOk() (*int32, bool)`

GetDocumentCountOk returns a tuple with the DocumentCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentCount

`func (o *ListProjects200ResponseProjectsInner) SetDocumentCount(v int32)`

SetDocumentCount sets DocumentCount field to given value.


### SetDocumentCountNil

`func (o *ListProjects200ResponseProjectsInner) SetDocumentCountNil(b bool)`

 SetDocumentCountNil sets the value for DocumentCount to be an explicit nil

### UnsetDocumentCount
`func (o *ListProjects200ResponseProjectsInner) UnsetDocumentCount()`

UnsetDocumentCount ensures that no value is present for DocumentCount, not even an explicit nil
### GetTripleCount

`func (o *ListProjects200ResponseProjectsInner) GetTripleCount() int32`

GetTripleCount returns the TripleCount field if non-nil, zero value otherwise.

### GetTripleCountOk

`func (o *ListProjects200ResponseProjectsInner) GetTripleCountOk() (*int32, bool)`

GetTripleCountOk returns a tuple with the TripleCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTripleCount

`func (o *ListProjects200ResponseProjectsInner) SetTripleCount(v int32)`

SetTripleCount sets TripleCount field to given value.


### SetTripleCountNil

`func (o *ListProjects200ResponseProjectsInner) SetTripleCountNil(b bool)`

 SetTripleCountNil sets the value for TripleCount to be an explicit nil

### UnsetTripleCount
`func (o *ListProjects200ResponseProjectsInner) UnsetTripleCount()`

UnsetTripleCount ensures that no value is present for TripleCount, not even an explicit nil
### GetEntityCount

`func (o *ListProjects200ResponseProjectsInner) GetEntityCount() int32`

GetEntityCount returns the EntityCount field if non-nil, zero value otherwise.

### GetEntityCountOk

`func (o *ListProjects200ResponseProjectsInner) GetEntityCountOk() (*int32, bool)`

GetEntityCountOk returns a tuple with the EntityCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEntityCount

`func (o *ListProjects200ResponseProjectsInner) SetEntityCount(v int32)`

SetEntityCount sets EntityCount field to given value.


### SetEntityCountNil

`func (o *ListProjects200ResponseProjectsInner) SetEntityCountNil(b bool)`

 SetEntityCountNil sets the value for EntityCount to be an explicit nil

### UnsetEntityCount
`func (o *ListProjects200ResponseProjectsInner) UnsetEntityCount()`

UnsetEntityCount ensures that no value is present for EntityCount, not even an explicit nil
### GetIsMember

`func (o *ListProjects200ResponseProjectsInner) GetIsMember() bool`

GetIsMember returns the IsMember field if non-nil, zero value otherwise.

### GetIsMemberOk

`func (o *ListProjects200ResponseProjectsInner) GetIsMemberOk() (*bool, bool)`

GetIsMemberOk returns a tuple with the IsMember field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsMember

`func (o *ListProjects200ResponseProjectsInner) SetIsMember(v bool)`

SetIsMember sets IsMember field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


