# ListDocuments200ResponseDocumentsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DocumentId** | **string** |  | 
**InvocationId** | Pointer to **string** |  | [optional] 
**Title** | **string** |  | 
**Content** | Pointer to **string** |  | [optional] 
**Source** | Pointer to **string** |  | [optional] 
**SourceKind** | Pointer to **NullableString** |  | [optional] 
**OriginSystem** | Pointer to **NullableString** |  | [optional] 
**OwnerExternalId** | Pointer to **NullableString** |  | [optional] 
**OwnerDisplayName** | Pointer to **NullableString** |  | [optional] 
**ContentType** | **string** |  | 
**Status** | **string** |  | 
**CreatedAt** | **string** |  | 
**UpdatedAt** | **string** |  | 
**TripleCount** | Pointer to **float32** |  | [optional] 
**Error** | Pointer to **string** |  | [optional] 
**Code** | Pointer to **string** |  | [optional] 
**FailureMessage** | Pointer to **string** |  | [optional] 
**StorageUrl** | Pointer to **string** |  | [optional] 
**DeletedAt** | Pointer to **string** |  | [optional] 
**ExtractionMethod** | Pointer to **string** |  | [optional] 
**StructuredRegions** | Pointer to **NullableString** |  | [optional] 
**ProvenanceChain** | Pointer to **NullableString** |  | [optional] 
**ExtractionStats** | Pointer to **NullableString** |  | [optional] 
**ProcessingSummary** | Pointer to **NullableString** |  | [optional] 
**ModelUsed** | Pointer to **NullableString** |  | [optional] 
**OcrStrategy** | Pointer to **NullableString** |  | [optional] 
**InferenceMode** | Pointer to **NullableString** |  | [optional] 
**ExtractionGuidanceRevision** | Pointer to **NullableInt32** |  | [optional] 
**GuidanceRecommendations** | Pointer to **NullableString** |  | [optional] 
**SourceCreatedAt** | Pointer to **NullableString** |  | [optional] 
**SourceModifiedAt** | Pointer to **NullableString** |  | [optional] 
**SourceAuthor** | Pointer to **NullableString** |  | [optional] 
**SourceMetadata** | Pointer to **NullableString** |  | [optional] 
**ProjectExternalId** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewListDocuments200ResponseDocumentsInner

`func NewListDocuments200ResponseDocumentsInner(documentId string, title string, contentType string, status string, createdAt string, updatedAt string, ) *ListDocuments200ResponseDocumentsInner`

NewListDocuments200ResponseDocumentsInner instantiates a new ListDocuments200ResponseDocumentsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListDocuments200ResponseDocumentsInnerWithDefaults

`func NewListDocuments200ResponseDocumentsInnerWithDefaults() *ListDocuments200ResponseDocumentsInner`

NewListDocuments200ResponseDocumentsInnerWithDefaults instantiates a new ListDocuments200ResponseDocumentsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDocumentId

`func (o *ListDocuments200ResponseDocumentsInner) GetDocumentId() string`

GetDocumentId returns the DocumentId field if non-nil, zero value otherwise.

### GetDocumentIdOk

`func (o *ListDocuments200ResponseDocumentsInner) GetDocumentIdOk() (*string, bool)`

GetDocumentIdOk returns a tuple with the DocumentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentId

`func (o *ListDocuments200ResponseDocumentsInner) SetDocumentId(v string)`

SetDocumentId sets DocumentId field to given value.


### GetInvocationId

`func (o *ListDocuments200ResponseDocumentsInner) GetInvocationId() string`

GetInvocationId returns the InvocationId field if non-nil, zero value otherwise.

### GetInvocationIdOk

`func (o *ListDocuments200ResponseDocumentsInner) GetInvocationIdOk() (*string, bool)`

GetInvocationIdOk returns a tuple with the InvocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvocationId

`func (o *ListDocuments200ResponseDocumentsInner) SetInvocationId(v string)`

SetInvocationId sets InvocationId field to given value.

### HasInvocationId

`func (o *ListDocuments200ResponseDocumentsInner) HasInvocationId() bool`

HasInvocationId returns a boolean if a field has been set.

### GetTitle

`func (o *ListDocuments200ResponseDocumentsInner) GetTitle() string`

