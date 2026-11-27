# HowSure

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Level** | **string** |  | 
**Reasons** | [**[]HowSureReasonsInner**](HowSureReasonsInner.md) |  | 

## Methods

### NewHowSure

`func NewHowSure(level string, reasons []HowSureReasonsInner, ) *HowSure`

NewHowSure instantiates a new HowSure object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHowSureWithDefaults

`func NewHowSureWithDefaults() *HowSure`

NewHowSureWithDefaults instantiates a new HowSure object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLevel

`func (o *HowSure) GetLevel() string`

GetLevel returns the Level field if non-nil, zero value otherwise.

### GetLevelOk

`func (o *HowSure) GetLevelOk() (*string, bool)`

GetLevelOk returns a tuple with the Level field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLevel

`func (o *HowSure) SetLevel(v string)`

SetLevel sets Level field to given value.


### GetReasons

`func (o *HowSure) GetReasons() []HowSureReasonsInner`

GetReasons returns the Reasons field if non-nil, zero value otherwise.

### GetReasonsOk

`func (o *HowSure) GetReasonsOk() (*[]HowSureReasonsInner, bool)`

GetReasonsOk returns a tuple with the Reasons field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReasons

`func (o *HowSure) SetReasons(v []HowSureReasonsInner)`

SetReasons sets Reasons field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


