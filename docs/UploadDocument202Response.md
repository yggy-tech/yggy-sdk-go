# UploadDocument202Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**DocumentId** | **string** |  | 
**InternalId** | **string** |  | 
**InvocationId** | **string** |  | 
**Status** | **string** | stored: saved without analysis because the account has no credits | 
**StoragePath** | **NullableString** |  | 
**StorageUrl** | **NullableString** |  | 
**Message** | **string** |  | 

## Methods

### NewUploadDocument202Response

`func NewUploadDocument202Response(success bool, documentId string, internalId string, invocationId string, status string, storagePath NullableString, storageUrl NullableString, message string, ) *UploadDocument202Response`

NewUploadDocument202Response instantiates a new UploadDocument202Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewUploadDocument202ResponseWithDefaults

`func NewUploadDocument202ResponseWithDefaults() *UploadDocument202Response`

NewUploadDocument202ResponseWithDefaults instantiates a new UploadDocument202Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *UploadDocument202Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *UploadDocument202Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *UploadDocument202Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetDocumentId

`func (o *UploadDocument202Response) GetDocumentId() string`

GetDocumentId returns the DocumentId field if non-nil, zero value otherwise.

### GetDocumentIdOk

`func (o *UploadDocument202Response) GetDocumentIdOk() (*string, bool)`

GetDocumentIdOk returns a tuple with the DocumentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentId

`func (o *UploadDocument202Response) SetDocumentId(v string)`

SetDocumentId sets DocumentId field to given value.


### GetInternalId

`func (o *UploadDocument202Response) GetInternalId() string`

GetInternalId returns the InternalId field if non-nil, zero value otherwise.

### GetInternalIdOk

`func (o *UploadDocument202Response) GetInternalIdOk() (*string, bool)`

GetInternalIdOk returns a tuple with the InternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInternalId

`func (o *UploadDocument202Response) SetInternalId(v string)`

SetInternalId sets InternalId field to given value.


### GetInvocationId

`func (o *UploadDocument202Response) GetInvocationId() string`

GetInvocationId returns the InvocationId field if non-nil, zero value otherwise.

### GetInvocationIdOk

`func (o *UploadDocument202Response) GetInvocationIdOk() (*string, bool)`

GetInvocationIdOk returns a tuple with the InvocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvocationId

`func (o *UploadDocument202Response) SetInvocationId(v string)`

SetInvocationId sets InvocationId field to given value.


### GetStatus

`func (o *UploadDocument202Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *UploadDocument202Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *UploadDocument202Response) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetStoragePath

`func (o *UploadDocument202Response) GetStoragePath() string`

GetStoragePath returns the StoragePath field if non-nil, zero value otherwise.

### GetStoragePathOk

`func (o *UploadDocument202Response) GetStoragePathOk() (*string, bool)`

GetStoragePathOk returns a tuple with the StoragePath field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoragePath

`func (o *UploadDocument202Response) SetStoragePath(v string)`

SetStoragePath sets StoragePath field to given value.


### SetStoragePathNil

`func (o *UploadDocument202Response) SetStoragePathNil(b bool)`

 SetStoragePathNil sets the value for StoragePath to be an explicit nil

### UnsetStoragePath
`func (o *UploadDocument202Response) UnsetStoragePath()`

UnsetStoragePath ensures that no value is present for StoragePath, not even an explicit nil
### GetStorageUrl

`func (o *UploadDocument202Response) GetStorageUrl() string`

GetStorageUrl returns the StorageUrl field if non-nil, zero value otherwise.

### GetStorageUrlOk

`func (o *UploadDocument202Response) GetStorageUrlOk() (*string, bool)`

GetStorageUrlOk returns a tuple with the StorageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageUrl

`func (o *UploadDocument202Response) SetStorageUrl(v string)`

SetStorageUrl sets StorageUrl field to given value.


### SetStorageUrlNil

`func (o *UploadDocument202Response) SetStorageUrlNil(b bool)`

 SetStorageUrlNil sets the value for StorageUrl to be an explicit nil

### UnsetStorageUrl
`func (o *UploadDocument202Response) UnsetStorageUrl()`

UnsetStorageUrl ensures that no value is present for StorageUrl, not even an explicit nil
### GetMessage

`func (o *UploadDocument202Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *UploadDocument202Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *UploadDocument202Response) SetMessage(v string)`

SetMessage sets Message field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