GetTitle returns the Title field if non-nil, zero value otherwise.

### GetTitleOk

`func (o *ListDocuments200ResponseDocumentsInner) GetTitleOk() (*string, bool)`

GetTitleOk returns a tuple with the Title field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTitle

`func (o *ListDocuments200ResponseDocumentsInner) SetTitle(v string)`

SetTitle sets Title field to given value.


### GetContent

`func (o *ListDocuments200ResponseDocumentsInner) GetContent() string`

GetContent returns the Content field if non-nil, zero value otherwise.

### GetContentOk

`func (o *ListDocuments200ResponseDocumentsInner) GetContentOk() (*string, bool)`

GetContentOk returns a tuple with the Content field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContent

`func (o *ListDocuments200ResponseDocumentsInner) SetContent(v string)`

SetContent sets Content field to given value.

### HasContent

`func (o *ListDocuments200ResponseDocumentsInner) HasContent() bool`

HasContent returns a boolean if a field has been set.

### GetSource

`func (o *ListDocuments200ResponseDocumentsInner) GetSource() string`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *ListDocuments200ResponseDocumentsInner) GetSourceOk() (*string, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *ListDocuments200ResponseDocumentsInner) SetSource(v string)`

SetSource sets Source field to given value.

### HasSource

`func (o *ListDocuments200ResponseDocumentsInner) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetSourceKind

`func (o *ListDocuments200ResponseDocumentsInner) GetSourceKind() string`

GetSourceKind returns the SourceKind field if non-nil, zero value otherwise.

### GetSourceKindOk

`func (o *ListDocuments200ResponseDocumentsInner) GetSourceKindOk() (*string, bool)`

GetSourceKindOk returns a tuple with the SourceKind field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceKind

`func (o *ListDocuments200ResponseDocumentsInner) SetSourceKind(v string)`

SetSourceKind sets SourceKind field to given value.

### HasSourceKind

`func (o *ListDocuments200ResponseDocumentsInner) HasSourceKind() bool`

HasSourceKind returns a boolean if a field has been set.

### SetSourceKindNil

`func (o *ListDocuments200ResponseDocumentsInner) SetSourceKindNil(b bool)`

 SetSourceKindNil sets the value for SourceKind to be an explicit nil

### UnsetSourceKind
`func (o *ListDocuments200ResponseDocumentsInner) UnsetSourceKind()`

UnsetSourceKind ensures that no value is present for SourceKind, not even an explicit nil
### GetOriginSystem

`func (o *ListDocuments200ResponseDocumentsInner) GetOriginSystem() string`

GetOriginSystem returns the OriginSystem field if non-nil, zero value otherwise.

### GetOriginSystemOk

`func (o *ListDocuments200ResponseDocumentsInner) GetOriginSystemOk() (*string, bool)`

GetOriginSystemOk returns a tuple with the OriginSystem field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginSystem

`func (o *ListDocuments200ResponseDocumentsInner) SetOriginSystem(v string)`

SetOriginSystem sets OriginSystem field to given value.

### HasOriginSystem

`func (o *ListDocuments200ResponseDocumentsInner) HasOriginSystem() bool`

HasOriginSystem returns a boolean if a field has been set.

### SetOriginSystemNil

`func (o *ListDocuments200ResponseDocumentsInner) SetOriginSystemNil(b bool)`

 SetOriginSystemNil sets the value for OriginSystem to be an explicit nil

### UnsetOriginSystem
`func (o *ListDocuments200ResponseDocumentsInner) UnsetOriginSystem()`

UnsetOriginSystem ensures that no value is present for OriginSystem, not even an explicit nil
### GetOwnerExternalId

`func (o *ListDocuments200ResponseDocumentsInner) GetOwnerExternalId() string`

GetOwnerExternalId returns the OwnerExternalId field if non-nil, zero value otherwise.

### GetOwnerExternalIdOk

`func (o *ListDocuments200ResponseDocumentsInner) GetOwnerExternalIdOk() (*string, bool)`

GetOwnerExternalIdOk returns a tuple with the OwnerExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerExternalId

`func (o *ListDocuments200ResponseDocumentsInner) SetOwnerExternalId(v string)`

SetOwnerExternalId sets OwnerExternalId field to given value.

