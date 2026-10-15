# ListDocuments200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Documents** | [**[]ListDocuments200ResponseDocumentsInner**](ListDocuments200ResponseDocumentsInner.md) |  | 
**Total** | **float32** |  | 
**Limit** | **float32** |  | 
**Offset** | **float32** |  | 

## Methods

### NewListDocuments200Response

`func NewListDocuments200Response(documents []ListDocuments200ResponseDocumentsInner, total float32, limit float32, offset float32, ) *ListDocuments200Response`

NewListDocuments200Response instantiates a new ListDocuments200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListDocuments200ResponseWithDefaults

`func NewListDocuments200ResponseWithDefaults() *ListDocuments200Response`

NewListDocuments200ResponseWithDefaults instantiates a new ListDocuments200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDocuments

`func (o *ListDocuments200Response) GetDocuments() []ListDocuments200ResponseDocumentsInner`

GetDocuments returns the Documents field if non-nil, zero value otherwise.

### GetDocumentsOk

`func (o *ListDocuments200Response) GetDocumentsOk() (*[]ListDocuments200ResponseDocumentsInner, bool)`

GetDocumentsOk returns a tuple with the Documents field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocuments

`func (o *ListDocuments200Response) SetDocuments(v []ListDocuments200ResponseDocumentsInner)`

SetDocuments sets Documents field to given value.


### GetTotal

`func (o *ListDocuments200Response) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ListDocuments200Response) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ListDocuments200Response) SetTotal(v float32)`

SetTotal sets Total field to given value.


### GetLimit

`func (o *ListDocuments200Response) GetLimit() float32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ListDocuments200Response) GetLimitOk() (*float32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ListDocuments200Response) SetLimit(v float32)`

SetLimit sets Limit field to given value.


### GetOffset

`func (o *ListDocuments200Response) GetOffset() float32`

GetOffset returns the Offset field if non-nil, zero value otherwise.

### GetOffsetOk

`func (o *ListDocuments200Response) GetOffsetOk() (*float32, bool)`

GetOffsetOk returns a tuple with the Offset field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOffset

`func (o *ListDocuments200Response) SetOffset(v float32)`

SetOffset sets Offset field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


