# Chat200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Data** | [**Chat200ResponseData**](Chat200ResponseData.md) |  | 

## Methods

### NewChat200Response

`func NewChat200Response(success bool, data Chat200ResponseData, ) *Chat200Response`

NewChat200Response instantiates a new Chat200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChat200ResponseWithDefaults

`func NewChat200ResponseWithDefaults() *Chat200Response`

NewChat200ResponseWithDefaults instantiates a new Chat200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *Chat200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *Chat200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *Chat200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetData

`func (o *Chat200Response) GetData() Chat200ResponseData`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Chat200Response) GetDataOk() (*Chat200ResponseData, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Chat200Response) SetData(v Chat200ResponseData)`

SetData sets Data field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