### HasOwnerExternalId

`func (o *ListDocuments200ResponseDocumentsInner) HasOwnerExternalId() bool`

HasOwnerExternalId returns a boolean if a field has been set.

### SetOwnerExternalIdNil

`func (o *ListDocuments200ResponseDocumentsInner) SetOwnerExternalIdNil(b bool)`

 SetOwnerExternalIdNil sets the value for OwnerExternalId to be an explicit nil

### UnsetOwnerExternalId
`func (o *ListDocuments200ResponseDocumentsInner) UnsetOwnerExternalId()`

UnsetOwnerExternalId ensures that no value is present for OwnerExternalId, not even an explicit nil
### GetOwnerDisplayName

`func (o *ListDocuments200ResponseDocumentsInner) GetOwnerDisplayName() string`

GetOwnerDisplayName returns the OwnerDisplayName field if non-nil, zero value otherwise.

### GetOwnerDisplayNameOk

`func (o *ListDocuments200ResponseDocumentsInner) GetOwnerDisplayNameOk() (*string, bool)`

GetOwnerDisplayNameOk returns a tuple with the OwnerDisplayName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOwnerDisplayName

`func (o *ListDocuments200ResponseDocumentsInner) SetOwnerDisplayName(v string)`

SetOwnerDisplayName sets OwnerDisplayName field to given value.

### HasOwnerDisplayName

`func (o *ListDocuments200ResponseDocumentsInner) HasOwnerDisplayName() bool`

HasOwnerDisplayName returns a boolean if a field has been set.

### SetOwnerDisplayNameNil

`func (o *ListDocuments200ResponseDocumentsInner) SetOwnerDisplayNameNil(b bool)`

 SetOwnerDisplayNameNil sets the value for OwnerDisplayName to be an explicit nil

### UnsetOwnerDisplayName
`func (o *ListDocuments200ResponseDocumentsInner) UnsetOwnerDisplayName()`

UnsetOwnerDisplayName ensures that no value is present for OwnerDisplayName, not even an explicit nil
### GetContentType

`func (o *ListDocuments200ResponseDocumentsInner) GetContentType() string`

GetContentType returns the ContentType field if non-nil, zero value otherwise.

### GetContentTypeOk

`func (o *ListDocuments200ResponseDocumentsInner) GetContentTypeOk() (*string, bool)`

GetContentTypeOk returns a tuple with the ContentType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetContentType

`func (o *ListDocuments200ResponseDocumentsInner) SetContentType(v string)`

SetContentType sets ContentType field to given value.


### GetStatus

`func (o *ListDocuments200ResponseDocumentsInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ListDocuments200ResponseDocumentsInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ListDocuments200ResponseDocumentsInner) SetStatus(v string)`

SetStatus sets Status field to given value.


### GetCreatedAt

`func (o *ListDocuments200ResponseDocumentsInner) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ListDocuments200ResponseDocumentsInner) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ListDocuments200ResponseDocumentsInner) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.


### GetUpdatedAt

`func (o *ListDocuments200ResponseDocumentsInner) GetUpdatedAt() string`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *ListDocuments200ResponseDocumentsInner) GetUpdatedAtOk() (*string, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *ListDocuments200ResponseDocumentsInner) SetUpdatedAt(v string)`

SetUpdatedAt sets UpdatedAt field to given value.


### GetTripleCount

`func (o *ListDocuments200ResponseDocumentsInner) GetTripleCount() float32`

GetTripleCount returns the TripleCount field if non-nil, zero value otherwise.

### GetTripleCountOk

`func (o *ListDocuments200ResponseDocumentsInner) GetTripleCountOk() (*float32, bool)`

GetTripleCountOk returns a tuple with the TripleCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTripleCount

`func (o *ListDocuments200ResponseDocumentsInner) SetTripleCount(v float32)`

SetTripleCount sets TripleCount field to given value.

### HasTripleCount

`func (o *ListDocuments200ResponseDocumentsInner) HasTripleCount() bool`

HasTripleCount returns a boolean if a field has been set.

### GetError

`func (o *ListDocuments200ResponseDocumentsInner) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ListDocuments200ResponseDocumentsInner) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ListDocuments200ResponseDocumentsInner) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *ListDocuments200ResponseDocumentsInner) HasError() bool`

