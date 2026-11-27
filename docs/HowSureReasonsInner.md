# HowSureReasonsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Code** | **string** |  | 
**ReviewId** | **string** | The open review item that holds both facts | 
**OtherValue** | **string** | What the other fact says, null when you cannot read it | 
**Count** | **int32** | Documents behind the fact | 

## Methods

### NewHowSureReasonsInner

`func NewHowSureReasonsInner(code string, reviewId string, otherValue string, count int32, ) *HowSureReasonsInner`

NewHowSureReasonsInner instantiates a new HowSureReasonsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHowSureReasonsInnerWithDefaults

`func NewHowSureReasonsInnerWithDefaults() *HowSureReasonsInner`

NewHowSureReasonsInnerWithDefaults instantiates a new HowSureReasonsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCode

`func (o *HowSureReasonsInner) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *HowSureReasonsInner) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *HowSureReasonsInner) SetCode(v string)`

SetCode sets Code field to given value.


### GetReviewId

`func (o *HowSureReasonsInner) GetReviewId() string`

GetReviewId returns the ReviewId field if non-nil, zero value otherwise.

### GetReviewIdOk

`func (o *HowSureReasonsInner) GetReviewIdOk() (*string, bool)`

GetReviewIdOk returns a tuple with the ReviewId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReviewId

`func (o *HowSureReasonsInner) SetReviewId(v string)`

SetReviewId sets ReviewId field to given value.


### GetOtherValue

`func (o *HowSureReasonsInner) GetOtherValue() string`

GetOtherValue returns the OtherValue field if non-nil, zero value otherwise.

### GetOtherValueOk

`func (o *HowSureReasonsInner) GetOtherValueOk() (*string, bool)`

GetOtherValueOk returns a tuple with the OtherValue field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtherValue

`func (o *HowSureReasonsInner) SetOtherValue(v string)`

SetOtherValue sets OtherValue field to given value.


### GetCount

`func (o *HowSureReasonsInner) GetCount() int32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *HowSureReasonsInner) GetCountOk() (*int32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *HowSureReasonsInner) SetCount(v int32)`

SetCount sets Count field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


