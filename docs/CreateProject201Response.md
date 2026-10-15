# CreateProject201Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Success** | **bool** |  | 
**Project** | [**CreateProject201ResponseProject**](CreateProject201ResponseProject.md) |  | 

## Methods

### NewCreateProject201Response

`func NewCreateProject201Response(success bool, project CreateProject201ResponseProject, ) *CreateProject201Response`

NewCreateProject201Response instantiates a new CreateProject201Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCreateProject201ResponseWithDefaults

`func NewCreateProject201ResponseWithDefaults() *CreateProject201Response`

NewCreateProject201ResponseWithDefaults instantiates a new CreateProject201Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetSuccess

`func (o *CreateProject201Response) GetSuccess() bool`

GetSuccess returns the Success field if non-nil, zero value otherwise.

### GetSuccessOk

`func (o *CreateProject201Response) GetSuccessOk() (*bool, bool)`

GetSuccessOk returns a tuple with the Success field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSuccess

`func (o *CreateProject201Response) SetSuccess(v bool)`

SetSuccess sets Success field to given value.


### GetProject

`func (o *CreateProject201Response) GetProject() CreateProject201ResponseProject`

GetProject returns the Project field if non-nil, zero value otherwise.

### GetProjectOk

`func (o *CreateProject201Response) GetProjectOk() (*CreateProject201ResponseProject, bool)`

GetProjectOk returns a tuple with the Project field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProject

`func (o *CreateProject201Response) SetProject(v CreateProject201ResponseProject)`

SetProject sets Project field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


