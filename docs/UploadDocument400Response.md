# UploadDocument400Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | Pointer to **bool** |  | [optional] [default to false]
**Error** | **string** |  | 
**Message** | Pointer to **string** |  | [optional] 

## Methods

### NewUploadDocument400Response

`func NewUploadDocument400Response(error_ string, ) *UploadDocument400Response`

NewUploadDocument400Response instantiates a new UploadDocument400Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUploadDocument400ResponseWithDefaults

`func NewUploadDocument400ResponseWithDefaults() *UploadDocument400Response`

NewUploadDocument400ResponseWithDefaults instantiates a new UploadDocument400Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *UploadDocument400Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *UploadDocument400Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *UploadDocument400Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.

### HasSuccess

`func (o *UploadDocument400Response) HasSuccess() bool`

HasSuccess returns a boolean if a field has been set.

### GetError

`func (o *UploadDocument400Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *UploadDocument400Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *UploadDocument400Response) SetError(v string)`

SetError sets Error field to given value.


### GetMessage

`func (o *UploadDocument400Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *UploadDocument400Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *UploadDocument400Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *UploadDocument400Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


