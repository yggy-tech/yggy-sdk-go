# ListProjects200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Projects** | [**[]ListProjects200ResponseProjectsInner**](ListProjects200ResponseProjectsInner.md) |  | 
**Pinned** | [**[]ListProjects200ResponseProjectsInner**](ListProjects200ResponseProjectsInner.md) |  | 
**Personal** | [**ListProjects200ResponseProjectsInner**](ListProjects200ResponseProjectsInner.md) |  | 
**Total** | **int32** |  | 
**Limit** | **int32** |  | 
**Offset** | **int32** |  | 

## Methods

### NewListProjects200Response

`func NewListProjects200Response(success bool, projects []ListProjects200ResponseProjectsInner, pinned []ListProjects200ResponseProjectsInner, personal ListProjects200ResponseProjectsInner, total int32, limit int32, offset int32, ) *ListProjects200Response`

NewListProjects200Response instantiates a new ListProjects200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListProjects200ResponseWithDefaults

`func NewListProjects200ResponseWithDefaults() *ListProjects200Response`

NewListProjects200ResponseWithDefaults instantiates a new ListProjects200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *ListProjects200Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *ListProjects200Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *ListProjects200Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetProjects

`func (o *ListProjects200Response) GetProjects() []ListProjects200ResponseProjectsInner`

GetProjects returns the Projects field if non-nil, zero value otherwise.

### GetProjectsOk

`func (o *ListProjects200Response) GetProjectsOk() (*[]ListProjects200ResponseProjectsInner, bool)`

GetProjectsOk returns a tuple with the Projects field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjects

`func (o *ListProjects200Response) SetProjects(v []ListProjects200ResponseProjectsInner)`

SetProjects sets Projects field to given value.


### GetPinned

`func (o *ListProjects200Response) GetPinned() []ListProjects200ResponseProjectsInner`

GetPinned returns the Pinned field if non-nil, zero value otherwise.

### GetPinnedOk

`func (o *ListProjects200Response) GetPinnedOk() (*[]ListProjects200ResponseProjectsInner, bool)`

GetPinnedOk returns a tuple with the Pinned field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPinned

`func (o *ListProjects200Response) SetPinned(v []ListProjects200ResponseProjectsInner)`

SetPinned sets Pinned field to given value.


### GetPersonal

`func (o *ListProjects200Response) GetPersonal() ListProjects200ResponseProjectsInner`

GetPersonal returns the Personal field if non-nil, zero value otherwise.

### GetPersonalOk

`func (o *ListProjects200Response) GetPersonalOk() (*ListProjects200ResponseProjectsInner, bool)`

GetPersonalOk returns a tuple with the Personal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPersonal

`func (o *ListProjects200Response) SetPersonal(v ListProjects200ResponseProjectsInner)`

SetPersonal sets Personal field to given value.


### GetTotal

`func (o *ListProjects200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ListProjects200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ListProjects200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetLimit

`func (o *ListProjects200Response) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ListProjects200Response) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ListProjects200Response) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### GetOffset

`func (o *ListProjects200Response) GetOffset() int32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *ListProjects200Response) GetOffsetOk() (*int32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *ListProjects200Response) SetOffset(v int32)`

SetOffset sets Offset field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


