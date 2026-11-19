# Chat200ResponseDataMetadata

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**ProcessingTimeMs** | **float32** |  | 
**TierApplied** | **string** |  | 
**TierReason** | Pointer to **string** | Why the applied tier differs from the requested one | [optional] 

## Methods

### NewChat200ResponseDataMetadata

`func NewChat200ResponseDataMetadata(processingTimeMs float32, tierApplied string, ) *Chat200ResponseDataMetadata`

NewChat200ResponseDataMetadata instantiates a new Chat200ResponseDataMetadata object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChat200ResponseDataMetadataWithDefaults

`func NewChat200ResponseDataMetadataWithDefaults() *Chat200ResponseDataMetadata`

NewChat200ResponseDataMetadataWithDefaults instantiates a new Chat200ResponseDataMetadata object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetProcessingTimeMs

`func (o *Chat200ResponseDataMetadata) GetProcessingTimeMs() float32`

GetProcessingTimeMs returns the ProcessingTimeMs field if non-nil, zero value otherwise.

### GetProcessingTimeMsOk

`func (o *Chat200ResponseDataMetadata) GetProcessingTimeMsOk() (*float32, bool)`

GetProcessingTimeMsOk returns a tuple with the ProcessingTimeMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingTimeMs

`func (o *Chat200ResponseDataMetadata) SetProcessingTimeMs(v float32)`

SetProcessingTimeMs sets ProcessingTimeMs field to given value.


### GetTierApplied

`func (o *Chat200ResponseDataMetadata) GetTierApplied() string`

GetTierApplied returns the TierApplied field if non-nil, zero value otherwise.

### GetTierAppliedOk

`func (o *Chat200ResponseDataMetadata) GetTierAppliedOk() (*string, bool)`

GetTierAppliedOk returns a tuple with the TierApplied field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTierApplied

`func (o *Chat200ResponseDataMetadata) SetTierApplied(v string)`

SetTierApplied sets TierApplied field to given value.


### GetTierReason

`func (o *Chat200ResponseDataMetadata) GetTierReason() string`

GetTierReason returns the TierReason field if non-nil, zero value otherwise.

### GetTierReasonOk

`func (o *Chat200ResponseDataMetadata) GetTierReasonOk() (*string, bool)`

GetTierReasonOk returns a tuple with the TierReason field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTierReason

`func (o *Chat200ResponseDataMetadata) SetTierReason(v string)`

SetTierReason sets TierReason field to given value.

### HasTierReason

`func (o *Chat200ResponseDataMetadata) HasTierReason() bool`

HasTierReason returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


