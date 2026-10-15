# ChatRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | **string** | Your question about the knowledge graph | 
**History** | Pointer to [**[]ChatRequestHistoryInner**](ChatRequestHistoryInner.md) | Previous conversation messages for context | [optional] [default to []]
**Options** | Pointer to [**ChatRequestOptions**](ChatRequestOptions.md) |  | [optional] 

## Methods

### NewChatRequest

`func NewChatRequest(message string, ) *ChatRequest`

NewChatRequest instantiates a new ChatRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewChatRequestWithDefaults

`func NewChatRequestWithDefaults() *ChatRequest`

NewChatRequestWithDefaults instantiates a new ChatRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ChatRequest) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ChatRequest) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ChatRequest) SetMessage(v string)`

SetMessage sets Message field to given value.


### GetHistory

`func (o *ChatRequest) GetHistory() []ChatRequestHistoryInner`

GetHistory returns the History field if non-nil, zero value otherwise.

### GetHistoryOk

`func (o *ChatRequest) GetHistoryOk() (*[]ChatRequestHistoryInner, bool)`

GetHistoryOk returns a tuple with the History field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistory

`func (o *ChatRequest) SetHistory(v []ChatRequestHistoryInner)`

SetHistory sets History field to given value.

### HasHistory

`func (o *ChatRequest) HasHistory() bool`

HasHistory returns a boolean if a field has been set.

### GetOptions

`func (o *ChatRequest) GetOptions() ChatRequestOptions`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *ChatRequest) GetOptionsOk() (*ChatRequestOptions, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *ChatRequest) SetOptions(v ChatRequestOptions)`

SetOptions sets Options field to given value.

### HasOptions

`func (o *ChatRequest) HasOptions() bool`

HasOptions returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


