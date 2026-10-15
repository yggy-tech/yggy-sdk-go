# ListGraphExports200ResponseExportsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Format** | **string** |  | 
**Status** | **string** |  | 
**CreatedAt** | **time.Time** |  | 
**ExpiresAt** | **time.Time** |  | 
**CreatedByName** | **NullableString** |  | 
**AssertedCount** | **NullableInt32** |  | 
**HistoryCount** | **NullableInt32** |  | 
**Notes** | **[]string** |  | 

## Methods

### NewListGraphExports200ResponseExportsInner

`func NewListGraphExports200ResponseExportsInner(id string, format string, status string, createdAt time.Time, expiresAt time.Time, createdByName NullableString, assertedCount NullableInt32, historyCount NullableInt32, notes []string, ) *ListGraphExports200ResponseExportsInner`

NewListGraphExports200ResponseExportsInner instantiates a new ListGraphExports200ResponseExportsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListGraphExports200ResponseExportsInnerWithDefaults

`func NewListGraphExports200ResponseExportsInnerWithDefaults() *ListGraphExports200ResponseExportsInner`

NewListGraphExports200ResponseExportsInnerWithDefaults instantiates a new ListGraphExports200ResponseExportsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ListGraphExports200ResponseExportsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ListGraphExports200ResponseExportsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ListGraphExports200ResponseExportsInner) SetId(v string)`

SetId sets Id field to given value.


### GetFormat

`func (o *ListGraphExports200ResponseExportsInner) GetFormat() string`

GetFormat returns the Format field if non-nil, zero value otherwise.

### GetFormatOk

`func (o *ListGraphExports200ResponseExportsInner) GetFormatOk() (*string, bool)`

GetFormatOk returns a tuple with the Format field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFormat

`func (o *ListGraphExports200ResponseExportsInner) SetFormat(v string)`

SetFormat sets Format field to given value.


### GetStatus

`func (o *ListGraphExports200ResponseExportsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ListGraphExports200ResponseExportsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ListGraphExports200ResponseExportsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *ListGraphExports200ResponseExportsInner) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListGraphExports200ResponseExportsInner) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListGraphExports200ResponseExportsInner) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.


### GetExpiresAt

`func (o *ListGraphExports200ResponseExportsInner) GetExpiresAt() time.Time`

GetExpiresAt returns the ExpiresAt field if non-nil, zero value otherwise.

### GetExpiresAtOk

`func (o *ListGraphExports200ResponseExportsInner) GetExpiresAtOk() (*time.Time, bool)`

GetExpiresAtOk returns a tuple with the ExpiresAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiresAt

`func (o *ListGraphExports200ResponseExportsInner) SetExpiresAt(v time.Time)`

SetExpiresAt sets ExpiresAt field to given value.


### GetCreatedByName

`func (o *ListGraphExports200ResponseExportsInner) GetCreatedByName() string`

GetCreatedByName returns the CreatedByName field if non-nil, zero value otherwise.

### GetCreatedByNameOk

`func (o *ListGraphExports200ResponseExportsInner) GetCreatedByNameOk() (*string, bool)`

GetCreatedByNameOk returns a tuple with the CreatedByName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedByName

`func (o *ListGraphExports200ResponseExportsInner) SetCreatedByName(v string)`

SetCreatedByName sets CreatedByName field to given value.


### SetCreatedByNameNil

`func (o *ListGraphExports200ResponseExportsInner) SetCreatedByNameNil(b bool)`

 SetCreatedByNameNil sets the value for CreatedByName to be an explicit nil

### UnsetCreatedByName
`func (o *ListGraphExports200ResponseExportsInner) UnsetCreatedByName()`

UnsetCreatedByName ensures that no value is present for CreatedByName, not even an explicit nil
### GetAssertedCount

`func (o *ListGraphExports200ResponseExportsInner) GetAssertedCount() int32`

GetAssertedCount returns the AssertedCount field if non-nil, zero value otherwise.

### GetAssertedCountOk

`func (o *ListGraphExports200ResponseExportsInner) GetAssertedCountOk() (*int32, bool)`

GetAssertedCountOk returns a tuple with the AssertedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAssertedCount

`func (o *ListGraphExports200ResponseExportsInner) SetAssertedCount(v int32)`

SetAssertedCount sets AssertedCount field to given value.


### SetAssertedCountNil

`func (o *ListGraphExports200ResponseExportsInner) SetAssertedCountNil(b bool)`

 SetAssertedCountNil sets the value for AssertedCount to be an explicit nil

### UnsetAssertedCount
`func (o *ListGraphExports200ResponseExportsInner) UnsetAssertedCount()`

UnsetAssertedCount ensures that no value is present for AssertedCount, not even an explicit nil
### GetHistoryCount

`func (o *ListGraphExports200ResponseExportsInner) GetHistoryCount() int32`

GetHistoryCount returns the HistoryCount field if non-nil, zero value otherwise.

### GetHistoryCountOk

`func (o *ListGraphExports200ResponseExportsInner) GetHistoryCountOk() (*int32, bool)`

GetHistoryCountOk returns a tuple with the HistoryCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHistoryCount

`func (o *ListGraphExports200ResponseExportsInner) SetHistoryCount(v int32)`

SetHistoryCount sets HistoryCount field to given value.


### SetHistoryCountNil

`func (o *ListGraphExports200ResponseExportsInner) SetHistoryCountNil(b bool)`

 SetHistoryCountNil sets the value for HistoryCount to be an explicit nil

### UnsetHistoryCount
`func (o *ListGraphExports200ResponseExportsInner) UnsetHistoryCount()`

UnsetHistoryCount ensures that no value is present for HistoryCount, not even an explicit nil
### GetNotes

`func (o *ListGraphExports200ResponseExportsInner) GetNotes() []string`

GetNotes returns the Notes field if non-nil, zero value otherwise.

### GetNotesOk

`func (o *ListGraphExports200ResponseExportsInner) GetNotesOk() (*[]string, bool)`

GetNotesOk returns a tuple with the Notes field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotes

`func (o *ListGraphExports200ResponseExportsInner) SetNotes(v []string)`

SetNotes sets Notes field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


