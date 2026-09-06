# StoreListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Stores** | [**[]StoreResponse**](StoreResponse.md) |  | 
**Total** | **int32** |  | 

## Methods

### NewStoreListResponse

`func NewStoreListResponse(stores []StoreResponse, total int32, ) *StoreListResponse`

NewStoreListResponse instantiates a new StoreListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoreListResponseWithDefaults

`func NewStoreListResponseWithDefaults() *StoreListResponse`

NewStoreListResponseWithDefaults instantiates a new StoreListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStores

`func (o *StoreListResponse) GetStores() []StoreResponse`

GetStores returns the Stores field if non-nil, zero value otherwise.

### GetStoresOk

`func (o *StoreListResponse) GetStoresOk() (*[]StoreResponse, bool)`

GetStoresOk returns a tuple with the Stores field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStores

`func (o *StoreListResponse) SetStores(v []StoreResponse)`

SetStores sets Stores field to given value.


### GetTotal

`func (o *StoreListResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *StoreListResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *StoreListResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


