# PaginationInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Page** | **int32** | Current page number | 
**Limit** | **int32** | Items per page | 
**Total** | **int32** | Total number of items | 
**HasNext** | **bool** | Whether there is a next page | 

## Methods

### NewPaginationInfo

`func NewPaginationInfo(page int32, limit int32, total int32, hasNext bool, ) *PaginationInfo`

NewPaginationInfo instantiates a new PaginationInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPaginationInfoWithDefaults

`func NewPaginationInfoWithDefaults() *PaginationInfo`

NewPaginationInfoWithDefaults instantiates a new PaginationInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPage

`func (o *PaginationInfo) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *PaginationInfo) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *PaginationInfo) SetPage(v int32)`

SetPage sets Page field to given value.


### GetLimit

`func (o *PaginationInfo) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *PaginationInfo) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *PaginationInfo) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### GetTotal

`func (o *PaginationInfo) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *PaginationInfo) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *PaginationInfo) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetHasNext

`func (o *PaginationInfo) GetHasNext() bool`

GetHasNext returns the HasNext field if non-nil, zero value otherwise.

### GetHasNextOk

`func (o *PaginationInfo) GetHasNextOk() (*bool, bool)`

GetHasNextOk returns a tuple with the HasNext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasNext

`func (o *PaginationInfo) SetHasNext(v bool)`

SetHasNext sets HasNext field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


