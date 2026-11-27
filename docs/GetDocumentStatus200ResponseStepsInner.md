# GetDocumentStatus200ResponseStepsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Name** | **string** |  | 
**Status** | **string** |  | 
**StartedAt** | Pointer to **float32** |  | [optional] 
**CompletedAt** | Pointer to **float32** |  | [optional] 
**DurationMs** | Pointer to **float32** |  | [optional] 
**Message** | Pointer to **string** |  | [optional] 
**Current** | Pointer to **float32** |  | [optional] 
**Total** | Pointer to **float32** |  | [optional] 
**Unit** | Pointer to **string** |  | [optional] 
**WaitedForCapacity** | Pointer to **bool** |  | [optional] 

## Methods

### NewGetDocumentStatus200ResponseStepsInner

`func NewGetDocumentStatus200ResponseStepsInner(id string, name string, status string, ) *GetDocumentStatus200ResponseStepsInner`

NewGetDocumentStatus200ResponseStepsInner instantiates a new GetDocumentStatus200ResponseStepsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDocumentStatus200ResponseStepsInnerWithDefaults

`func NewGetDocumentStatus200ResponseStepsInnerWithDefaults() *GetDocumentStatus200ResponseStepsInner`

NewGetDocumentStatus200ResponseStepsInnerWithDefaults instantiates a new GetDocumentStatus200ResponseStepsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *GetDocumentStatus200ResponseStepsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *GetDocumentStatus200ResponseStepsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *GetDocumentStatus200ResponseStepsInner) SetId(v string)`

SetId sets Id field to given value.


### GetName

`func (o *GetDocumentStatus200ResponseStepsInner) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *GetDocumentStatus200ResponseStepsInner) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *GetDocumentStatus200ResponseStepsInner) SetName(v string)`

SetName sets Name field to given value.


### GetStatus

`func (o *GetDocumentStatus200ResponseStepsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetDocumentStatus200ResponseStepsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetDocumentStatus200ResponseStepsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStartedAt

`func (o *GetDocumentStatus200ResponseStepsInner) GetStartedAt() float32`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *GetDocumentStatus200ResponseStepsInner) GetStartedAtOk() (*float32, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *GetDocumentStatus200ResponseStepsInner) SetStartedAt(v float32)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *GetDocumentStatus200ResponseStepsInner) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### GetCompletedAt

`func (o *GetDocumentStatus200ResponseStepsInner) GetCompletedAt() float32`

GetCompletedAt returns the CompletedAt field if non-nil, zero value otherwise.

### GetCompletedAtOk

`func (o *GetDocumentStatus200ResponseStepsInner) GetCompletedAtOk() (*float32, bool)`

GetCompletedAtOk returns a tuple with the CompletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompletedAt

`func (o *GetDocumentStatus200ResponseStepsInner) SetCompletedAt(v float32)`

SetCompletedAt sets CompletedAt field to given value.

### HasCompletedAt

`func (o *GetDocumentStatus200ResponseStepsInner) HasCompletedAt() bool`

HasCompletedAt returns a boolean if a field has been set.

### GetDurationMs

`func (o *GetDocumentStatus200ResponseStepsInner) GetDurationMs() float32`

GetDurationMs returns the DurationMs field if non-nil, zero value otherwise.

### GetDurationMsOk

`func (o *GetDocumentStatus200ResponseStepsInner) GetDurationMsOk() (*float32, bool)`

GetDurationMsOk returns a tuple with the DurationMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDurationMs

`func (o *GetDocumentStatus200ResponseStepsInner) SetDurationMs(v float32)`

SetDurationMs sets DurationMs field to given value.

### HasDurationMs

`func (o *GetDocumentStatus200ResponseStepsInner) HasDurationMs() bool`

HasDurationMs returns a boolean if a field has been set.

### GetMessage

`func (o *GetDocumentStatus200ResponseStepsInner) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *GetDocumentStatus200ResponseStepsInner) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *GetDocumentStatus200ResponseStepsInner) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *GetDocumentStatus200ResponseStepsInner) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetCurrent

`func (o *GetDocumentStatus200ResponseStepsInner) GetCurrent() float32`

GetCurrent returns the Current field if non-nil, zero value otherwise.

### GetCurrentOk

`func (o *GetDocumentStatus200ResponseStepsInner) GetCurrentOk() (*float32, bool)`

GetCurrentOk returns a tuple with the Current field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrent

`func (o *GetDocumentStatus200ResponseStepsInner) SetCurrent(v float32)`

SetCurrent sets Current field to given value.

### HasCurrent

`func (o *GetDocumentStatus200ResponseStepsInner) HasCurrent() bool`

HasCurrent returns a boolean if a field has been set.

### GetTotal

`func (o *GetDocumentStatus200ResponseStepsInner) GetTotal() float32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *GetDocumentStatus200ResponseStepsInner) GetTotalOk() (*float32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *GetDocumentStatus200ResponseStepsInner) SetTotal(v float32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *GetDocumentStatus200ResponseStepsInner) HasTotal() bool`

HasTotal returns a boolean if a field has been set.

### GetUnit

`func (o *GetDocumentStatus200ResponseStepsInner) GetUnit() string`

GetUnit returns the Unit field if non-nil, zero value otherwise.

### GetUnitOk

`func (o *GetDocumentStatus200ResponseStepsInner) GetUnitOk() (*string, bool)`

GetUnitOk returns a tuple with the Unit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUnit

`func (o *GetDocumentStatus200ResponseStepsInner) SetUnit(v string)`

SetUnit sets Unit field to given value.

### HasUnit

`func (o *GetDocumentStatus200ResponseStepsInner) HasUnit() bool`

HasUnit returns a boolean if a field has been set.

### GetWaitedForCapacity

`func (o *GetDocumentStatus200ResponseStepsInner) GetWaitedForCapacity() bool`

GetWaitedForCapacity returns the WaitedForCapacity field if non-nil, zero value otherwise.

### GetWaitedForCapacityOk

`func (o *GetDocumentStatus200ResponseStepsInner) GetWaitedForCapacityOk() (*bool, bool)`

GetWaitedForCapacityOk returns a tuple with the WaitedForCapacity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWaitedForCapacity

`func (o *GetDocumentStatus200ResponseStepsInner) SetWaitedForCapacity(v bool)`

SetWaitedForCapacity sets WaitedForCapacity field to given value.

### HasWaitedForCapacity

`func (o *GetDocumentStatus200ResponseStepsInner) HasWaitedForCapacity() bool`

HasWaitedForCapacity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


