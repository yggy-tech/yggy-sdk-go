# ListDocumentTriples200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Triples** | [**[]ListDocumentTriples200ResponseTriplesInner**](ListDocumentTriples200ResponseTriplesInner.md) |  | 
**Count** | **float32** |  | 

## Methods

### NewListDocumentTriples200Response

`func NewListDocumentTriples200Response(triples []ListDocumentTriples200ResponseTriplesInner, count float32, ) *ListDocumentTriples200Response`

NewListDocumentTriples200Response instantiates a new ListDocumentTriples200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewListDocumentTriples200ResponseWithDefaults

`func NewListDocumentTriples200ResponseWithDefaults() *ListDocumentTriples200Response`

NewListDocumentTriples200ResponseWithDefaults instantiates a new ListDocumentTriples200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTriples

`func (o *ListDocumentTriples200Response) GetTriples() []ListDocumentTriples200ResponseTriplesInner`

GetTriples returns the Triples field if non-nil, zero value otherwise.

### GetTriplesOk

`func (o *ListDocumentTriples200Response) GetTriplesOk() (*[]ListDocumentTriples200ResponseTriplesInner, bool)`

GetTriplesOk returns a tuple with the Triples field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTriples

`func (o *ListDocumentTriples200Response) SetTriples(v []ListDocumentTriples200ResponseTriplesInner)`

SetTriples sets Triples field to given value.


### GetCount

`func (o *ListDocumentTriples200Response) GetCount() float32`

GetCount returns the Count field if non-nil, zero value otherwise.

### GetCountOk

`func (o *ListDocumentTriples200Response) GetCountOk() (*float32, bool)`

GetCountOk returns a tuple with the Count field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCount

`func (o *ListDocumentTriples200Response) SetCount(v float32)`

SetCount sets Count field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


