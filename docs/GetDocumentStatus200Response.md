# GetDocumentStatus200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DocumentId** | **string** |  | 
**Step** | Pointer to **string** |  | [optional] 
**Progress** | **float32** |  | 
**Message** | Pointer to **string** |  | [optional] 
**Paused** | Pointer to **bool** |  | [optional] 
**Completed** | **bool** |  | 
**Failed** | **bool** |  | 
**Stored** | Pointer to **bool** |  | [optional] 
**AwaitingOntologyReview** | Pointer to **bool** |  | [optional] 
**OntologyReviewId** | Pointer to **string** |  | [optional] 
**OntologyProposalCount** | Pointer to **float32** |  | [optional] 
**Error** | Pointer to **string** |  | [optional] 
**Code** | Pointer to **string** |  | [optional] 
**FailureMessage** | Pointer to **string** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**WorkflowError** | Pointer to **string** |  | [optional] 
**Retryable** | Pointer to **bool** |  | [optional] 
**TriplesExtracted** | Pointer to **float32** |  | [optional] 
**InputTokens** | Pointer to **float32** |  | [optional] 
**OutputTokens** | Pointer to **float32** |  | [optional] 
**ExtractionTier** | Pointer to **string** |  | [optional] 
**ExtractionMode** | Pointer to **string** |  | [optional] 
**EstimatedRemainingMs** | Pointer to **float32** |  | [optional] 
**Steps** | Pointer to [**[]GetDocumentStatus200ResponseStepsInner**](GetDocumentStatus200ResponseStepsInner.md) |  | [optional] 
**Stages** | Pointer to [**[]GetDocumentStatus200ResponseStepsInner**](GetDocumentStatus200ResponseStepsInner.md) |  | [optional] 
**InvocationId** | Pointer to **string** |  | [optional] 
**UpdatedAt** | **float32** |  | 

## Methods

### NewGetDocumentStatus200Response

`func NewGetDocumentStatus200Response(documentId string, progress float32, completed bool, failed bool, updatedAt float32, ) *GetDocumentStatus200Response`

NewGetDocumentStatus200Response instantiates a new GetDocumentStatus200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewGetDocumentStatus200ResponseWithDefaults

`func NewGetDocumentStatus200ResponseWithDefaults() *GetDocumentStatus200Response`

NewGetDocumentStatus200ResponseWithDefaults instantiates a new GetDocumentStatus200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDocumentId

`func (o *GetDocumentStatus200Response) GetDocumentId() string`

GetDocumentId returns the DocumentId field if non-nil, zero value otherwise.

### GetDocumentIdOk

`func (o *GetDocumentStatus200Response) GetDocumentIdOk() (*string, bool)`

GetDocumentIdOk returns a tuple with the DocumentId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDocumentId

`func (o *GetDocumentStatus200Response) SetDocumentId(v string)`

SetDocumentId sets DocumentId field to given value.


### GetStep

`func (o *GetDocumentStatus200Response) GetStep() string`

GetStep returns the Step field if non-nil, zero value otherwise.

### GetStepOk

`func (o *GetDocumentStatus200Response) GetStepOk() (*string, bool)`

GetStepOk returns a tuple with the Step field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStep

`func (o *GetDocumentStatus200Response) SetStep(v string)`

SetStep sets Step field to given value.

### HasStep

`func (o *GetDocumentStatus200Response) HasStep() bool`

HasStep returns a boolean if a field has been set.

### GetProgress

`func (o *GetDocumentStatus200Response) GetProgress() float32`

GetProgress returns the Progress field if non-nil, zero value otherwise.

### GetProgressOk

`func (o *GetDocumentStatus200Response) GetProgressOk() (*float32, bool)`

GetProgressOk returns a tuple with the Progress field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProgress

`func (o *GetDocumentStatus200Response) SetProgress(v float32)`

SetProgress sets Progress field to given value.


### GetMessage

