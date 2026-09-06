# ReceiptListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Receipts** | [**[]ReceiptSummary**](ReceiptSummary.md) |  | 
**Total** | **int32** |  | 
**Page** | **int32** |  | 
**Limit** | **int32** |  | 
**HasNext** | **bool** |  | 
**HasPrev** | **bool** |  | 

## Methods

### NewReceiptListResponse

`func NewReceiptListResponse(receipts []ReceiptSummary, total int32, page int32, limit int32, hasNext bool, hasPrev bool, ) *ReceiptListResponse`

NewReceiptListResponse instantiates a new ReceiptListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewReceiptListResponseWithDefaults

`func NewReceiptListResponseWithDefaults() *ReceiptListResponse`

NewReceiptListResponseWithDefaults instantiates a new ReceiptListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetReceipts

`func (o *ReceiptListResponse) GetReceipts() []ReceiptSummary`

GetReceipts returns the Receipts field if non-nil, zero value otherwise.

### GetReceiptsOk

`func (o *ReceiptListResponse) GetReceiptsOk() (*[]ReceiptSummary, bool)`

GetReceiptsOk returns a tuple with the Receipts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceipts

`func (o *ReceiptListResponse) SetReceipts(v []ReceiptSummary)`

SetReceipts sets Receipts field to given value.


### GetTotal

`func (o *ReceiptListResponse) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ReceiptListResponse) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ReceiptListResponse) SetTotal(v int32)`

SetTotal sets Total field to given value.


### GetPage

`func (o *ReceiptListResponse) GetPage() int32`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ReceiptListResponse) GetPageOk() (*int32, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ReceiptListResponse) SetPage(v int32)`

SetPage sets Page field to given value.


### GetLimit

`func (o *ReceiptListResponse) GetLimit() int32`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *ReceiptListResponse) GetLimitOk() (*int32, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *ReceiptListResponse) SetLimit(v int32)`

SetLimit sets Limit field to given value.


### GetHasNext

`func (o *ReceiptListResponse) GetHasNext() bool`

GetHasNext returns the HasNext field if non-nil, zero value otherwise.

### GetHasNextOk

`func (o *ReceiptListResponse) GetHasNextOk() (*bool, bool)`

GetHasNextOk returns a tuple with the HasNext field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasNext

`func (o *ReceiptListResponse) SetHasNext(v bool)`

SetHasNext sets HasNext field to given value.


### GetHasPrev

`func (o *ReceiptListResponse) GetHasPrev() bool`

GetHasPrev returns the HasPrev field if non-nil, zero value otherwise.

### GetHasPrevOk

`func (o *ReceiptListResponse) GetHasPrevOk() (*bool, bool)`

GetHasPrevOk returns a tuple with the HasPrev field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHasPrev

`func (o *ReceiptListResponse) SetHasPrev(v bool)`

SetHasPrev sets HasPrev field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


