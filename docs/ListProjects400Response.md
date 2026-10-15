# ListProjects400Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Error** | [**ListProjects400ResponseError**](ListProjects400ResponseError.md) |  | 

## Methods

### NewListProjects400Response

`func NewListProjects400Response(success bool, error_ ListProjects400ResponseError, ) *ListProjects400Response`

NewListProjects400Response instantiates a new ListProjects400Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListProjects400ResponseWithDefaults

`func NewListProjects400ResponseWithDefaults() *ListProjects400Response`

NewListProjects400ResponseWithDefaults instantiates a new ListProjects400Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ListProjects400Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ListProjects400Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ListProjects400Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetError

`func (o *ListProjects400Response) GetError() ListProjects400ResponseError`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ListProjects400Response) GetErrorOk() (*ListProjects400ResponseError, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ListProjects400Response) SetError(v ListProjects400ResponseError)`

SetError sets Error field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


