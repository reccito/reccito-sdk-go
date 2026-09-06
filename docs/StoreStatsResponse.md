# StoreStatsResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**StoreId** | **string** |  | 
**StoreName** | **string** |  | 
**ReceiptsCreatedCount** | **int32** |  | 
**ReceiptsCreatedToday** | **int32** |  | 
**ReceiptsCreatedThisMonth** | **int32** |  | 
**QrScansCount** | **int32** |  | 
**QrScansToday** | **int32** |  | 
**QrScansThisMonth** | **int32** |  | 
**TotalAmountThisMonth** | **string** |  | 
**AverageReceiptAmount** | **string** |  | 
**LastReceiptCreated** | Pointer to **NullableTime** |  | [optional] 
**BusiestHour** | Pointer to **NullableString** |  | [optional] 
**BusiestDay** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewStoreStatsResponse

`func NewStoreStatsResponse(storeId string, storeName string, receiptsCreatedCount int32, receiptsCreatedToday int32, receiptsCreatedThisMonth int32, qrScansCount int32, qrScansToday int32, qrScansThisMonth int32, totalAmountThisMonth string, averageReceiptAmount string, ) *StoreStatsResponse`

NewStoreStatsResponse instantiates a new StoreStatsResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoreStatsResponseWithDefaults

`func NewStoreStatsResponseWithDefaults() *StoreStatsResponse`

NewStoreStatsResponseWithDefaults instantiates a new StoreStatsResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetStoreId

`func (o *StoreStatsResponse) GetStoreId() string`

GetStoreId returns the StoreId field if non-nil, zero value otherwise.

### GetStoreIdOk

`func (o *StoreStatsResponse) GetStoreIdOk() (*string, bool)`

GetStoreIdOk returns a tuple with the StoreId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreId

`func (o *StoreStatsResponse) SetStoreId(v string)`

SetStoreId sets StoreId field to given value.


### GetStoreName

`func (o *StoreStatsResponse) GetStoreName() string`

GetStoreName returns the StoreName field if non-nil, zero value otherwise.

### GetStoreNameOk

`func (o *StoreStatsResponse) GetStoreNameOk() (*string, bool)`

GetStoreNameOk returns a tuple with the StoreName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStoreName

`func (o *StoreStatsResponse) SetStoreName(v string)`

SetStoreName sets StoreName field to given value.


### GetReceiptsCreatedCount

`func (o *StoreStatsResponse) GetReceiptsCreatedCount() int32`

GetReceiptsCreatedCount returns the ReceiptsCreatedCount field if non-nil, zero value otherwise.

### GetReceiptsCreatedCountOk

`func (o *StoreStatsResponse) GetReceiptsCreatedCountOk() (*int32, bool)`

GetReceiptsCreatedCountOk returns a tuple with the ReceiptsCreatedCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptsCreatedCount

`func (o *StoreStatsResponse) SetReceiptsCreatedCount(v int32)`

SetReceiptsCreatedCount sets ReceiptsCreatedCount field to given value.


### GetReceiptsCreatedToday

`func (o *StoreStatsResponse) GetReceiptsCreatedToday() int32`

GetReceiptsCreatedToday returns the ReceiptsCreatedToday field if non-nil, zero value otherwise.

### GetReceiptsCreatedTodayOk

`func (o *StoreStatsResponse) GetReceiptsCreatedTodayOk() (*int32, bool)`

GetReceiptsCreatedTodayOk returns a tuple with the ReceiptsCreatedToday field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptsCreatedToday

`func (o *StoreStatsResponse) SetReceiptsCreatedToday(v int32)`

SetReceiptsCreatedToday sets ReceiptsCreatedToday field to given value.


### GetReceiptsCreatedThisMonth

`func (o *StoreStatsResponse) GetReceiptsCreatedThisMonth() int32`

GetReceiptsCreatedThisMonth returns the ReceiptsCreatedThisMonth field if non-nil, zero value otherwise.

### GetReceiptsCreatedThisMonthOk

`func (o *StoreStatsResponse) GetReceiptsCreatedThisMonthOk() (*int32, bool)`

GetReceiptsCreatedThisMonthOk returns a tuple with the ReceiptsCreatedThisMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReceiptsCreatedThisMonth

`func (o *StoreStatsResponse) SetReceiptsCreatedThisMonth(v int32)`

SetReceiptsCreatedThisMonth sets ReceiptsCreatedThisMonth field to given value.


### GetQrScansCount

`func (o *StoreStatsResponse) GetQrScansCount() int32`

GetQrScansCount returns the QrScansCount field if non-nil, zero value otherwise.

### GetQrScansCountOk

`func (o *StoreStatsResponse) GetQrScansCountOk() (*int32, bool)`

GetQrScansCountOk returns a tuple with the QrScansCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrScansCount

`func (o *StoreStatsResponse) SetQrScansCount(v int32)`

SetQrScansCount sets QrScansCount field to given value.


### GetQrScansToday

`func (o *StoreStatsResponse) GetQrScansToday() int32`

GetQrScansToday returns the QrScansToday field if non-nil, zero value otherwise.

### GetQrScansTodayOk

`func (o *StoreStatsResponse) GetQrScansTodayOk() (*int32, bool)`

GetQrScansTodayOk returns a tuple with the QrScansToday field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrScansToday

