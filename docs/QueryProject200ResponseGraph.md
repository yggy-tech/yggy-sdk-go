# QueryProject200ResponseGraph

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Hops** | **int32** | Hops followed. 0 in &#x60;lexical&#x60; mode. | 
**Seeds** | **int32** | Entities the walk started from | 
**Reached** | [**QueryProject200ResponseGraphReached**](QueryProject200ResponseGraphReached.md) |  | 
**Truncated** | **bool** | True when a limit or the time budget stopped the walk early. The result is still returned. | 

## Methods

### NewQueryProject200ResponseGraph

`func NewQueryProject200ResponseGraph(hops int32, seeds int32, reached QueryProject200ResponseGraphReached, truncated bool, ) *QueryProject200ResponseGraph`

NewQueryProject200ResponseGraph instantiates a new QueryProject200ResponseGraph object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewQueryProject200ResponseGraphWithDefaults

`func NewQueryProject200ResponseGraphWithDefaults() *QueryProject200ResponseGraph`

NewQueryProject200ResponseGraphWithDefaults instantiates a new QueryProject200ResponseGraph object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetHops

`func (o *QueryProject200ResponseGraph) GetHops() int32`

GetHops returns the Hops field if non-nil, zero value otherwise.

### GetHopsOk

`func (o *QueryProject200ResponseGraph) GetHopsOk() (*int32, bool)`

GetHopsOk returns a tuple with the Hops field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHops

`func (o *QueryProject200ResponseGraph) SetHops(v int32)`

SetHops sets Hops field to given value.


### GetSeeds

`func (o *QueryProject200ResponseGraph) GetSeeds() int32`

GetSeeds returns the Seeds field if non-nil, zero value otherwise.

### GetSeedsOk

`func (o *QueryProject200ResponseGraph) GetSeedsOk() (*int32, bool)`

GetSeedsOk returns a tuple with the Seeds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSeeds

`func (o *QueryProject200ResponseGraph) SetSeeds(v int32)`

SetSeeds sets Seeds field to given value.


### GetReached

`func (o *QueryProject200ResponseGraph) GetReached() QueryProject200ResponseGraphReached`

GetReached returns the Reached field if non-nil, zero value otherwise.

### GetReachedOk

`func (o *QueryProject200ResponseGraph) GetReachedOk() (*QueryProject200ResponseGraphReached, bool)`

GetReachedOk returns a tuple with the Reached field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReached

`func (o *QueryProject200ResponseGraph) SetReached(v QueryProject200ResponseGraphReached)`

SetReached sets Reached field to given value.


### GetTruncated

`func (o *QueryProject200ResponseGraph) GetTruncated() bool`

GetTruncated returns the Truncated field if non-nil, zero value otherwise.

### GetTruncatedOk

`func (o *QueryProject200ResponseGraph) GetTruncatedOk() (*bool, bool)`

GetTruncatedOk returns a tuple with the Truncated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTruncated

`func (o *QueryProject200ResponseGraph) SetTruncated(v bool)`

SetTruncated sets Truncated field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


