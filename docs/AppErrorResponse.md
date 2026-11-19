# AppErrorResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Error** | [**AppErrorResponseError**](AppErrorResponseError.md) |  | 

## Methods

### NewAppErrorResponse

`func NewAppErrorResponse(success bool, error_ AppErrorResponseError, ) *AppErrorResponse`

NewAppErrorResponse instantiates a new AppErrorResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppErrorResponseWithDefaults

`func NewAppErrorResponseWithDefaults() *AppErrorResponse`

NewAppErrorResponseWithDefaults instantiates a new AppErrorResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *AppErrorResponse) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *AppErrorResponse) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *AppErrorResponse) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetError

`func (o *AppErrorResponse) GetError() AppErrorResponseError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *AppErrorResponse) GetErrorOk() (*AppErrorResponseError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *AppErrorResponse) SetError(v AppErrorResponseError)`

SetError sets Error field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