`func (o *GetDocumentStatus200Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *GetDocumentStatus200Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *GetDocumentStatus200Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *GetDocumentStatus200Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetPaused

`func (o *GetDocumentStatus200Response) GetPaused() bool`

GetPaused returns the Paused field if non-nil, zero value otherwise.

### GetPausedOk

`func (o *GetDocumentStatus200Response) GetPausedOk() (*bool, bool)`

GetPausedOk returns a tuple with the Paused field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPaused

`func (o *GetDocumentStatus200Response) SetPaused(v bool)`

SetPaused sets Paused field to given value.

### HasPaused

`func (o *GetDocumentStatus200Response) HasPaused() bool`

HasPaused returns a boolean if a field has been set.

### GetCompleted

`func (o *GetDocumentStatus200Response) GetCompleted() bool`

GetCompleted returns the Completed field if non-nil, zero value otherwise.

### GetCompletedOk

`func (o *GetDocumentStatus200Response) GetCompletedOk() (*bool, bool)`

GetCompletedOk returns a tuple with the Completed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCompleted

`func (o *GetDocumentStatus200Response) SetCompleted(v bool)`

SetCompleted sets Completed field to given value.


### GetFailed

`func (o *GetDocumentStatus200Response) GetFailed() bool`

GetFailed returns the Failed field if non-nil, zero value otherwise.

### GetFailedOk

`func (o *GetDocumentStatus200Response) GetFailedOk() (*bool, bool)`

GetFailedOk returns a tuple with the Failed field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailed

`func (o *GetDocumentStatus200Response) SetFailed(v bool)`

SetFailed sets Failed field to given value.


### GetStored

`func (o *GetDocumentStatus200Response) GetStored() bool`

GetStored returns the Stored field if non-nil, zero value otherwise.

### GetStoredOk

`func (o *GetDocumentStatus200Response) GetStoredOk() (*bool, bool)`

GetStoredOk returns a tuple with the Stored field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStored

`func (o *GetDocumentStatus200Response) SetStored(v bool)`

SetStored sets Stored field to given value.

### HasStored

`func (o *GetDocumentStatus200Response) HasStored() bool`

HasStored returns a boolean if a field has been set.

### GetAwaitingOntologyReview

`func (o *GetDocumentStatus200Response) GetAwaitingOntologyReview() bool`

GetAwaitingOntologyReview returns the AwaitingOntologyReview field if non-nil, zero value otherwise.

### GetAwaitingOntologyReviewOk

`func (o *GetDocumentStatus200Response) GetAwaitingOntologyReviewOk() (*bool, bool)`

GetAwaitingOntologyReviewOk returns a tuple with the AwaitingOntologyReview field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAwaitingOntologyReview

`func (o *GetDocumentStatus200Response) SetAwaitingOntologyReview(v bool)`

SetAwaitingOntologyReview sets AwaitingOntologyReview field to given value.

### HasAwaitingOntologyReview

`func (o *GetDocumentStatus200Response) HasAwaitingOntologyReview() bool`

HasAwaitingOntologyReview returns a boolean if a field has been set.

### GetOntologyReviewId

`func (o *GetDocumentStatus200Response) GetOntologyReviewId() string`

GetOntologyReviewId returns the OntologyReviewId field if non-nil, zero value otherwise.

### GetOntologyReviewIdOk

`func (o *GetDocumentStatus200Response) GetOntologyReviewIdOk() (*string, bool)`

GetOntologyReviewIdOk returns a tuple with the OntologyReviewId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOntologyReviewId

`func (o *GetDocumentStatus200Response) SetOntologyReviewId(v string)`

SetOntologyReviewId sets OntologyReviewId field to given value.

### HasOntologyReviewId

`func (o *GetDocumentStatus200Response) HasOntologyReviewId() bool`

HasOntologyReviewId returns a boolean if a field has been set.

### GetOntologyProposalCount

`func (o *GetDocumentStatus200Response) GetOntologyProposalCount() float32`

GetOntologyProposalCount returns the OntologyProposalCount field if non-nil, zero value otherwise.

### GetOntologyProposalCountOk

`func (o *GetDocumentStatus200Response) GetOntologyProposalCountOk() (*float32, bool)`

GetOntologyProposalCountOk returns a tuple with the OntologyProposalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOntologyProposalCount

`func (o *GetDocumentStatus200Response) SetOntologyProposalCount(v float32)`

SetOntologyProposalCount sets OntologyProposalCount field to given value.

### HasOntologyProposalCount

`func (o *GetDocumentStatus200Response) HasOntologyProposalCount() bool`

HasOntologyProposalCount returns a boolean if a field has been set.

### GetError

`func (o *GetDocumentStatus200Response) GetError() string`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *GetDocumentStatus200Response) GetErrorOk() (*string, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *GetDocumentStatus200Response) SetError(v string)`

SetError sets Error field to given value.

### HasError

`func (o *GetDocumentStatus200Response) HasError() bool`

HasError returns a boolean if a field has been set.

### GetCode

`func (o *GetDocumentStatus200Response) GetCode() string`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *GetDocumentStatus200Response) GetCodeOk() (*string, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *GetDocumentStatus200Response) SetCode(v string)`

SetCode sets Code field to given value.

### HasCode

`func (o *GetDocumentStatus200Response) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetFailureMessage

`func (o *GetDocumentStatus200Response) GetFailureMessage() string`

GetFailureMessage returns the FailureMessage field if non-nil, zero value otherwise.

### GetFailureMessageOk

`func (o *GetDocumentStatus200Response) GetFailureMessageOk() (*string, bool)`

GetFailureMessageOk returns a tuple with the FailureMessage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFailureMessage

`func (o *GetDocumentStatus200Response) SetFailureMessage(v string)`

SetFailureMessage sets FailureMessage field to given value.

### HasFailureMessage

`func (o *GetDocumentStatus200Response) HasFailureMessage() bool`

HasFailureMessage returns a boolean if a field has been set.

### GetStatus

`func (o *GetDocumentStatus200Response) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *GetDocumentStatus200Response) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *GetDocumentStatus200Response) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *GetDocumentStatus200Response) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetWorkflowError

`func (o *GetDocumentStatus200Response) GetWorkflowError() string`

GetWorkflowError returns the WorkflowError field if non-nil, zero value otherwise.

### GetWorkflowErrorOk

`func (o *GetDocumentStatus200Response) GetWorkflowErrorOk() (*string, bool)`

GetWorkflowErrorOk returns a tuple with the WorkflowError field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetWorkflowError

`func (o *GetDocumentStatus200Response) SetWorkflowError(v string)`

SetWorkflowError sets WorkflowError field to given value.

### HasWorkflowError

`func (o *GetDocumentStatus200Response) HasWorkflowError() bool`

HasWorkflowError returns a boolean if a field has been set.

### GetRetryable

`func (o *GetDocumentStatus200Response) GetRetryable() bool`

GetRetryable returns the Retryable field if non-nil, zero value otherwise.

### GetRetryableOk

`func (o *GetDocumentStatus200Response) GetRetryableOk() (*bool, bool)`

GetRetryableOk returns a tuple with the Retryable field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRetryable

`func (o *GetDocumentStatus200Response) SetRetryable(v bool)`

SetRetryable sets Retryable field to given value.

### HasRetryable

`func (o *GetDocumentStatus200Response) HasRetryable() bool`

HasRetryable returns a boolean if a field has been set.

### GetTriplesExtracted

`func (o *GetDocumentStatus200Response) GetTriplesExtracted() float32`

GetTriplesExtracted returns the TriplesExtracted field if non-nil, zero value otherwise.

### GetTriplesExtractedOk

`func (o *GetDocumentStatus200Response) GetTriplesExtractedOk() (*float32, bool)`

GetTriplesExtractedOk returns a tuple with the TriplesExtracted field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriplesExtracted

`func (o *GetDocumentStatus200Response) SetTriplesExtracted(v float32)`

SetTriplesExtracted sets TriplesExtracted field to given value.

### HasTriplesExtracted

`func (o *GetDocumentStatus200Response) HasTriplesExtracted() bool`

HasTriplesExtracted returns a boolean if a field has been set.

### GetInputTokens

`func (o *GetDocumentStatus200Response) GetInputTokens() float32`

GetInputTokens returns the InputTokens field if non-nil, zero value otherwise.

### GetInputTokensOk

`func (o *GetDocumentStatus200Response) GetInputTokensOk() (*float32, bool)`

GetInputTokensOk returns a tuple with the InputTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInputTokens

`func (o *GetDocumentStatus200Response) SetInputTokens(v float32)`

SetInputTokens sets InputTokens field to given value.

### HasInputTokens

`func (o *GetDocumentStatus200Response) HasInputTokens() bool`

HasInputTokens returns a boolean if a field has been set.

### GetOutputTokens

`func (o *GetDocumentStatus200Response) GetOutputTokens() float32`

GetOutputTokens returns the OutputTokens field if non-nil, zero value otherwise.

### GetOutputTokensOk

`func (o *GetDocumentStatus200Response) GetOutputTokensOk() (*float32, bool)`

GetOutputTokensOk returns a tuple with the OutputTokens field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOutputTokens

`func (o *GetDocumentStatus200Response) SetOutputTokens(v float32)`

SetOutputTokens sets OutputTokens field to given value.

### HasOutputTokens

`func (o *GetDocumentStatus200Response) HasOutputTokens() bool`

HasOutputTokens returns a boolean if a field has been set.

### GetExtractionTier

`func (o *GetDocumentStatus200Response) GetExtractionTier() string`

GetExtractionTier returns the ExtractionTier field if non-nil, zero value otherwise.

### GetExtractionTierOk

`func (o *GetDocumentStatus200Response) GetExtractionTierOk() (*string, bool)`

GetExtractionTierOk returns a tuple with the ExtractionTier field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionTier

`func (o *GetDocumentStatus200Response) SetExtractionTier(v string)`

SetExtractionTier sets ExtractionTier field to given value.

### HasExtractionTier

`func (o *GetDocumentStatus200Response) HasExtractionTier() bool`

HasExtractionTier returns a boolean if a field has been set.

### GetExtractionMode

`func (o *GetDocumentStatus200Response) GetExtractionMode() string`

GetExtractionMode returns the ExtractionMode field if non-nil, zero value otherwise.

### GetExtractionModeOk

`func (o *GetDocumentStatus200Response) GetExtractionModeOk() (*string, bool)`

GetExtractionModeOk returns a tuple with the ExtractionMode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExtractionMode

`func (o *GetDocumentStatus200Response) SetExtractionMode(v string)`

SetExtractionMode sets ExtractionMode field to given value.

### HasExtractionMode

`func (o *GetDocumentStatus200Response) HasExtractionMode() bool`

HasExtractionMode returns a boolean if a field has been set.

### GetEstimatedRemainingMs

`func (o *GetDocumentStatus200Response) GetEstimatedRemainingMs() float32`

GetEstimatedRemainingMs returns the EstimatedRemainingMs field if non-nil, zero value otherwise.

### GetEstimatedRemainingMsOk

`func (o *GetDocumentStatus200Response) GetEstimatedRemainingMsOk() (*float32, bool)`

GetEstimatedRemainingMsOk returns a tuple with the EstimatedRemainingMs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetEstimatedRemainingMs

`func (o *GetDocumentStatus200Response) SetEstimatedRemainingMs(v float32)`

SetEstimatedRemainingMs sets EstimatedRemainingMs field to given value.

### HasEstimatedRemainingMs

`func (o *GetDocumentStatus200Response) HasEstimatedRemainingMs() bool`

HasEstimatedRemainingMs returns a boolean if a field has been set.

### GetSteps

`func (o *GetDocumentStatus200Response) GetSteps() []GetDocumentStatus200ResponseStepsInner`

GetSteps returns the Steps field if non-nil, zero value otherwise.

### GetStepsOk

`func (o *GetDocumentStatus200Response) GetStepsOk() (*[]GetDocumentStatus200ResponseStepsInner, bool)`

GetStepsOk returns a tuple with the Steps field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSteps

`func (o *GetDocumentStatus200Response) SetSteps(v []GetDocumentStatus200ResponseStepsInner)`

SetSteps sets Steps field to given value.

### HasSteps

`func (o *GetDocumentStatus200Response) HasSteps() bool`

HasSteps returns a boolean if a field has been set.

### GetStages

`func (o *GetDocumentStatus200Response) GetStages() []GetDocumentStatus200ResponseStepsInner`

GetStages returns the Stages field if non-nil, zero value otherwise.

### GetStagesOk

`func (o *GetDocumentStatus200Response) GetStagesOk() (*[]GetDocumentStatus200ResponseStepsInner, bool)`

GetStagesOk returns a tuple with the Stages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStages

`func (o *GetDocumentStatus200Response) SetStages(v []GetDocumentStatus200ResponseStepsInner)`

SetStages sets Stages field to given value.

### HasStages

`func (o *GetDocumentStatus200Response) HasStages() bool`

HasStages returns a boolean if a field has been set.

### GetInvocationId

`func (o *GetDocumentStatus200Response) GetInvocationId() string`

GetInvocationId returns the InvocationId field if non-nil, zero value otherwise.

### GetInvocationIdOk

`func (o *GetDocumentStatus200Response) GetInvocationIdOk() (*string, bool)`

GetInvocationIdOk returns a tuple with the InvocationId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInvocationId

`func (o *GetDocumentStatus200Response) SetInvocationId(v string)`

SetInvocationId sets InvocationId field to given value.

### HasInvocationId

`func (o *GetDocumentStatus200Response) HasInvocationId() bool`

HasInvocationId returns a boolean if a field has been set.

### GetUpdatedAt

`func (o *GetDocumentStatus200Response) GetUpdatedAt() float32`

GetUpdatedAt returns the UpdatedAt field if non-nil, zero value otherwise.

### GetUpdatedAtOk

`func (o *GetDocumentStatus200Response) GetUpdatedAtOk() (*float32, bool)`

GetUpdatedAtOk returns a tuple with the UpdatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetUpdatedAt

`func (o *GetDocumentStatus200Response) SetUpdatedAt(v float32)`

SetUpdatedAt sets UpdatedAt field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