HasError returns a boolean if a field has been set.

### GetCode

`func (o *ListDocuments200ResponseDocumentsInner) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *ListDocuments200ResponseDocumentsInner) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *ListDocuments200ResponseDocumentsInner) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *ListDocuments200ResponseDocumentsInner) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetFailureMessage

`func (o *ListDocuments200ResponseDocumentsInner) GetFailureMessage() string`

GetFailureMessage returns the FailureMessage field if non-nil, zero value otherwise.

### GetFailureMessageOk

`func (o *ListDocuments200ResponseDocumentsInner) GetFailureMessageOk() (*string, bool)`

GetFailureMessageOk returns a tuple with the FailureMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureMessage

`func (o *ListDocuments200ResponseDocumentsInner) SetFailureMessage(v string)`

SetFailureMessage sets FailureMessage field to given value.

### HasFailureMessage

`func (o *ListDocuments200ResponseDocumentsInner) HasFailureMessage() bool`

HasFailureMessage returns a boolean if a field has been set.

### GetStorageUrl

`func (o *ListDocuments200ResponseDocumentsInner) GetStorageUrl() string`

GetStorageUrl returns the StorageUrl field if non-nil, zero value otherwise.

### GetStorageUrlOk

`func (o *ListDocuments200ResponseDocumentsInner) GetStorageUrlOk() (*string, bool)`

GetStorageUrlOk returns a tuple with the StorageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStorageUrl

`func (o *ListDocuments200ResponseDocumentsInner) SetStorageUrl(v string)`

SetStorageUrl sets StorageUrl field to given value.

### HasStorageUrl

`func (o *ListDocuments200ResponseDocumentsInner) HasStorageUrl() bool`

HasStorageUrl returns a boolean if a field has been set.

### GetDeletedAt

`func (o *ListDocuments200ResponseDocumentsInner) GetDeletedAt() string`

GetDeletedAt returns the DeletedAt field if non-nil, zero value otherwise.

### GetDeletedAtOk

`func (o *ListDocuments200ResponseDocumentsInner) GetDeletedAtOk() (*string, bool)`

GetDeletedAtOk returns a tuple with the DeletedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeletedAt

`func (o *ListDocuments200ResponseDocumentsInner) SetDeletedAt(v string)`

SetDeletedAt sets DeletedAt field to given value.

### HasDeletedAt

`func (o *ListDocuments200ResponseDocumentsInner) HasDeletedAt() bool`

HasDeletedAt returns a boolean if a field has been set.

### GetExtractionMethod

`func (o *ListDocuments200ResponseDocumentsInner) GetExtractionMethod() string`

GetExtractionMethod returns the ExtractionMethod field if non-nil, zero value otherwise.

### GetExtractionMethodOk

`func (o *ListDocuments200ResponseDocumentsInner) GetExtractionMethodOk() (*string, bool)`

GetExtractionMethodOk returns a tuple with the ExtractionMethod field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionMethod

`func (o *ListDocuments200ResponseDocumentsInner) SetExtractionMethod(v string)`

SetExtractionMethod sets ExtractionMethod field to given value.

### HasExtractionMethod

`func (o *ListDocuments200ResponseDocumentsInner) HasExtractionMethod() bool`

HasExtractionMethod returns a boolean if a field has been set.

### GetStructuredRegions

`func (o *ListDocuments200ResponseDocumentsInner) GetStructuredRegions() string`

GetStructuredRegions returns the StructuredRegions field if non-nil, zero value otherwise.

### GetStructuredRegionsOk

`func (o *ListDocuments200ResponseDocumentsInner) GetStructuredRegionsOk() (*string, bool)`

GetStructuredRegionsOk returns a tuple with the StructuredRegions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStructuredRegions

`func (o *ListDocuments200ResponseDocumentsInner) SetStructuredRegions(v string)`

SetStructuredRegions sets StructuredRegions field to given value.

### HasStructuredRegions

`func (o *ListDocuments200ResponseDocumentsInner) HasStructuredRegions() bool`

HasStructuredRegions returns a boolean if a field has been set.

### SetStructuredRegionsNil

`func (o *ListDocuments200ResponseDocumentsInner) SetStructuredRegionsNil(b bool)`

 SetStructuredRegionsNil sets the value for StructuredRegions to be an explicit nil

### UnsetStructuredRegions
`func (o *ListDocuments200ResponseDocumentsInner) UnsetStructuredRegions()`

UnsetStructuredRegions ensures that no value is present for StructuredRegions, not even an explicit nil
### GetProvenanceChain

`func (o *ListDocuments200ResponseDocumentsInner) GetProvenanceChain() string`

GetProvenanceChain returns the ProvenanceChain field if non-nil, zero value otherwise.

### GetProvenanceChainOk

`func (o *ListDocuments200ResponseDocumentsInner) GetProvenanceChainOk() (*string, bool)`

GetProvenanceChainOk returns a tuple with the ProvenanceChain field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProvenanceChain

`func (o *ListDocuments200ResponseDocumentsInner) SetProvenanceChain(v string)`

SetProvenanceChain sets ProvenanceChain field to given value.

### HasProvenanceChain

`func (o *ListDocuments200ResponseDocumentsInner) HasProvenanceChain() bool`

HasProvenanceChain returns a boolean if a field has been set.

### SetProvenanceChainNil

`func (o *ListDocuments200ResponseDocumentsInner) SetProvenanceChainNil(b bool)`

 SetProvenanceChainNil sets the value for ProvenanceChain to be an explicit nil

### UnsetProvenanceChain
`func (o *ListDocuments200ResponseDocumentsInner) UnsetProvenanceChain()`

UnsetProvenanceChain ensures that no value is present for ProvenanceChain, not even an explicit nil
### GetExtractionStats

`func (o *ListDocuments200ResponseDocumentsInner) GetExtractionStats() string`

GetExtractionStats returns the ExtractionStats field if non-nil, zero value otherwise.

### GetExtractionStatsOk

`func (o *ListDocuments200ResponseDocumentsInner) GetExtractionStatsOk() (*string, bool)`

GetExtractionStatsOk returns a tuple with the ExtractionStats field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionStats

`func (o *ListDocuments200ResponseDocumentsInner) SetExtractionStats(v string)`

SetExtractionStats sets ExtractionStats field to given value.

### HasExtractionStats

`func (o *ListDocuments200ResponseDocumentsInner) HasExtractionStats() bool`

HasExtractionStats returns a boolean if a field has been set.

### SetExtractionStatsNil

`func (o *ListDocuments200ResponseDocumentsInner) SetExtractionStatsNil(b bool)`

 SetExtractionStatsNil sets the value for ExtractionStats to be an explicit nil

### UnsetExtractionStats
`func (o *ListDocuments200ResponseDocumentsInner) UnsetExtractionStats()`

UnsetExtractionStats ensures that no value is present for ExtractionStats, not even an explicit nil
### GetProcessingSummary

`func (o *ListDocuments200ResponseDocumentsInner) GetProcessingSummary() string`

GetProcessingSummary returns the ProcessingSummary field if non-nil, zero value otherwise.

### GetProcessingSummaryOk

`func (o *ListDocuments200ResponseDocumentsInner) GetProcessingSummaryOk() (*string, bool)`

GetProcessingSummaryOk returns a tuple with the ProcessingSummary field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProcessingSummary

`func (o *ListDocuments200ResponseDocumentsInner) SetProcessingSummary(v string)`

SetProcessingSummary sets ProcessingSummary field to given value.

### HasProcessingSummary

`func (o *ListDocuments200ResponseDocumentsInner) HasProcessingSummary() bool`

HasProcessingSummary returns a boolean if a field has been set.

### SetProcessingSummaryNil

`func (o *ListDocuments200ResponseDocumentsInner) SetProcessingSummaryNil(b bool)`

 SetProcessingSummaryNil sets the value for ProcessingSummary to be an explicit nil

### UnsetProcessingSummary
`func (o *ListDocuments200ResponseDocumentsInner) UnsetProcessingSummary()`

UnsetProcessingSummary ensures that no value is present for ProcessingSummary, not even an explicit nil
### GetModelUsed

`func (o *ListDocuments200ResponseDocumentsInner) GetModelUsed() string`

GetModelUsed returns the ModelUsed field if non-nil, zero value otherwise.

### GetModelUsedOk

`func (o *ListDocuments200ResponseDocumentsInner) GetModelUsedOk() (*string, bool)`

GetModelUsedOk returns a tuple with the ModelUsed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetModelUsed

`func (o *ListDocuments200ResponseDocumentsInner) SetModelUsed(v string)`

SetModelUsed sets ModelUsed field to given value.

### HasModelUsed

`func (o *ListDocuments200ResponseDocumentsInner) HasModelUsed() bool`

HasModelUsed returns a boolean if a field has been set.

### SetModelUsedNil

`func (o *ListDocuments200ResponseDocumentsInner) SetModelUsedNil(b bool)`

 SetModelUsedNil sets the value for ModelUsed to be an explicit nil

### UnsetModelUsed
`func (o *ListDocuments200ResponseDocumentsInner) UnsetModelUsed()`

UnsetModelUsed ensures that no value is present for ModelUsed, not even an explicit nil
### GetOcrStrategy

`func (o *ListDocuments200ResponseDocumentsInner) GetOcrStrategy() string`

GetOcrStrategy returns the OcrStrategy field if non-nil, zero value otherwise.

### GetOcrStrategyOk

`func (o *ListDocuments200ResponseDocumentsInner) GetOcrStrategyOk() (*string, bool)`

GetOcrStrategyOk returns a tuple with the OcrStrategy field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOcrStrategy

`func (o *ListDocuments200ResponseDocumentsInner) SetOcrStrategy(v string)`

SetOcrStrategy sets OcrStrategy field to given value.

### HasOcrStrategy

`func (o *ListDocuments200ResponseDocumentsInner) HasOcrStrategy() bool`

HasOcrStrategy returns a boolean if a field has been set.

### SetOcrStrategyNil

`func (o *ListDocuments200ResponseDocumentsInner) SetOcrStrategyNil(b bool)`

 SetOcrStrategyNil sets the value for OcrStrategy to be an explicit nil

### UnsetOcrStrategy
`func (o *ListDocuments200ResponseDocumentsInner) UnsetOcrStrategy()`

UnsetOcrStrategy ensures that no value is present for OcrStrategy, not even an explicit nil
### GetInferenceMode

`func (o *ListDocuments200ResponseDocumentsInner) GetInferenceMode() string`

GetInferenceMode returns the InferenceMode field if non-nil, zero value otherwise.

### GetInferenceModeOk

`func (o *ListDocuments200ResponseDocumentsInner) GetInferenceModeOk() (*string, bool)`

GetInferenceModeOk returns a tuple with the InferenceMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInferenceMode

`func (o *ListDocuments200ResponseDocumentsInner) SetInferenceMode(v string)`

SetInferenceMode sets InferenceMode field to given value.

### HasInferenceMode

`func (o *ListDocuments200ResponseDocumentsInner) HasInferenceMode() bool`

HasInferenceMode returns a boolean if a field has been set.

### SetInferenceModeNil

`func (o *ListDocuments200ResponseDocumentsInner) SetInferenceModeNil(b bool)`

 SetInferenceModeNil sets the value for InferenceMode to be an explicit nil

### UnsetInferenceMode
`func (o *ListDocuments200ResponseDocumentsInner) UnsetInferenceMode()`

UnsetInferenceMode ensures that no value is present for InferenceMode, not even an explicit nil
### GetExtractionGuidanceRevision

`func (o *ListDocuments200ResponseDocumentsInner) GetExtractionGuidanceRevision() int32`

GetExtractionGuidanceRevision returns the ExtractionGuidanceRevision field if non-nil, zero value otherwise.

### GetExtractionGuidanceRevisionOk

`func (o *ListDocuments200ResponseDocumentsInner) GetExtractionGuidanceRevisionOk() (*int32, bool)`

GetExtractionGuidanceRevisionOk returns a tuple with the ExtractionGuidanceRevision field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionGuidanceRevision

`func (o *ListDocuments200ResponseDocumentsInner) SetExtractionGuidanceRevision(v int32)`

SetExtractionGuidanceRevision sets ExtractionGuidanceRevision field to given value.

### HasExtractionGuidanceRevision

`func (o *ListDocuments200ResponseDocumentsInner) HasExtractionGuidanceRevision() bool`

HasExtractionGuidanceRevision returns a boolean if a field has been set.

### SetExtractionGuidanceRevisionNil

`func (o *ListDocuments200ResponseDocumentsInner) SetExtractionGuidanceRevisionNil(b bool)`

 SetExtractionGuidanceRevisionNil sets the value for ExtractionGuidanceRevision to be an explicit nil

### UnsetExtractionGuidanceRevision
`func (o *ListDocuments200ResponseDocumentsInner) UnsetExtractionGuidanceRevision()`

UnsetExtractionGuidanceRevision ensures that no value is present for ExtractionGuidanceRevision, not even an explicit nil
### GetGuidanceRecommendations

`func (o *ListDocuments200ResponseDocumentsInner) GetGuidanceRecommendations() string`

GetGuidanceRecommendations returns the GuidanceRecommendations field if non-nil, zero value otherwise.

### GetGuidanceRecommendationsOk

`func (o *ListDocuments200ResponseDocumentsInner) GetGuidanceRecommendationsOk() (*string, bool)`

GetGuidanceRecommendationsOk returns a tuple with the GuidanceRecommendations field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGuidanceRecommendations

`func (o *ListDocuments200ResponseDocumentsInner) SetGuidanceRecommendations(v string)`

SetGuidanceRecommendations sets GuidanceRecommendations field to given value.

### HasGuidanceRecommendations

`func (o *ListDocuments200ResponseDocumentsInner) HasGuidanceRecommendations() bool`

HasGuidanceRecommendations returns a boolean if a field has been set.

### SetGuidanceRecommendationsNil

`func (o *ListDocuments200ResponseDocumentsInner) SetGuidanceRecommendationsNil(b bool)`

 SetGuidanceRecommendationsNil sets the value for GuidanceRecommendations to be an explicit nil

### UnsetGuidanceRecommendations
`func (o *ListDocuments200ResponseDocumentsInner) UnsetGuidanceRecommendations()`

UnsetGuidanceRecommendations ensures that no value is present for GuidanceRecommendations, not even an explicit nil
### GetSourceCreatedAt

`func (o *ListDocuments200ResponseDocumentsInner) GetSourceCreatedAt() string`

GetSourceCreatedAt returns the SourceCreatedAt field if non-nil, zero value otherwise.

### GetSourceCreatedAtOk

`func (o *ListDocuments200ResponseDocumentsInner) GetSourceCreatedAtOk() (*string, bool)`

GetSourceCreatedAtOk returns a tuple with the SourceCreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceCreatedAt

`func (o *ListDocuments200ResponseDocumentsInner) SetSourceCreatedAt(v string)`

SetSourceCreatedAt sets SourceCreatedAt field to given value.

### HasSourceCreatedAt

`func (o *ListDocuments200ResponseDocumentsInner) HasSourceCreatedAt() bool`

HasSourceCreatedAt returns a boolean if a field has been set.

### SetSourceCreatedAtNil

`func (o *ListDocuments200ResponseDocumentsInner) SetSourceCreatedAtNil(b bool)`

 SetSourceCreatedAtNil sets the value for SourceCreatedAt to be an explicit nil

### UnsetSourceCreatedAt
`func (o *ListDocuments200ResponseDocumentsInner) UnsetSourceCreatedAt()`

UnsetSourceCreatedAt ensures that no value is present for SourceCreatedAt, not even an explicit nil
### GetSourceModifiedAt

`func (o *ListDocuments200ResponseDocumentsInner) GetSourceModifiedAt() string`

GetSourceModifiedAt returns the SourceModifiedAt field if non-nil, zero value otherwise.

### GetSourceModifiedAtOk

`func (o *ListDocuments200ResponseDocumentsInner) GetSourceModifiedAtOk() (*string, bool)`

GetSourceModifiedAtOk returns a tuple with the SourceModifiedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceModifiedAt

`func (o *ListDocuments200ResponseDocumentsInner) SetSourceModifiedAt(v string)`

SetSourceModifiedAt sets SourceModifiedAt field to given value.

### HasSourceModifiedAt

`func (o *ListDocuments200ResponseDocumentsInner) HasSourceModifiedAt() bool`

HasSourceModifiedAt returns a boolean if a field has been set.

### SetSourceModifiedAtNil

`func (o *ListDocuments200ResponseDocumentsInner) SetSourceModifiedAtNil(b bool)`

 SetSourceModifiedAtNil sets the value for SourceModifiedAt to be an explicit nil

### UnsetSourceModifiedAt
`func (o *ListDocuments200ResponseDocumentsInner) UnsetSourceModifiedAt()`

UnsetSourceModifiedAt ensures that no value is present for SourceModifiedAt, not even an explicit nil
### GetSourceAuthor

`func (o *ListDocuments200ResponseDocumentsInner) GetSourceAuthor() string`

GetSourceAuthor returns the SourceAuthor field if non-nil, zero value otherwise.

### GetSourceAuthorOk

`func (o *ListDocuments200ResponseDocumentsInner) GetSourceAuthorOk() (*string, bool)`

GetSourceAuthorOk returns a tuple with the SourceAuthor field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceAuthor

`func (o *ListDocuments200ResponseDocumentsInner) SetSourceAuthor(v string)`

SetSourceAuthor sets SourceAuthor field to given value.

### HasSourceAuthor

`func (o *ListDocuments200ResponseDocumentsInner) HasSourceAuthor() bool`

HasSourceAuthor returns a boolean if a field has been set.

### SetSourceAuthorNil

`func (o *ListDocuments200ResponseDocumentsInner) SetSourceAuthorNil(b bool)`

 SetSourceAuthorNil sets the value for SourceAuthor to be an explicit nil

### UnsetSourceAuthor
`func (o *ListDocuments200ResponseDocumentsInner) UnsetSourceAuthor()`

UnsetSourceAuthor ensures that no value is present for SourceAuthor, not even an explicit nil
### GetSourceMetadata

`func (o *ListDocuments200ResponseDocumentsInner) GetSourceMetadata() string`

GetSourceMetadata returns the SourceMetadata field if non-nil, zero value otherwise.

### GetSourceMetadataOk

`func (o *ListDocuments200ResponseDocumentsInner) GetSourceMetadataOk() (*string, bool)`

GetSourceMetadataOk returns a tuple with the SourceMetadata field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSourceMetadata

`func (o *ListDocuments200ResponseDocumentsInner) SetSourceMetadata(v string)`

SetSourceMetadata sets SourceMetadata field to given value.

### HasSourceMetadata

`func (o *ListDocuments200ResponseDocumentsInner) HasSourceMetadata() bool`

HasSourceMetadata returns a boolean if a field has been set.

### SetSourceMetadataNil

`func (o *ListDocuments200ResponseDocumentsInner) SetSourceMetadataNil(b bool)`

 SetSourceMetadataNil sets the value for SourceMetadata to be an explicit nil

### UnsetSourceMetadata
`func (o *ListDocuments200ResponseDocumentsInner) UnsetSourceMetadata()`

UnsetSourceMetadata ensures that no value is present for SourceMetadata, not even an explicit nil
### GetProjectExternalId

`func (o *ListDocuments200ResponseDocumentsInner) GetProjectExternalId() string`

GetProjectExternalId returns the ProjectExternalId field if non-nil, zero value otherwise.

### GetProjectExternalIdOk

`func (o *ListDocuments200ResponseDocumentsInner) GetProjectExternalIdOk() (*string, bool)`

GetProjectExternalIdOk returns a tuple with the ProjectExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProjectExternalId

`func (o *ListDocuments200ResponseDocumentsInner) SetProjectExternalId(v string)`

SetProjectExternalId sets ProjectExternalId field to given value.

### HasProjectExternalId

`func (o *ListDocuments200ResponseDocumentsInner) HasProjectExternalId() bool`

HasProjectExternalId returns a boolean if a field has been set.

### SetProjectExternalIdNil

`func (o *ListDocuments200ResponseDocumentsInner) SetProjectExternalIdNil(b bool)`

 SetProjectExternalIdNil sets the value for ProjectExternalId to be an explicit nil

### UnsetProjectExternalId
`func (o *ListDocuments200ResponseDocumentsInner) UnsetProjectExternalId()`

UnsetProjectExternalId ensures that no value is present for ProjectExternalId, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


