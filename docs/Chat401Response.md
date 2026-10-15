# Chat401Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Error** | [**Chat401ResponseError**](Chat401ResponseError.md) |  | 

## Methods

### NewChat401Response

`func NewChat401Response(success bool, error_ Chat401ResponseError, ) *Chat401Response`

NewChat401Response instantiates a new Chat401Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChat401ResponseWithDefaults

`func NewChat401ResponseWithDefaults() *Chat401Response`

NewChat401ResponseWithDefaults instantiates a new Chat401Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *Chat401Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *Chat401Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *Chat401Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetError

`func (o *Chat401Response) GetError() Chat401ResponseError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *Chat401Response) GetErrorOk() (*Chat401ResponseError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *Chat401Response) SetError(v Chat401ResponseError)`

SetError sets Error field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


