# AppErrorResponseError

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** |  | 
**Code** | **string** |  | 
**Details** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewAppErrorResponseError

`func NewAppErrorResponseError(message string, code string, ) *AppErrorResponseError`

NewAppErrorResponseError instantiates a new AppErrorResponseError object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppErrorResponseErrorWithDefaults

`func NewAppErrorResponseErrorWithDefaults() *AppErrorResponseError`

NewAppErrorResponseErrorWithDefaults instantiates a new AppErrorResponseError object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *AppErrorResponseError) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *AppErrorResponseError) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *AppErrorResponseError) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetCode

`func (o *AppErrorResponseError) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *AppErrorResponseError) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *AppErrorResponseError) SetCode(v string)`

SetCode sets Code field to given value.


### GetDetails

`func (o *AppErrorResponseError) GetDetails() interface{}`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *AppErrorResponseError) GetDetailsOk() (*interface{}, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *AppErrorResponseError) SetDetails(v interface{})`

SetDetails sets Details field to given value.

### HasDetails

`func (o *AppErrorResponseError) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### SetDetailsNil

`func (o *AppErrorResponseError) SetDetailsNil(b bool)`

 SetDetailsNil sets the value for Details to be an explicit nil

### UnsetDetails
`func (o *AppErrorResponseError) UnsetDetails()`

UnsetDetails ensures that no value is present for Details, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


