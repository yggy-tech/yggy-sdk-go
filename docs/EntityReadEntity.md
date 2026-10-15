# EntityReadEntity

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Label** | **string** |  | 
**Type** | **string** |  | 
**Aliases** | **[]string** |  | 
**CanonicalId** | **NullableString** |  | 
**Identity** | [**EntityReadEntityIdentity**](EntityReadEntityIdentity.md) |  | 
**HomeProjectExternalId** | **NullableString** |  | 

## Methods

### NewEntityReadEntity

`func NewEntityReadEntity(id string, label string, type_ string, aliases []string, canonicalId NullableString, identity EntityReadEntityIdentity, homeProjectExternalId NullableString, ) *EntityReadEntity`

NewEntityReadEntity instantiates a new EntityReadEntity object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewEntityReadEntityWithDefaults

`func NewEntityReadEntityWithDefaults() *EntityReadEntity`

NewEntityReadEntityWithDefaults instantiates a new EntityReadEntity object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *EntityReadEntity) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *EntityReadEntity) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *EntityReadEntity) SetId(v string)`

SetId sets Id field to given value.


### GetLabel

`func (o *EntityReadEntity) GetLabel() string`

GetLabel returns the Label field if non-nil, zero value otherwise.

### GetLabelOk

`func (o *EntityReadEntity) GetLabelOk() (*string, bool)`

GetLabelOk returns a tuple with the Label field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLabel

`func (o *EntityReadEntity) SetLabel(v string)`

SetLabel sets Label field to given value.


### GetType

`func (o *EntityReadEntity) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *EntityReadEntity) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *EntityReadEntity) SetType(v string)`

SetType sets Type field to given value.


### GetAliases

`func (o *EntityReadEntity) GetAliases() []string`

GetAliases returns the Aliases field if non-nil, zero value otherwise.

### GetAliasesOk

`func (o *EntityReadEntity) GetAliasesOk() (*[]string, bool)`

GetAliasesOk returns a tuple with the Aliases field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAliases

`func (o *EntityReadEntity) SetAliases(v []string)`

SetAliases sets Aliases field to given value.


### GetCanonicalId

`func (o *EntityReadEntity) GetCanonicalId() string`

GetCanonicalId returns the CanonicalId field if non-nil, zero value otherwise.

### GetCanonicalIdOk

`func (o *EntityReadEntity) GetCanonicalIdOk() (*string, bool)`

GetCanonicalIdOk returns a tuple with the CanonicalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCanonicalId

`func (o *EntityReadEntity) SetCanonicalId(v string)`

SetCanonicalId sets CanonicalId field to given value.


### SetCanonicalIdNil

`func (o *EntityReadEntity) SetCanonicalIdNil(b bool)`

 SetCanonicalIdNil sets the value for CanonicalId to be an explicit nil

### UnsetCanonicalId
`func (o *EntityReadEntity) UnsetCanonicalId()`

UnsetCanonicalId ensures that no value is present for CanonicalId, not even an explicit nil
### GetIdentity

`func (o *EntityReadEntity) GetIdentity() EntityReadEntityIdentity`

GetIdentity returns the Identity field if non-nil, zero value otherwise.

### GetIdentityOk

`func (o *EntityReadEntity) GetIdentityOk() (*EntityReadEntityIdentity, bool)`

GetIdentityOk returns a tuple with the Identity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIdentity

`func (o *EntityReadEntity) SetIdentity(v EntityReadEntityIdentity)`

SetIdentity sets Identity field to given value.


### GetHomeProjectExternalId

`func (o *EntityReadEntity) GetHomeProjectExternalId() string`

GetHomeProjectExternalId returns the HomeProjectExternalId field if non-nil, zero value otherwise.

### GetHomeProjectExternalIdOk

`func (o *EntityReadEntity) GetHomeProjectExternalIdOk() (*string, bool)`

GetHomeProjectExternalIdOk returns a tuple with the HomeProjectExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHomeProjectExternalId

`func (o *EntityReadEntity) SetHomeProjectExternalId(v string)`

SetHomeProjectExternalId sets HomeProjectExternalId field to given value.


### SetHomeProjectExternalIdNil

`func (o *EntityReadEntity) SetHomeProjectExternalIdNil(b bool)`

 SetHomeProjectExternalIdNil sets the value for HomeProjectExternalId to be an explicit nil

### UnsetHomeProjectExternalId
`func (o *EntityReadEntity) UnsetHomeProjectExternalId()`

UnsetHomeProjectExternalId ensures that no value is present for HomeProjectExternalId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


