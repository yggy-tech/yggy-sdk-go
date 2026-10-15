# Chat200ResponseData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Response** | **string** | The AI&#39;s answer to your question | 
**Citations** | Pointer to [**[]Chat200ResponseDataCitationsInner**](Chat200ResponseDataCitationsInner.md) | Documents referenced by graph tools | [optional] 
**ToolCalls** | Pointer to [**[]Chat200ResponseDataToolCallsInner**](Chat200ResponseDataToolCallsInner.md) |  | [optional] 
**Usage** | Pointer to [**Chat200ResponseDataUsage**](Chat200ResponseDataUsage.md) |  | [optional] 
**Metadata** | [**Chat200ResponseDataMetadata**](Chat200ResponseDataMetadata.md) |  | 

## Methods

### NewChat200ResponseData

`func NewChat200ResponseData(response string, metadata Chat200ResponseDataMetadata, ) *Chat200ResponseData`

NewChat200ResponseData instantiates a new Chat200ResponseData object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChat200ResponseDataWithDefaults

`func NewChat200ResponseDataWithDefaults() *Chat200ResponseData`

NewChat200ResponseDataWithDefaults instantiates a new Chat200ResponseData object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResponse

`func (o *Chat200ResponseData) GetResponse() string`

GetResponse returns the Response field if non-nil, zero value otherwise.

### GetResponseOk

`func (o *Chat200ResponseData) GetResponseOk() (*string, bool)`

GetResponseOk returns a tuple with the Response field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResponse

`func (o *Chat200ResponseData) SetResponse(v string)`

SetResponse sets Response field to given value.


### GetCitations

`func (o *Chat200ResponseData) GetCitations() []Chat200ResponseDataCitationsInner`

GetCitations returns the Citations field if non-nil, zero value otherwise.

### GetCitationsOk

`func (o *Chat200ResponseData) GetCitationsOk() (*[]Chat200ResponseDataCitationsInner, bool)`

GetCitationsOk returns a tuple with the Citations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCitations

`func (o *Chat200ResponseData) SetCitations(v []Chat200ResponseDataCitationsInner)`

SetCitations sets Citations field to given value.

### HasCitations

`func (o *Chat200ResponseData) HasCitations() bool`

HasCitations returns a boolean if a field has been set.

### GetToolCalls

`func (o *Chat200ResponseData) GetToolCalls() []Chat200ResponseDataToolCallsInner`

GetToolCalls returns the ToolCalls field if non-nil, zero value otherwise.

### GetToolCallsOk

`func (o *Chat200ResponseData) GetToolCallsOk() (*[]Chat200ResponseDataToolCallsInner, bool)`

GetToolCallsOk returns a tuple with the ToolCalls field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetToolCalls

`func (o *Chat200ResponseData) SetToolCalls(v []Chat200ResponseDataToolCallsInner)`

SetToolCalls sets ToolCalls field to given value.

### HasToolCalls

`func (o *Chat200ResponseData) HasToolCalls() bool`

HasToolCalls returns a boolean if a field has been set.

### GetUsage

`func (o *Chat200ResponseData) GetUsage() Chat200ResponseDataUsage`

GetUsage returns the Usage field if non-nil, zero value otherwise.

### GetUsageOk

`func (o *Chat200ResponseData) GetUsageOk() (*Chat200ResponseDataUsage, bool)`

GetUsageOk returns a tuple with the Usage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUsage

`func (o *Chat200ResponseData) SetUsage(v Chat200ResponseDataUsage)`

SetUsage sets Usage field to given value.

### HasUsage

`func (o *Chat200ResponseData) HasUsage() bool`

HasUsage returns a boolean if a field has been set.

### GetMetadata

`func (o *Chat200ResponseData) GetMetadata() Chat200ResponseDataMetadata`

GetMetadata returns the Metadata field if non-nil, zero value otherwise.

### GetMetadataOk

`func (o *Chat200ResponseData) GetMetadataOk() (*Chat200ResponseDataMetadata, bool)`

GetMetadataOk returns a tuple with the Metadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadata

`func (o *Chat200ResponseData) SetMetadata(v Chat200ResponseDataMetadata)`

SetMetadata sets Metadata field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