`func (o *StoreStatsResponse) SetQrScansToday(v int32)`

SetQrScansToday sets QrScansToday field to given value.


### GetQrScansThisMonth

`func (o *StoreStatsResponse) GetQrScansThisMonth() int32`

GetQrScansThisMonth returns the QrScansThisMonth field if non-nil, zero value otherwise.

### GetQrScansThisMonthOk

`func (o *StoreStatsResponse) GetQrScansThisMonthOk() (*int32, bool)`

GetQrScansThisMonthOk returns a tuple with the QrScansThisMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetQrScansThisMonth

`func (o *StoreStatsResponse) SetQrScansThisMonth(v int32)`

SetQrScansThisMonth sets QrScansThisMonth field to given value.


### GetTotalAmountThisMonth

`func (o *StoreStatsResponse) GetTotalAmountThisMonth() string`

GetTotalAmountThisMonth returns the TotalAmountThisMonth field if non-nil, zero value otherwise.

### GetTotalAmountThisMonthOk

`func (o *StoreStatsResponse) GetTotalAmountThisMonthOk() (*string, bool)`

GetTotalAmountThisMonthOk returns a tuple with the TotalAmountThisMonth field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalAmountThisMonth

`func (o *StoreStatsResponse) SetTotalAmountThisMonth(v string)`

SetTotalAmountThisMonth sets TotalAmountThisMonth field to given value.


### GetAverageReceiptAmount

`func (o *StoreStatsResponse) GetAverageReceiptAmount() string`

GetAverageReceiptAmount returns the AverageReceiptAmount field if non-nil, zero value otherwise.

### GetAverageReceiptAmountOk

`func (o *StoreStatsResponse) GetAverageReceiptAmountOk() (*string, bool)`

GetAverageReceiptAmountOk returns a tuple with the AverageReceiptAmount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAverageReceiptAmount

`func (o *StoreStatsResponse) SetAverageReceiptAmount(v string)`

SetAverageReceiptAmount sets AverageReceiptAmount field to given value.


### GetLastReceiptCreated

`func (o *StoreStatsResponse) GetLastReceiptCreated() time.Time`

GetLastReceiptCreated returns the LastReceiptCreated field if non-nil, zero value otherwise.

### GetLastReceiptCreatedOk

`func (o *StoreStatsResponse) GetLastReceiptCreatedOk() (*time.Time, bool)`

GetLastReceiptCreatedOk returns a tuple with the LastReceiptCreated field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLastReceiptCreated

`func (o *StoreStatsResponse) SetLastReceiptCreated(v time.Time)`

SetLastReceiptCreated sets LastReceiptCreated field to given value.

### HasLastReceiptCreated

`func (o *StoreStatsResponse) HasLastReceiptCreated() bool`

HasLastReceiptCreated returns a boolean if a field has been set.

### SetLastReceiptCreatedNil

`func (o *StoreStatsResponse) SetLastReceiptCreatedNil(b bool)`

 SetLastReceiptCreatedNil sets the value for LastReceiptCreated to be an explicit nil

### UnsetLastReceiptCreated
`func (o *StoreStatsResponse) UnsetLastReceiptCreated()`

UnsetLastReceiptCreated ensures that no value is present for LastReceiptCreated, not even an explicit nil
### GetBusiestHour

`func (o *StoreStatsResponse) GetBusiestHour() string`

GetBusiestHour returns the BusiestHour field if non-nil, zero value otherwise.

### GetBusiestHourOk

`func (o *StoreStatsResponse) GetBusiestHourOk() (*string, bool)`

GetBusiestHourOk returns a tuple with the BusiestHour field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusiestHour

`func (o *StoreStatsResponse) SetBusiestHour(v string)`

SetBusiestHour sets BusiestHour field to given value.

### HasBusiestHour

`func (o *StoreStatsResponse) HasBusiestHour() bool`

HasBusiestHour returns a boolean if a field has been set.

### SetBusiestHourNil

`func (o *StoreStatsResponse) SetBusiestHourNil(b bool)`

 SetBusiestHourNil sets the value for BusiestHour to be an explicit nil

### UnsetBusiestHour
`func (o *StoreStatsResponse) UnsetBusiestHour()`

UnsetBusiestHour ensures that no value is present for BusiestHour, not even an explicit nil
### GetBusiestDay

`func (o *StoreStatsResponse) GetBusiestDay() string`

GetBusiestDay returns the BusiestDay field if non-nil, zero value otherwise.

### GetBusiestDayOk

`func (o *StoreStatsResponse) GetBusiestDayOk() (*string, bool)`

GetBusiestDayOk returns a tuple with the BusiestDay field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBusiestDay

`func (o *StoreStatsResponse) SetBusiestDay(v string)`

SetBusiestDay sets BusiestDay field to given value.

### HasBusiestDay

`func (o *StoreStatsResponse) HasBusiestDay() bool`

HasBusiestDay returns a boolean if a field has been set.

### SetBusiestDayNil

`func (o *StoreStatsResponse) SetBusiestDayNil(b bool)`

 SetBusiestDayNil sets the value for BusiestDay to be an explicit nil

### UnsetBusiestDay
`func (o *StoreStatsResponse) UnsetBusiestDay()`

UnsetBusiestDay ensures that no value is present for BusiestDay, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


